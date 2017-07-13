### About

A simple SDDM theme intended to be a replacement to FBSD SLiM theme.

### Preview!
![FreeBSD Black Theme](https://github.com/lebarondemerde/freebsd-black-theme/blob/master/screenshot.png)

### Installation
```shell
git clone https://github.com/lebarondemerde/freebsd-black-theme.git
cp -R freebsd-black-theme /usr/local/share/sddm/themes
```

- Open up `/usr/local/etc/sddm.conf` file and set `freebsd-black-theme` as your current theme.
```shell
[Theme]
# Current theme name
Current=freebsd-black-theme
```

### Configuration
- The theme uses the Montserrat font by default, but you can change it editing the `/usr/local/share/sddm/themes/freebsd-black-theme/theme.conf` file and setting the desired font in the `displayFont` variable.

```shell
[General]
background=background.png
displayFont="Montserrat"
```
