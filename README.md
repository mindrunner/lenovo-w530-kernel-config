# Kernel config for my lenovo w530

- Based on a minimalistic config from kernel seeds
- Targeting ~amd64 Gentoo Linux running on systemd or openrc (untested)
- Set default hostname to w530
- Kernel and initramfs must be gzip-compressed
- No bluetooth support yet

Added support for:
- intel sata chipset
- intel GPU
- iwlwifi
- e100e ethernet
- webcam
- mmc/sdcard
- usb 3
- logitech unified receiver
- ACPI battery
- suspend to ram
- thinkpad ACPI extras
- intel coretemp
- intel cpuidle
- initramfs
- early cryptsetup
- KVM
- HD audio with Realtec codec
- ext2/3/4
- btrfs
- dosfs
- android USB tethering

Probably more stuff I already forgot....
