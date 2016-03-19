
# floppymusic

This repo contains melodies, written in C++, to be played using Raspberry Pi and floppy disk drive 
This was made using [XtraPerianer's guide](https://xtraperianer.wordpress.com/2014/08/06/making-floppy-music-with-a-raspberry-pi/?lang=en)

## To assemble this you need:

* Raspberry Pi
* floppy disk drive
* power source; it's perfect if you have one from an old PC, it should be 5V
* wires to connect everything, e.g. the power source and the battery
* jumper wires or jumpers

Also you need to install [wiringPi lib](http://wiringpi.com/) in order to run the code.

## Compile and run

First check if you have c++ compiler on you Raspberry, and install it if you don't:

```shell
sudo apt-get install g++
``` 

Then go to directory with your code (You can get an example [here](https://www.raspberrypi.org/forums/viewtopic.php?f=41&t=69947)):

```shell
g++ music.cpp -o music -lwiringPi
```

You should now be able to run the Programm by simply typing:

```shell
./music
```

## Guides on the Internet

* http://projects-raspberry.com/floppy-drive-music-w-raspberry-pi/
* https://xtraperianer.wordpress.com/2014/08/06/making-floppy-music-with-a-raspberry-pi/?lang=en

And original code source:

* https://www.raspberrypi.org/forums/viewtopic.php?f=41&t=69947

