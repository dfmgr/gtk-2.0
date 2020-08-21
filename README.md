## gtk-2.0  
  
GTK, or the GIMP Toolkit, is a multi-platform toolkit for creating graphical user interfaces  
  
requires:    
```
apt install gtk-2.0
```  
```
yum install gtk-2.0
```  
```
pacman -S gtk-2.0
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/gtk-2.0/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/gtk-2.0" "$HOME/.config/gtk-2.0.bak"
git clone https://github.com/dfmgr/gtk-2.0 "$HOME/.config/gtk-2.0"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/GTK" target="_blank">gtk-2.0 wiki</a>  |  
  <a href="https://www.gtk.org" target="_blank">gtk-2.0 site</a>
</p>  
