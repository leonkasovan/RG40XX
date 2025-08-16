# RG40XX
Anbernic RG40XX Knowledge

## Anbernic Stock OS: 202502

Connect via SSH
```
user: root
password: root

ssh root@192.168.1.40
```

Install package
`apt-get install gcc make lua5.1 zip libdrm-dev libxxf86vm-dev nano mc`

Stop Main Menu
`/etc/init.d/launcher.sh stop`

Change Default Language to English
```
nano /etc/default/locale
LANG="en_US.UTF-8"
LANGUAGE="en_US:en"
LC_ALL="en_US.UTF-8"

run:
locale-gen en_US.UTF-8
update-locale LANG=en_US.UTF-8
```

Install Pico8 Native in EXPERT
```
extract pico-8_0.2.6b_raspi.zip:
1. pico8_64
2. pico8.dat

Put in /mnt/mmc/EXE/pico-8
create empty file: splore
```

Add new APPS
```
cd /mnt/mmc/Roms/APPS
nano My_New_Apps.sh
```

