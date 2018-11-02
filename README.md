
# JAVA JDK (online)
```bash
sudo  apt-get install openjdk-8-jdk
```


# JAVA JDK (offline)


# Eclipse #


# Instlall STLinkV2 #
## NOTE: download STlinkV2 and rules 
## NOTE: makesure runing it under sudo 
#


```bash 
sudo apt-get install libusb-1.0
sudo apt-get install autoconf
```

```bash
cd stlink
./autogen.sh
./configure
make
make install
``` 
## NOTE: you can verify by follow command  
## whereis st-flash


## NOTE: move rulefile to the /etc/udev/rules.d

```bash
cd /toolchain
sudo cp 49-stlinkv1.rules 49-stlinkv2.rules 49-stlinkv2-1.rules /etc/udev/rules.d
sudo service udev resart
```
## NOTE: st-info --chipid  
# Install gcc-arm-none #



```bash
sudo tar -xzvf file.tar.gz             ##exart here
sudo tar -xzvf file.tar.gz -C /home    ##exart to home
sudo tar -jxvf FileName.tar.bz2    
sudo tar -jcvf FileName.tar.bz2 DirName 

nano ~/.profile
source ~/.profile
```


Install gcc-arm-none
source /etc/profile

sudo gedit /etc/profile

```bash
 sudo tar -jxvf gcc-arm-none-eabi-6-2017-q2-linux.tar.bz2 -C /usr/bin
```


```bash
 export PATH=$PATH:/usr/bin/gcc-arm-none-eabi-6-2017-q2-update/bin 
```

```bash
arm-none-eabi-gcc -v
```


STM32CubeMX on ubuntu
```bahs
sudo apt install libc6-i386
```