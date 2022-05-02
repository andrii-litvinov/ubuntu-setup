Reset default Launch terminal key binding
```bash
gsettings list-recursively | grep terminal
gsettings set org.gnome.settings-daemon.plugins.media-keys terminal '[]'
```

Shurtcus
https://askubuntu.com/questions/597395/how-to-set-custom-keyboard-shortcuts-from-terminal

Full RGB
https://askubuntu.com/a/678301

Do not suspend on lid close
https://ubuntuhandbook.org/index.php/2020/05/lid-close-behavior-ubuntu-20-04/

Remove keybindings used by Rider
```bash
gsettings list-recursively | grep "<Control><Shift><Alt>"
gsettings set org.gnome.desktop.wm.keybindings move-to-workspace-right "['<Super><Shift>Page_Down', '<Super><Shift><Alt>Right']"
gsettings set org.gnome.desktop.wm.keybindings move-to-workspace-left "['<Super><Shift>Page_Up', '<Super><Shift><Alt>Left']"
gsettings set org.gnome.desktop.wm.keybindings move-to-workspace-down "[]"
gsettings set org.gnome.desktop.wm.keybindings move-to-workspace-up "[]"
```

PCIe Bus error severity=Corrected
https://askubuntu.com/a/926352/1513408
