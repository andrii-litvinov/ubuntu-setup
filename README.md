Reset default Launch terminal ket binding
```bash
gsettings list-recursively | grep terminal
gsettings set org.gnome.settings-daemon.plugins.media-keys terminal '[]'
```
