# firejail

Install firejail
```bash
sudo apt install firejail
```

File location:
```bash
ls /usr/share/applications/masterpdfeditor5.desktop
```

Run app without Internet:
```bash
firejail --noprofile --allusers --net=none /opt/master-pdf-editor-5/masterpdfeditor5
```
