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
