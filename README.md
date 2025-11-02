# Socialblocklist
Ubuntu
sudo -i
apt-get install mdadm lvm2
mdadm -AsfR && vgchange -ay
fdisk -l | grep /dev/sd
mdadm -Ee0.swap /dev/sda* /dev/sdb*
mdadm -AU byteorder /dev/md0 /dev/sda* /dev/sdb*

find . -type d -name "@eaDir" -print0 | xargs -0 rm -rf


https://github.com/danhorton7 - tiktok
https://github.com/nickoppen/pihole-blocklists
https://bgp.tools/tags/vpsh
https://github.com/nickoppen/pihole-blocklists
https://github.com/ninjayoto/PornList/blob/master/PornList.txt
https://github.com/blocklistproject/Lists/tree/master
