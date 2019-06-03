## Manual Installation for sigrok-firmware-fx2lafw on Ubuntu 18.04

Requirements
------------
 - git
 - make
 - autoconf >= 2.63
 - automake >= 1.11
 - sdcc (>= 2.9.0)
 
 
 ### Install SDCC compiler
 
 In order to build fx2lafw you need the 'sdcc' compiler (>= 2.9.0)
 
     $ apt-get install sdcc
     

Building and installing sigrok-firmware-fx2lafw
------------------------------------------------

In order to get the sigrok-firmware-fx2lafw source code and build it, run:

 $ git clone git://sigrok.org/sigrok-firmware-fx2lafw
 $ cd sigrok-firmware-fx2lafw
 $ ./autogen.sh
 $ ./configure
 $ make
 $ make install
