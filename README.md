# Flyme Patchrom for Bq Aquaris M5, aka piccolo
![Flyme 6 Logo](https://raw.githubusercontent.com/NESPTechnology/FlymeOS_devices_P8Lite/android-6.0/images/flyme.png)


To get started with Flyme patchrom, you'll need to get familiar with Git and Repo. 

# Getting Started

```bash

mkdir flyme

cd flyme

repo init -u https://github.com/FlymeOS/manifest.git -b nougat-7.1

repo sync -c -j4

git clone https://github.com/aymende7/flyme_devices_piccolo -b nougat-7.1_caf devices/piccolo
```

# Build
```bash
. build/envsetup.sh  

cd devices/piccolo

flyme fullota
```
