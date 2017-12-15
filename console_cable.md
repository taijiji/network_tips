# How to use Cosole Cable on Mac

```
ls -l /dev/tty.*

crw-rw-rw-  1 root  wheel   20,   4 Nov 29 06:22 /dev/tty.Bluetooth-Incoming-Port
crw-rw-rw-  1 root  wheel   20,   0 Nov 29 06:22 /dev/tty.MALS
crw-rw-rw-  1 root  wheel   20,   2 Nov 29 06:22 /dev/tty.SOC
crw-rw-rw-  1 root  wheel   20,  22 Dec 15 11:22 /dev/tty.usbserial-FTY4QKR3
```

# For Cumulus Linix
The default serial console baud rate is 115200

```
screen /dev/tty.usbserial-FTY4QKR3 115200
```

# For Cisco/Juniper

```
screen /dev/tty.usbserial-FTY4QKR3 9600
```