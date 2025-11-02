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
Cloudflare: ASN: AS395747
AS394536
AS209242
AS203898
AS202623
AS14789
AS139242
AS133877
AS13335
AS132892
