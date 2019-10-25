# smartWinder
A module to smarten up "dumb" (non IOT-able) belt winders

The Project is based on the preliminary work in the FHEM forum which focused on connecting the existing GW60 electronic belt winder by Superrollo: https://forum.fhem.de/index.php/topic,60575.0.html
This repository is meant to keep the relevant information over the existing project and allow forther development.

# Working principle
The existing control unit was kept in place and extended with a secondary ESP8266 WiFi MCU.
Motion of the winder motor is fed in with 2 pins on the ESP.
The position can be determined via an magnetic sensor, either with the integrated hall sensor which is measuring the rotations of the winder or an additional placed hall Sensor which is measuring the rotations of the deflection roller.
The ESP gets control over the movement of the belt winder via two pins which simulate presses on the up and down key.

# Further ideas
- Extending more other comparably working belt winders
- Controlling other Devices which control the position of an object like Garage doors, etc.

# Credits
Great thanks to the FHEM community for all current and furher development and research on the topic https://forum.fhem.de/index.php/topic,60575.0.html
