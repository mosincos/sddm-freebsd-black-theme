### About

Simple SDDM theme inspired on the FBSD SLiM theme.

### Preview!
![SDDM FreeBSD Black Theme](https://github.com/lebarondemerde/sddm-freebsd-black-theme/blob/master/screenshot.png)

### Installation
```shell
git clone https://github.com/lebarondemerde/sddm-freebsd-black-theme.git
cp -R sddm-freebsd-black-theme /usr/local/share/sddm/themes
```

- Open up `/usr/local/etc/sddm.conf` file and set `sddm-freebsd-black-theme` as your current theme.
```shell
[Theme]
# Current theme name
Current=sddm-freebsd-black-theme
```

### Configuration
- The theme uses the Montserrat font by default, but you can change it editing the `/usr/local/share/sddm/themes/sddm-freebsd-black-theme/theme.conf` file and setting the desired font in the `displayFont` variable.

```shell
[General]
background=background.png
displayFont="Montserrat"
```
