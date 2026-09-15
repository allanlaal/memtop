# install

put it in your favourite bin dir
chmod +x
run with root to get complete overview

# EXAMPLE

```
2026-09-15 21:07:08 root@S7:/home/allan$ /abin/memtop
========================================================================================================================
                                           NUMA SYSTEM-WIDE OVERVIEW                                                    
========================================================================================================================
Node         | Size         | Free         | PageCache    | Slab (Kernel) | Shmem (tmpfs)
========================================================================================================================
node0        |  283.3 GiB   |   68.6 GiB   |   26.8 GiB   |   16.2 GiB   |   26.2 GiB  
node1        |  141.7 GiB   |   22.9 GiB   |   24.6 GiB   |    6.0 GiB   |   23.1 GiB  
========================================================================================================================
TOTAL        |  425.0 GiB   |   91.5 GiB   |   51.4 GiB   |   22.2 GiB   |   49.3 GiB  

========================================================================================================================
                                     PROCESS & TMPFS ALLOCATION PER NUMA NODE                                           
========================================================================================================================
Program / Mount                                         | Node 0       | Node 1       | Total RAM ↓
--------------------------------------------------------+--------------+--------------+--------------
firefox-bin                                             |   62.4 GiB   |  129.3 MiB   |   62.6 GiB  
firefox-esr                                             |   37.4 GiB   |  126.1 MiB   |   37.6 GiB  
idea                                                    |   13.7 GiB   |   16.0 GiB   |   29.6 GiB  
FS:/home/allan/.cache/JetBrains                         |   16.0 GiB   |        -     |   16.0 GiB  
firefox                                                 |  469.9 MiB   |    7.8 GiB   |    8.3 GiB  
qemu-system-x86_64                                      |    3.2 GiB   |    3.5 GiB   |    6.7 GiB  
opencode.exe                                            |    2.8 GiB   |    2.4 GiB   |    5.2 GiB  
FS:/run/user/1000                                       |    2.7 GiB   |        -     |    2.7 GiB  
opencode                                                |    1.0 GiB   |    1.5 GiB   |    2.5 GiB  
dartaotruntime                                          |    1.6 GiB   |  467.8 MiB   |    2.0 GiB  
java                                                    |  944.5 MiB   |    1.0 GiB   |    1.9 GiB  
FS:/tmp                                                 |    1.5 GiB   |        -     |    1.5 GiB  
bash                                                    |  671.0 MiB   |  482.6 MiB   |    1.1 GiB  
dart                                                    |  413.1 MiB   |  598.0 MiB   | 1011.2 MiB  
python3                                                 |  408.8 MiB   |  368.9 MiB   |  777.7 MiB  
dartvm                                                  |  497.9 MiB   |  188.2 MiB   |  686.0 MiB  
Xorg                                                    |  347.7 MiB   |  228.0 MiB   |  575.7 MiB  
mariadbd                                                |  247.2 MiB   |  298.2 MiB   |  545.5 MiB  
copilot                                                 |  396.9 MiB   |  109.4 MiB   |  506.3 MiB  
command-applet                                          |  183.2 MiB   |  294.4 MiB   |  477.6 MiB  
language_server_linux_x64                               |  278.1 MiB   |  197.6 MiB   |  475.6 MiB  
harper-ls                                               |  454.5 MiB   |  120.0 KiB   |  454.7 MiB  
php-fpm:                                                |  231.4 MiB   |  134.1 MiB   |  365.6 MiB  
mysqld                                                  |  330.9 MiB   |    9.7 MiB   |  340.6 MiB  
mate-terminal                                           |  170.0 MiB   |  133.6 MiB   |  303.7 MiB  
osemgrep                                                |   20.0 MiB   |  262.1 MiB   |  282.1 MiB  
agy                                                     |  162.9 MiB   |   67.2 MiB   |  230.1 MiB  
mate-settings-daemon                                    |  188.8 MiB   |    1.7 MiB   |  190.5 MiB  
gedit                                                   |   84.7 MiB   |   86.3 MiB   |  171.0 MiB  
docker-proxy                                            |  102.2 MiB   |   42.5 MiB   |  144.7 MiB  
sudo                                                    |  110.7 MiB   |   20.2 MiB   |  130.9 MiB  
apache2                                                 |   64.0 MiB   |   51.5 MiB   |  115.5 MiB  
atop                                                    |  107.9 MiB   |  484.0 KiB   |  108.4 MiB  
containerd-shim-runc-v2                                 |   87.0 MiB   |   16.4 MiB   |  103.4 MiB  
caja                                                    |   58.6 MiB   |   41.9 MiB   |  100.5 MiB  
audacious                                               |   58.1 MiB   |   39.9 MiB   |   98.0 MiB  
xdg-desktop-portal-gtk                                  |   67.7 MiB   |   21.4 MiB   |   89.0 MiB  
embeddings-server                                       |   87.0 MiB   |  580.0 KiB   |   87.6 MiB  
named                                                   |    8.9 MiB   |   78.5 MiB   |   87.4 MiB  
dockerd                                                 |   55.3 MiB   |   24.8 MiB   |   80.1 MiB  
bloc_linux_x64                                          |   52.6 MiB   |   24.7 MiB   |   77.3 MiB  
ssh                                                     |   52.0 MiB   |   21.1 MiB   |   73.1 MiB  
mount.fuse.sshfs                                        |   34.2 MiB   |   34.2 MiB   |   68.4 MiB  
sshd:                                                   |   45.7 MiB   |   18.4 MiB   |   64.1 MiB  
parcellite                                              |   34.5 MiB   |   25.4 MiB   |   59.8 MiB  
FS:/run/snapd/ns                                        |   59.7 MiB   |        -     |   59.7 MiB  
FS:/run                                                 |   59.7 MiB   |        -     |   59.7 MiB  
htop                                                    |   37.8 MiB   |   21.6 MiB   |   59.3 MiB  
su                                                      |   50.1 MiB   |    8.3 MiB   |   58.4 MiB  
traefik                                                 |   46.9 MiB   |    9.3 MiB   |   56.3 MiB  
marco                                                   |   17.5 MiB   |   29.3 MiB   |   46.8 MiB  
fuse-overlayfs                                          |   33.0 MiB   |   12.0 MiB   |   45.0 MiB  
pipewire-pulse                                          |   23.4 MiB   |   13.3 MiB   |   36.8 MiB  
wnck-applet                                             |   12.8 MiB   |   23.7 MiB   |   36.5 MiB  
containerd                                              |   29.4 MiB   |    6.7 MiB   |   36.2 MiB  
systemd-journald                                        |   23.5 MiB   |   11.0 MiB   |   34.5 MiB  
snyk-linux                                              |   30.6 MiB   |    3.4 MiB   |   34.0 MiB  
C:windowssystem32winedevice.exe                         |   22.3 MiB   |   11.6 MiB   |   33.9 MiB  
notify-osd                                              |   19.3 MiB   |   12.7 MiB   |   32.0 MiB  
snapd                                                   |   23.3 MiB   |    7.8 MiB   |   31.1 MiB  
notification-area-applet                                |   15.8 MiB   |   14.9 MiB   |   30.7 MiB  
node                                                    |   16.4 MiB   |   14.0 MiB   |   30.5 MiB  
pipewire                                                |   15.3 MiB   |   15.0 MiB   |   30.3 MiB  
jetbrainsd                                              |   14.9 MiB   |   15.4 MiB   |   30.2 MiB  
multipathd                                              |   26.3 MiB   |  908.0 KiB   |   27.2 MiB  
sh                                                      |   25.7 MiB   |    1.3 MiB   |   27.0 MiB  
xdg-desktop-portal                                      |   22.5 MiB   |    3.8 MiB   |   26.4 MiB  
vpnagentd                                               |   11.3 MiB   |   14.1 MiB   |   25.4 MiB  
mate-panel                                              |   12.8 MiB   |   12.4 MiB   |   25.3 MiB  
fwupd                                                   |   15.2 MiB   |    9.8 MiB   |   25.0 MiB  
clock-applet                                            |   15.0 MiB   |    9.8 MiB   |   24.8 MiB  
evolution-alarm-notify                                  |    9.6 MiB   |   15.1 MiB   |   24.7 MiB  
FS:/home/allan/.cache/mozilla                           |   23.2 MiB   |        -     |   23.2 MiB  
urfkilld                                                |    7.9 MiB   |   15.0 MiB   |   22.9 MiB  
mate-cpufreq-applet                                     |   17.7 MiB   |    4.1 MiB   |   21.8 MiB  
ibus-extension-gtk3                                     |    8.3 MiB   |   12.1 MiB   |   20.4 MiB  
upowerd                                                 |   19.6 MiB   |  520.0 KiB   |   20.1 MiB  
nm-applet                                               |   17.2 MiB   |    2.6 MiB   |   19.8 MiB  
polkit-mate-authentication-agent-1                      |    8.8 MiB   |   10.3 MiB   |   19.1 MiB  
agetty                                                  |   17.8 MiB   |    1.2 MiB   |   18.9 MiB  
wineserver64                                            |   17.0 MiB   |    1.3 MiB   |   18.3 MiB  
dbus-daemon                                             |   15.5 MiB   |    2.8 MiB   |   18.2 MiB  
ibus-ui-gtk3                                            |   10.8 MiB   |    7.2 MiB   |   18.0 MiB  
wireplumber                                             |   15.3 MiB   |    2.5 MiB   |   17.8 MiB  
docker-registry                                         |   12.0 MiB   |    5.8 MiB   |   17.8 MiB  
polkitd                                                 |   10.4 MiB   |    7.0 MiB   |   17.4 MiB  
init                                                    |    8.6 MiB   |    8.5 MiB   |   17.1 MiB  
evolution-source-registry                               |   15.2 MiB   |    1.1 MiB   |   16.4 MiB  
gnome-keyring-daemon                                    |    6.8 MiB   |    9.3 MiB   |   16.1 MiB  
canonical-livepatchd                                    |   11.2 MiB   |    4.4 MiB   |   15.7 MiB  
iscsid                                                  |   10.3 MiB   |    5.2 MiB   |   15.5 MiB  
previews_daemon                                         |   14.0 MiB   |    1.4 MiB   |   15.4 MiB  
x-session-manager                                       |   14.7 MiB   |  776.0 KiB   |   15.4 MiB  
gvfsd-metadata                                          |    3.0 MiB   |   12.2 MiB   |   15.2 MiB  
udisksd                                                 |   12.8 MiB   |    2.2 MiB   |   15.1 MiB  
fsnotifier                                              |   13.6 MiB   |  632.0 KiB   |   14.2 MiB  
NetworkManager                                          |    8.3 MiB   |    5.9 MiB   |   14.2 MiB  
xdg-permission-store                                    |   12.4 MiB   |    1.5 MiB   |   13.9 MiB  
systemd-resolved                                        |   12.8 MiB   |  952.0 KiB   |   13.7 MiB  
C:windowssystem32plugplay.exe                           |   11.1 MiB   |    2.6 MiB   |   13.6 MiB  
adb                                                     |    9.7 MiB   |    3.8 MiB   |   13.5 MiB  
docker                                                  |   11.2 MiB   |    2.0 MiB   |   13.2 MiB  
light-locker                                            |    5.6 MiB   |    7.6 MiB   |   13.1 MiB  
ibus-x11                                                |    9.1 MiB   |    3.9 MiB   |   13.0 MiB  
xdg-document-portal                                     |   10.2 MiB   |    2.7 MiB   |   12.9 MiB  
goa-daemon                                              |    7.2 MiB   |    5.0 MiB   |   12.2 MiB  
sftp-server                                             |   10.8 MiB   |    1.3 MiB   |   12.1 MiB  
zeitgeist-datahub                                       |    6.1 MiB   |    6.0 MiB   |   12.0 MiB  
xdg-desktop-portal-xapp                                 |    8.6 MiB   |    3.4 MiB   |   12.0 MiB  
evolution-addressbook-factory                           |    7.8 MiB   |    4.2 MiB   |   12.0 MiB  
dbeaver-ce                                              |   11.3 MiB   |  632.0 KiB   |   11.9 MiB  
systemd                                                 |    6.1 MiB   |    5.7 MiB   |   11.9 MiB  
lightdm                                                 |   10.0 MiB   |    1.6 MiB   |   11.6 MiB  
C:windowssystem32services.exe                           |    6.2 MiB   |    5.2 MiB   |   11.4 MiB  
smbd                                                    |    4.8 MiB   |    6.4 MiB   |   11.2 MiB  
scx_rusty                                               |    4.8 MiB   |    6.4 MiB   |   11.1 MiB  
colord                                                  |   10.5 MiB   |  488.0 KiB   |   11.0 MiB  
evolution-calendar-factory                              |    8.2 MiB   |    2.1 MiB   |   10.3 MiB  
cups-browsed                                            |    9.8 MiB   |  476.0 KiB   |   10.3 MiB  
--------------------------------------------------------+--------------+--------------+--------------
[SPECIAL] Unmapped Shmem / IPC / GPU                    |    5.8 GiB   |   23.1 GiB   |   28.9 GiB  
[SPECIAL] Kernel Slab (Unreclaimable)                   |   14.8 GiB   |    4.5 GiB   |   19.3 GiB  
[SPECIAL] Kernel PageTables & Stacks                    |  868.0 MiB   |  240.4 MiB   |    1.1 GiB  
--------------------------------------------------------+--------------+--------------+--------------
TOTAL ALLOCATED RAM (PROCESS + SPECIAL)                 |  172.8 GiB   |   65.0 GiB   |  237.8 GiB  
FREE RAM (UNALLOCATED)                                  |   68.6 GiB   |   22.9 GiB   |   91.5 GiB  
AVAILABLE RAM (FREE + RECLAIMABLE)                      |   70.5 GiB   |   26.3 GiB   |   96.8 GiB  


