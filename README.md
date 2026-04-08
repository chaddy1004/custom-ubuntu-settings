# custom-ubuntu-settings


disable wayland by going 
```
sudo vim /etc/gdm3/custom.conf

WaylandEnable=false
```
gotta restart gdm3


```
sudo systemctl restart gdm3
```


Install [alfred](https://albertlauncher.github.io/)

Install [dash-to-dock](https://micheleg.github.io/dash-to-dock/)