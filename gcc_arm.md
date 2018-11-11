# Install gcc-arm-none


```bash
sudo gedit /etc/profile
```

```bash
 sudo tar -jxvf gcc-arm-none-eabi-6-2017-q2-linux.tar.bz2 -C /usr/bin
```


```bash
 export PATH=$PATH:/usr/bin/gcc-arm-none-eabi-6-2017-q2-update/bin 
```

```bash
source /etc/profile
```

```bash
arm-none-eabi-gcc -v
```


STM32CubeMX on ubuntu
```bahs
sudo apt install libc6-i386
```
