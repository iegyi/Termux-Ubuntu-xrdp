# Termux-Ubuntu-xrdp

proot-distro login ubuntu

nano ../usr/etc/xrdp/xrdp.ini

vncserver -xstartup ../usr/bin/startxfce4 -listen tcp :1

kill pids
xrdp -k
vncserver -xstartup ../usr/bin/startxfce4 -listen tcp :1 -kill :1



another way of installing

pkg update
pkg install x11-repo
pkg install termux-x11-nightly
pkg install pulseaudio
pkg install proot-distro

proot-distro install ubuntu
proot-distro login ubuntu
apt-get update 
apt-get install xfce4
exit


Install apps

pkg install tur-repo
pkg install chromium -y
pkg install code-oss

