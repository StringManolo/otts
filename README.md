# otts
Otts is a customized versión of an alpine linux designed to hacking using Termux on an Android OS without root.

## How to install?
Run the next command:
```
yes | pkg install proot-distro; git clone https://github.com/stringmanolo/otts && 7z x otts.7z && mv otts.override.sh /data/data/com.termux/files/usr/etc/proot-distro/ && mv otts /data/data/com.termux/files/usr/var/lib/proot-distro/installed-rootfs/otts && echo '#!/usr/bin/bash
proot-distro login otts' > ~/../usr/bin/otts && chmod +775 ~/../usr/bin/otts && otts
```

## How to run?
Run the next command
```
otts
```
