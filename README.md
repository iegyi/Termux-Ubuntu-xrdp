# Termux-Ubuntu-xrdp

proot-distro login ubuntu

nano ../usr/etc/xrdp/xrdp.ini

vncserver -xstartup ../usr/bin/startxfce4 -listen tcp :1

vncserver -start

kill pids
xrdp -k
vncserver -xstartup ../usr/bin/startxfce4 -listen tcp :1 -kill :1


##
pkg install xfce4 xfce4-goodies tigervnc xrdp 


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

install apps
pkg install firefox
pkg install chromium 
pkg install code-oss
pkg install tur-repo 
pkg install gimp
pkg search vlc
pkg install transmission-gtk
pkg install evince
 