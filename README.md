# firejail

Install firejail
```bash
sudo apt install firejail
```

Run app without Internet:
```bash
firejail --noprofile --allusers --net=none /opt/master-pdf-editor-5/masterpdfeditor5
```
