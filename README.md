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

## Third party apps

### gnome-tweak

### alfred
Install [alfred](https://albertlauncher.github.io/)

### Dash to dock

Install [dash-to-dock](https://micheleg.github.io/dash-to-dock/)

Keep the dock visible all the time
```
gsettings set org.gnome.shell.extensions.dash-to-dock dock-fixed true
gsettings set org.gnome.shell.extensions.dash-to-dock intellihide false
```
