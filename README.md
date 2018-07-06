A Qt gui to control and debug the the BLDC controller. 

This is a modified version of the original bldc-tool by Benjamin Vedder.

More information and tutorial about how to use it can be found here: http://vedder.se/2015/01/vesc-open-source-esc/
and here https://www.electric-skateboard.builders/t/extended-bldc-tool-with-watt-control-mode-ppm-cruise-control-individual-throttle-curve-and-android-app/12286

Quick build instructions for Ubuntu:

1. `sudo apt-get install qtcreator qt-sdk libudev-dev libqt5serialport5-dev`

2. `qmake -qt=qt5`

3. `make clean && make`

4. Allow for serial access without using sudo: `sudo adduser $USER dialout`

5. Restart for access changes to take effect `sudo reboot now`

6. Start BLDC-tool from inside of the built repo `./BLDC_Tool`

This is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
The software is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.
You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses

