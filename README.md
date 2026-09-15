# install

put it in your favourite bin dir
chmod +x
run with root to get complete overview

# EXAMPLE

```
2026-09-15 21:07:08 root@S7:/home/allan$ /abin/memtop
================================================================================================================
                                           NUMA SYSTEM-WIDE OVERVIEW                                            
================================================================================================================
Node         | Size         | Free         | PageCache    | Slab (Kernel) | Shmem (tmpfs)
----------------------------------------------------------------------------------------------------------------
node0        |  283.3 GiB   |   69.6 GiB   |   26.8 GiB   |   16.2 GiB   |   26.1 GiB  
node1        |  141.7 GiB   |   29.2 GiB   |   23.2 GiB   |    6.0 GiB   |   22.5 GiB  
----------------------------------------------------------------------------------------------------------------
TOTAL        |  425.0 GiB   |   98.8 GiB   |   50.0 GiB   |   22.2 GiB   |   48.5 GiB  

================================================================================================================
                                     PROCESS & TMPFS ALLOCATION PER NUMA NODE                                   
================================================================================================================
Program / Mount                            | Node 0       | Node 1       | Total RAM   
-------------------------------------------+--------------+--------------+--------------
idea                                       |   13.6 GiB   |   15.3 GiB   |   28.9 GiB  
FS:/home/allan/.cache/JetBrains            |   16.0 GiB   |        -     |   16.0 GiB  
qemu-system-x86                            |    3.2 GiB   |    3.5 GiB   |    6.6 GiB  
opencode.exe                               |    2.8 GiB   |    2.4 GiB   |    5.2 GiB  
firefox-esr                                |    5.0 GiB   |    6.9 MiB   |    5.0 GiB  
FS:/run/user/1000                          |    2.7 GiB   |        -     |    2.7 GiB  
firefox-bin                                |    2.6 GiB   |    7.1 MiB   |    2.7 GiB  
opencode                                   |    1.0 GiB   |    1.5 GiB   |    2.5 GiB  
java                                       |  944.5 MiB   |    1.0 GiB   |    1.9 GiB  
dart:frontend_s                            |    1.5 GiB   |  387.7 MiB   |    1.9 GiB  
FS:/tmp                                    |    1.5 GiB   |        -     |    1.5 GiB  
WebExtensions                              |    1.2 GiB   |  844.0 KiB   |    1.2 GiB  
bash                                       |  647.5 MiB   |  480.2 MiB   |    1.1 GiB  
dart:dartdev_ao                            |  487.1 MiB   |  471.0 MiB   |  958.1 MiB  
dart:flutter_to                            |  481.2 MiB   |  191.6 MiB   |  672.9 MiB  
Xorg                                       |  347.6 MiB   |  228.1 MiB   |  575.7 MiB  
mariadbd                                   |  247.8 MiB   |  299.9 MiB   |  547.8 MiB  
MainThread                                 |  399.2 MiB   |  110.3 MiB   |  509.4 MiB  
language_server                            |  290.9 MiB   |  195.3 MiB   |  486.2 MiB  
command-applet                             |  183.1 MiB   |  294.0 MiB   |  477.1 MiB  
harper-ls                                  |  454.5 MiB   |  120.0 KiB   |  454.7 MiB  
php-fpm                                    |  230.7 MiB   |  122.6 MiB   |  353.3 MiB  
mysqld                                     |  330.9 MiB   |    9.7 MiB   |  340.6 MiB  
mate-terminal                              |  171.6 MiB   |  134.2 MiB   |  305.7 MiB  
semgrep-core                               |   19.2 MiB   |  260.9 MiB   |  280.1 MiB  
agy                                        |  163.1 MiB   |   68.9 MiB   |  232.0 MiB  
mate-settings-d                            |  188.8 MiB   |    1.7 MiB   |  190.6 MiB  
gedit                                      |   97.1 MiB   |   86.5 MiB   |  183.6 MiB  
docker-proxy                               |  102.7 MiB   |   42.5 MiB   |  145.2 MiB  
sudo                                       |  111.1 MiB   |   20.1 MiB   |  131.2 MiB  
xdg-desktop-por                            |  101.0 MiB   |   29.2 MiB   |  130.2 MiB  
apache2                                    |   64.0 MiB   |   51.7 MiB   |  115.7 MiB  
atop                                       |  103.1 MiB   |  484.0 KiB   |  103.6 MiB  
containerd-shim                            |   86.8 MiB   |   16.3 MiB   |  103.1 MiB  
caja                                       |   60.0 MiB   |   42.2 MiB   |  102.2 MiB  
dart:dds_aot.da                            |   41.1 MiB   |   56.6 MiB   |   97.7 MiB  
supervisord                                |   72.3 MiB   |   21.4 MiB   |   93.6 MiB  
mirage                                     |   53.6 MiB   |   39.4 MiB   |   93.0 MiB  
audacious                                  |   52.9 MiB   |   35.4 MiB   |   88.4 MiB  
embeddings-serv                            |   87.0 MiB   |  580.0 KiB   |   87.6 MiB  
named                                      |    9.0 MiB   |   78.5 MiB   |   87.5 MiB  
autokey-gtk                                |   41.9 MiB   |   42.6 MiB   |   84.4 MiB  
landscape-monit                            |    8.8 MiB   |   73.0 MiB   |   81.8 MiB  
dockerd                                    |   56.0 MiB   |   24.8 MiB   |   80.7 MiB  
dart:bloc_linux                            |   52.6 MiB   |   24.7 MiB   |   77.3 MiB  
ssh                                        |   52.0 MiB   |   21.1 MiB   |   73.1 MiB  
mount.fuse.sshf                            |   34.2 MiB   |   34.2 MiB   |   68.4 MiB  
dart:main.dart-                            |   52.5 MiB   |   15.1 MiB   |   67.5 MiB  
sshd                                       |   45.7 MiB   |   18.4 MiB   |   64.1 MiB  
landscape-broke                            |   23.5 MiB   |   37.7 MiB   |   61.2 MiB  
parcellite                                 |   34.5 MiB   |   25.4 MiB   |   59.9 MiB  
FS:/run/snapd/ns                           |   59.5 MiB   |        -     |   59.5 MiB  
FS:/run                                    |   59.5 MiB   |        -     |   59.5 MiB  
htop                                       |   37.8 MiB   |   21.6 MiB   |   59.3 MiB  
su                                         |   49.5 MiB   |    8.9 MiB   |   58.4 MiB  
traefik                                    |   47.3 MiB   |    9.3 MiB   |   56.6 MiB  
solaar                                     |   47.2 MiB   |    8.3 MiB   |   55.6 MiB  
glances                                    |   47.8 MiB   |    7.3 MiB   |   55.1 MiB  
php-fpm8.1                                 |   12.2 MiB   |   39.5 MiB   |   51.7 MiB  
marco                                      |   17.6 MiB   |   29.7 MiB   |   47.4 MiB  
fuse-overlayfs                             |   33.0 MiB   |   12.0 MiB   |   45.0 MiB  
php-fpm8.3                                 |   10.4 MiB   |   32.7 MiB   |   43.0 MiB  
systemd-journal                            |   22.4 MiB   |   20.0 MiB   |   42.5 MiB  
landscape-manag                            |    7.0 MiB   |   35.1 MiB   |   42.1 MiB  
landscape-clien                            |    6.4 MiB   |   34.5 MiB   |   40.8 MiB  
php-fpm8.2                                 |   37.9 MiB   |    1.5 MiB   |   39.4 MiB  
quicktile                                  |   32.5 MiB   |    5.5 MiB   |   38.0 MiB  
wnck-applet                                |   13.2 MiB   |   23.7 MiB   |   36.9 MiB  
containerd                                 |   29.3 MiB   |    7.1 MiB   |   36.5 MiB  
pipewire-pulse                             |   23.3 MiB   |   13.2 MiB   |   36.5 MiB  
winedevice.exe                             |   22.4 MiB   |   11.6 MiB   |   34.0 MiB  
notify-osd                                 |   20.7 MiB   |   13.1 MiB   |   33.8 MiB  
snyk-linux                                 |   28.6 MiB   |    4.0 MiB   |   32.5 MiB  
notification-ar                            |   17.3 MiB   |   15.2 MiB   |   32.5 MiB  
snapd                                      |   23.4 MiB   |    7.9 MiB   |   31.3 MiB  
node-MainThread                            |   16.4 MiB   |   14.0 MiB   |   30.4 MiB  
blueman-applet                             |   29.1 MiB   |    1.0 MiB   |   30.1 MiB  
pipewire                                   |   15.3 MiB   |   14.8 MiB   |   30.1 MiB  
jetbrainsd                                 |   14.7 MiB   |   15.3 MiB   |   29.9 MiB  
systemd                                    |   14.2 MiB   |   14.9 MiB   |   29.1 MiB  
multipathd                                 |   26.3 MiB   |  908.0 KiB   |   27.2 MiB  
dbus-daemon                                |   21.7 MiB   |    4.7 MiB   |   26.4 MiB  
vpnagentd                                  |   11.3 MiB   |   14.5 MiB   |   25.8 MiB  
sh                                         |   24.3 MiB   |    1.3 MiB   |   25.6 MiB  
mate-panel                                 |   12.9 MiB   |   12.4 MiB   |   25.3 MiB  
fwupd                                      |   15.3 MiB   |    9.8 MiB   |   25.1 MiB  
clock-applet                               |   15.0 MiB   |    9.9 MiB   |   24.9 MiB  
blueman-tray                               |    5.7 MiB   |   19.0 MiB   |   24.7 MiB  
evolution-alarm                            |    9.6 MiB   |   15.1 MiB   |   24.7 MiB  
smart-notifier                             |    5.5 MiB   |   18.1 MiB   |   23.5 MiB  
FS:/home/allan/.cache/mozilla              |   23.2 MiB   |        -     |   23.2 MiB  
urfkilld                                   |    7.9 MiB   |   15.0 MiB   |   22.9 MiB  
mate-cpufreq-ap                            |   17.8 MiB   |    4.2 MiB   |   22.0 MiB  
nm-applet                                  |   18.4 MiB   |    2.6 MiB   |   21.0 MiB  
ibus-extension-                            |    8.3 MiB   |   12.2 MiB   |   20.5 MiB  
upowerd                                    |   19.5 MiB   |  460.0 KiB   |   20.0 MiB  
lvmdbusd                                   |   18.9 MiB   |  628.0 KiB   |   19.5 MiB  
polkit-mate-aut                            |    8.8 MiB   |   10.3 MiB   |   19.1 MiB  
agetty                                     |   17.8 MiB   |    1.2 MiB   |   18.9 MiB  
wineserver64                               |   17.0 MiB   |    1.3 MiB   |   18.3 MiB  
ibus-ui-gtk3                               |   10.8 MiB   |    7.4 MiB   |   18.1 MiB  
wireplumber                                |   15.3 MiB   |    2.5 MiB   |   17.8 MiB  
docker-registry                            |   11.8 MiB   |    5.8 MiB   |   17.7 MiB  
polkitd                                    |   10.4 MiB   |    7.1 MiB   |   17.4 MiB  
gnome-keyring-d                            |    6.9 MiB   |    9.6 MiB   |   16.5 MiB  
evolution-sourc                            |   15.2 MiB   |    1.1 MiB   |   16.4 MiB  
networkd-dispat                            |    5.1 MiB   |   11.0 MiB   |   16.2 MiB  
previews_daemon                            |   14.2 MiB   |    1.5 MiB   |   15.6 MiB  
iscsid                                     |   10.3 MiB   |    5.2 MiB   |   15.5 MiB  
x-session-manag                            |   14.7 MiB   |  780.0 KiB   |   15.5 MiB  
canonical-livep                            |   12.9 MiB   |    2.6 MiB   |   15.4 MiB  
gvfsd-metadata                             |    3.0 MiB   |   12.2 MiB   |   15.2 MiB  
udisksd                                    |   12.8 MiB   |    2.2 MiB   |   15.1 MiB  
unattended-upgr                            |    4.1 MiB   |   10.3 MiB   |   14.4 MiB  
NetworkManager                             |    8.5 MiB   |    5.9 MiB   |   14.4 MiB  
fsnotifier                                 |   13.6 MiB   |  632.0 KiB   |   14.2 MiB  
forkserver                                 |   13.9 MiB   |  208.0 KiB   |   14.1 MiB  
xdg-permission-                            |   12.5 MiB   |    1.5 MiB   |   14.0 MiB  
systemd-resolve                            |   12.8 MiB   |  956.0 KiB   |   13.7 MiB  
plugplay.exe                               |   11.1 MiB   |    2.6 MiB   |   13.6 MiB  
docker                                     |   11.6 MiB   |    2.0 MiB   |   13.6 MiB  
adb                                        |    9.7 MiB   |    3.8 MiB   |   13.5 MiB  
ayatana-indicat                            |   11.0 MiB   |    2.3 MiB   |   13.3 MiB  
light-locker                               |    5.6 MiB   |    7.6 MiB   |   13.1 MiB  
xdg-document-po                            |   10.2 MiB   |    2.8 MiB   |   13.1 MiB  
ibus-x11                                   |    9.1 MiB   |    3.9 MiB   |   13.0 MiB  
goa-daemon                                 |    7.6 MiB   |    5.0 MiB   |   12.6 MiB  
sftp-server                                |   10.8 MiB   |    1.3 MiB   |   12.1 MiB  
zeitgeist-datah                            |    6.1 MiB   |    6.0 MiB   |   12.1 MiB  
evolution-addre                            |    7.8 MiB   |    4.2 MiB   |   12.0 MiB  
dbeaver-ce                                 |   11.3 MiB   |  632.0 KiB   |   11.9 MiB  
sleep                                      |   10.9 MiB   |  884.0 KiB   |   11.8 MiB  
lightdm                                    |   10.0 MiB   |    1.6 MiB   |   11.6 MiB  
services.exe                               |    6.2 MiB   |    5.2 MiB   |   11.4 MiB  
smbd                                       |    4.8 MiB   |    6.4 MiB   |   11.2 MiB  
scx_rusty                                  |    4.8 MiB   |    6.4 MiB   |   11.1 MiB  
colord                                     |   10.5 MiB   |  488.0 KiB   |   11.0 MiB  
cups-browsed                               |   10.2 MiB   |  476.0 KiB   |   10.6 MiB  
evolution-calen                            |    8.2 MiB   |    2.1 MiB   |   10.3 MiB  
-------------------------------------------+--------------+--------------+--------------
TOTAL PROCESS & TMPFS RAM                  |   59.9 GiB   |   28.5 GiB   |   88.4 GiB  
