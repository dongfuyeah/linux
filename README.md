# linux

****************************flash*****************************
## Adobe Repository 64-bit x86_64 ##
 rpm -ivh http://linuxdownload.adobe.com/adobe-release/adobe-release-x86_64-1.0-1.noarch.rpm
rpm --import /etc/pki/rpm-gpg/RPM-GPG-KEY-adobe-linux
# Fedora 25/24 #
dnf install flash-plugin alsa-plugins-pulseaudio libcurl
https://www.if-not-true-then-false.com/2010/install-adobe-flash-player-10-on-fedora-centos-red-hat-rhel/


******************************vlc************************
rpmfusion-nonfree-release-22.noarch.rpm
rpmfusion-free-release-22.noarch.rpm
dnf install vlc

*******************ipv6**************
修改/etc/ppp/options，在檔案加上最後一行ipv6 ,，這邊要注意的是"ipv6 ,"，有空格和逗號。
http://m.xuite.net/blog/zack_pan/blog/62384661

*******************network*************
yum install *wifi
yum install NetworkManager
yum install *pppoe


