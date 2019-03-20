[![Build Status](https://travis-ci.org/synqs/YunTemp.svg?branch=master)](https://travis-ci.org/synqs/YunTemp)

# YunTemp
A simple Temp Control Simulator. The Yun Hardware etc will come here soon.  It's API is running on [heroku](https://yuntemp.herokuapp.com/).

# Installation

You can set this address to test the control of your temperature control with the [DeviceControlServer](https://github.com/synqs/DeviceControlServer).

## On the arduino

If you would like to go beyond the simple simple simulation you can also install it on your Arduino Yun. This in the end what this whole program was built for at [SynQS](http://www.kip.uni-heidelberg.de/synqs/). Simply upload the file _YunPutAndGet.ino.with_bootloader.yun.hex_ onto the Yun. This tells the arduino how to handle the API calls and it implements a simple PID control. The typical hardware is:
