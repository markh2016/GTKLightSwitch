# GTKLightSwitch
GTK GUI Light switch for RPI All source code  supplied   with  make file 
to compile  simply run make 
Make sure you have the correct header file  install  the bcm2835 headers
Glade file included 

Details on this are below for installation on RPI


# download the latest version of the library, say bcm2835-1.xx.tar.gz, then:
tar zxvf bcm2835-1.xx.tar.gz
cd bcm2835-1.xx
./configure
make
sudo make check
sudo make install

All paths should be set on the  makefile but this may vary with  install  with regards the linux distro you are using

Enjoy 

