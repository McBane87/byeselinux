# byeselinux<br>
<br>
Android kernel module to bypass SELinux at boot. Made for XZDualRecovery (Xperia) and Lollipop firmwares.<br>
<br>
This is just a copy for my own.<br>
Original Sources can be found here: https://github.com/dosomder/byeselinux<br>
<br>
<br>
### Tested on Ubuntu 14.04 ###<br>
<br>
First change Path to your Kernel Source in "make.sh"<br>
KERNEL_BUILD=/path/to/kernel/source<br>
<br>
Install Cross-Compiler:<br>
apt-get install gcc-arm-linux-androideabi<br>
<br>
compiling using "./make.sh" or ./make.sh arm64<br>
cleaning using "./make.sh clean"
