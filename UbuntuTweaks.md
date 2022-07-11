#### Set default sort order in nautilus
```
gsettings set org.gnome.nautilus.preferences default-folder-viewer 'list-view'
gsettings set org.gnome.nautilus.preferences default-sort-in-reverse-order true
gsettings set org.gnome.nautilus.preferences default-sort-order mtime
gsettings set org.gnome.nautilus.preferences show-hidden-files true
gsettings set org.gnome.nautilus.preferences search-filter-time-type 'last_modified'
gsettings set org.gnome.nautilus.preferences search-view 'list-view'
gsettings set org.gnome.nautilus.preferences show-create-link true
gsettings set org.gnome.nautilus.preferences show-delete-permanently true
gsettings set org.gnome.nautilus.list-view default-zoom-level 'small'
gsettings set org.gnome.nautilus.list-view use-tree-view true
gsettings set org.gnome.nautilus.window-state maximized true
gsettings set org.gnome.shell remember-mount-password true
gsettings set org.gnome.desktop.interface color-scheme 'prefer-dark'
gsettings set org.gnome.desktop.interface clock-format '12h'
gsettings set org.gnome.desktop.interface clock-show-date true
gsettings set org.gnome.desktop.interface clock-show-seconds true
gsettings set org.gnome.desktop.interface clock-show-weekday true
gsettings set org.gnome.desktop.interface show-battery-percentage true
gsettings set org.gnome.desktop.sound allow-volume-above-100-percent true

```

#### Install [dconf-editor](https://wiki.gnome.org/Apps/DconfEditor)
```
sudo apt install dconf-editor
```
