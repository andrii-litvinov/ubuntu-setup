Reset default Launch terminal ket binding
```bash
gsettings list-recursively | grep terminal
gsettings set org.gnome.settings-daemon.plugins.media-keys terminal '[]'
```

https://askubuntu.com/questions/597395/how-to-set-custom-keyboard-shortcuts-from-terminal
