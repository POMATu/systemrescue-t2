# systemrescue-t2
SystemRescueCD with patched kernel for t2 based macs

Just vanilla systemrescuecd with extra kpartx and mosh packages and arch t2-lts kernel

You can dd this ISO onto USB stick or create fat32 partition on your mac, label filesystem as RESCUE1101 and just unpack ISO init, this way you can boot systemrescuecd as an extra OS with ability to edit it: for example add your own custom scripts, change grub default option to boot to ram or even specifying yaml automation config in systemrescuecd format.

I am using this for doing clean automated drive-imaged backups.

# Information about yaml configuration, scripting and etc

https://www.system-rescue.org/
