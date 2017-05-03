A Qt gui to control and debug the the BLDC controller. 
More information and tutorial about how to use it can be found here: http://vedder.se/2015/01/vesc-open-source-esc/
and here https://www.electric-skateboard.builders/t/extended-bldc-tool-with-watt-control-mode-ppm-cruise-control-individual-throttle-curve-and-android-app/12286

Quick build instructions for Ubuntu:

1. `sudo apt-get install qtcreator qt-sdk libudev-dev libqt5serialport5-dev`

2. `qmake -qt=qt5`

3. `make clean && make`

4. Allow for serial access without using sudo: `sudo adduser $USER dialout`

5. Restart for access changes to take effect `sudo reboot now`

6. Start BLDC-tool from inside of the built repo `./BLDC_Tool`
