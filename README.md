# Qcow2.image
Disk image format!

# Compress
```
compressAndShrink(){
  # https://pve.proxmox.com/wiki/Shrink_Qcow2_Disk_Files
  # example:
  qemu-img convert -p -O qcow2 -c gamedata.qcow2 gamedata.qcow2_backup
}
```
