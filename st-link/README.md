# stlink on ubuntu #
## install necessary parts
```bash
sudo apt-get install libusb-1.0
sudo apt-get install autoconf
```
NOTE: befor necessary make sure you have already 
```bash
sudo apt-get update
```
## install stlink
```bash
cd stlink
./autogen.sh
./configure
make
make install
```
## NOTE: you can verify by follow command  
```bash
whereis st-flash
```

# HAVE FUN!!!
