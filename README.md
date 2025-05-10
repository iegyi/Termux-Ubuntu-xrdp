# Termux-Ubuntu-xrdp

proot-distro login ubuntu

nano ../usr/etc/xrdp/xrdp.ini

vncserver -xstartup ../usr/bin/startxfce4 -listen tcp :1

kill pids
xrdp -k
vncserver -xstartup ../usr/bin/startxfce4 -listen tcp :1 -kill :1
