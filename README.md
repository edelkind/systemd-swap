# systemd-swap
Script for auto create and mount: zram swaps, swap files (through loop) devices, swap partitions
Num of zram devices = num of cpu's cores.
It configurable in /etc/systemd-swap.conf
Source:
```
/etc/systemd/system/systemd-swap.service
/etc/systemd-swap.conf
/usr/lib/systemd/scripts/systemd-swap.sh
```
Using:
```
# systemctl enable systemd-swap
```
* ![logo](http://www.monitorix.org/imgs/archlinux.png "arch logo")Arch: in the [AUR](https://aur.archlinux.org/packages/systemd-swap/).