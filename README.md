Wireguard SPK for your Synology NAS
===================================

This installable package for the Synology DS1522+
It is compiled for the AMD Ryzen R1600 CPU (r1000 Architecture type).
See: https://kb.synology.com/en-global/DSM/tutorial/What_kind_of_CPU_does_my_NAS_have


The following following command was used:
```
sudo docker run --rm --privileged --env PACKAGE_ARCH=r1000 --env DSM_VER=7.1 -v /home/jni/Dev/temp_synobuild71:/result_spk blackvoidclub/synobuild71
```

Source:
https://www.blackvoid.club/wireguard-spk-for-your-synology-nas/

