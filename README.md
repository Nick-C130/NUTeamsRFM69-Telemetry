# RFM69 Library
[![license](https://img.shields.io/github/license/LowPowerLab/RFM69.svg)](https://github.com/LowPowerLab/RFM69/blob/master/LICENSE.txt)

Origanally by Felix Rusu, [LowPowerLab.com](http://LowPowerLab.com) Modified for NuTeams by Nicholas Cummings
<br/>
RFM69 library for complete telemetry for NuTeams
<br/>
The latest examples, new features and bug fixes are found in the [original repository](https://github.com/LowPowerLab/RFM69) of this library.

## License
GPL 3.0, please see the [License.txt](https://github.com/LowPowerLab/RFM69/blob/master/License.txt) file for details. Be sure to include the same license with any fork or redistribution of this library.

## Features
- easy to use 
- Simple control for many devices
- Automatic rocket ID checks
- Automatic tranmission control
- Automatic transmission deconfliction

### Library Installation (Arduino IDE)
Copy the content of this library in the "Arduino/libraries/NuTeamsRFM69" folder.
<br />
To find your Arduino folder go to File>Preferences in the Arduino IDE.
<br/>
See [this tutorial](https://www.arduino.cc/en/Guide/Libraries) on Arduino libraries.

### Hardware & programming
See examples for code and data formatts
Ensure there is no delay in void Loop() to ensure the best operation of the automatic identification/deconfliction systems