mongo-pi
========

Raspbian package for MongoDB. The binaries were lifted from https://github.com/brice-morin/ArduPi/tree/master/mongodb-rpi. The service script was lifted from https://github.com/brice-morin/ArduPi/tree/master/mongodb-rpi (and changed to make it work).

Create the package by running:

	equivs-build -a armhf mongo-pi

You'll get a .deb file that you can install on your RPi.
