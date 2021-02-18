# Qotom BIOS files

Backup of Qotom BIOS files. 

I've spent quite a lot of time trying to upgrade one of my Qotom devices.
Qotom used to host them on Dropbox, then on their websire (404 now), and I've finally came across https://www.qotom.shop/download/BIOS/.
So, this is a backup done with:

```
wget --no-parent -r https://www.qotom.shop/download/BIOS/
find . -name "index.html*" -exec rm {} \;
```

