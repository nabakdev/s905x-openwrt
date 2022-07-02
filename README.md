### Recomended build

- openwrt-21.\* => kernel 5.4.\*
- openwrt-22.\* => kernel 5.10.\*
- openwrt-23.\* => kernel 5.15.\*

### Burn to SDCARD

`zcat [firmware.img.gz] | sudo dd of=/dev/sdX bs=2M conv=fsync status=progress`
