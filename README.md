# fnt
apt for fonts, the missing font manager for macOS/linux

# Why?

If you run [Debian](https://www.debian.org) stable, you don't get the latest fonts, unless someone backports them actively. So this is useful to just get the latest and greatest fonts from Debian sid. It gets even worse with non Debian based Linux distributions.

If you run [macOS](https://www.next.com), neither [fink](https://www.finkproject.org), [brew](https://brew.sh), nor [macports](https://www.macports.org) come with a great list of available to install fonts.

# Font repositories

Debian sid, ~480 fonts available, only those starting with `fonts-`: https://packages.debian.org/unstable/fonts/

Google fonts, ~1280 fonts available, (`google-` prefixed) see: https://github.com/google/fonts

# Installation

```
cp fnt /usr/bin
```

# Usage

```
$ fnt update

$ fnt search agave

$ fnt preview agave
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷▃▃▖╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷▟▉▉▉╷╷╷╷╷╷╷▁▁▁╷╷╷╷╷▁▁▁▁╷╷╷╷▁▁▁╷╷╷▁▁╷╷╷╷▁▂▁╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷▗▇▉▉▉▌╷╷╷▗▆▇▉▉▉▇▍╷╷▐▉▉▉▇▇▅╷▕▜▉▉╷╷▟▉▉▘╷▗▇▇▛▉▇▆╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷▟▉▛▐▉▉▏╷▕▇▉▛╷▕▉▉▌╷╷╷╷▁▁▟▉▉▏╷▐▉▉▌▗▇▉▋╷▕▇▉▛▁▕▉▉▋╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▗▇▉▙▃▉▉▋╷╷▜▉▙▃▃▉▉▌╷▗▇▇▉▉▜▉▉▏╷╷▜▉▉▟▉▉╷╷▕▉▉▛▛▛▛▛▘╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▟▉▛▀▀▜▉▉▖╷╷▀▀▀▀▉▉▌╷▐▉▉▃▂▟▉▉▏╷╷▝▉▉▉▉▘╷╷╷▜▉▇▃▂▂▂╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╺▛▛▏╷╷╷▜▛▋╷╷╷╷▁▄▉▉▍╷╷▀▜▜▛▛▛▀╷╷╷╷▐▛▛▛╷╷╷╷╷▀▜▜▜▛▉╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▕▇▉▉▉▛▀╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷▗▇▇▙╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▐▇▇▇▇▇▇▊╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▇▇▇▇▇▆▅▖╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷▟▉▉▉▖╷╷╷▕▅▅▅▅▄▂╷╷╷╷╷╷╷╷╷╷╷╷▐▉▉▎▔▔▔▔╷╷╷▃▅▆▅▄▂╷╷╷╷╷╷╷╷╷╷╷╷▟▉▉▔▔▜▉▉╷╷▃▅▅▆▅▄▂╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷▐▉▉▜▉▙╷╷╷╷▀▀▀▜▉▉▍╷╷╷╷╷╷╷╷╷╷╷▐▉▉▙▄▄▄▏╷╷▟▉▉▀▜▉▇▍╷╷╷╷╷╷╷╷╷╷╷▟▉▉▄▄▇▉▛╷▕▉▉▛▔▜▉▉▎╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷┈┈┈┈┈┈╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▕▇▉▌▝▉▉▍╷╷▂▄▅▆▆▉▉▌╷╷╷╷╷╷╷╷╷╷╷▐▉▉▛▀▀▀▏╷▕▇▉▙▅▅▉▉▋╷╷╷╷╷╷╷╷╷╷╷▟▉▉▀▉▉▋╷╷▕▉▉▌╷╷▔▔╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╵╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▟▉▉▇▇▇▉▉╷▕▇▉▛▀▀▉▉▌╷╷╷╷╷╷╷╷╷╷╷▐▉▉▎╷╷╷╷╷▕▉▉▉▔▔▔▔╷╷╷╷╷╷╷╷╷╷╷╷▟▉▉╷▐▉▉▖╷▕▉▉▌╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷┈╷╷╷╷╷╷╵╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷▕▇▉▍▔▔▔▉▉▍╷▜▉▇▆▆▉▉▍╷╷╷╷╷╷╷╷╷╷╷▐▉▉▆▆▆▆▆╷╷▝▜▉▇▆▆▆╷╷╷╷╷╷╷╷╷╷╷╷▟▉▉╷╷▜▉▙╷▕▉▉▌╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╵╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷▔▔▔╷╷╷╷▔▔▔╷╷╷▔▔▔▔▔╷╷╷╷╷╷╷╷╷╷╷╷▔▔▔▔▔▔▔▔╷╷╷╷▔▔▔▔▔╷╷╷╷╷╷╷╷╷╷╷╷▔▔▔╷╷╷▔▔╷╷▔▔▔╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷┈╷╷╷╶╷╷╷╷╶╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╵╷╷╷╷╷┈╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╶╷╷╷╷╷╷╶╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╵╷╷╷╷╷╷╷┈╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▗▄▄▄▄▃▁╷╷╷▄▄▖╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▂▃▄▅▅▄╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▕▄▄▄▄▄▄▏╷╷╷╷╷▐▉▉▉╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╶╷╷╷╷╷╷╷╷╶╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▐▉▉▀▜▉▇▌╷╷▇▉▙▃▂▁╷╷╷╷╷╷╷╷╷╷╷╷╷▗▆▇▉▀▀▀▀╷╷╷▁▂▃▃▂▁╷╷╷╷╷╷╷╷╷╷╷╷▕▀▀▀▜▉▉▏╷╷╷╷╷▔▔▔▔╷╷╷╷╷╷╷╷╷╷╷╷╵╷╷╷╷╵╵╵╵╵╷╷╷╷╷╶╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▐▉▉▂▃▇▉▋╷╷▇▉▉▛▜▉▙▁╷╷╷╷╷╷╷╷╷╷╷▟▉▛╷▁▁▁▁╷╷▟▇▉▛▜▉▉▎╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▐▉▉▏╷╷▐▇▇▇▇▇▌╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▐▉▉▉▉▉▙▃╷╷▇▉▊╷▕▉▉▋╷╷╷╷╷╷╷╷╷╷▕▇▉▌╷▜▉▉▉┈▕▇▉▌╷▕▉▉▍╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▐▉▉▏╷╷▔▔▔▕▉▉▌╷╷╷╷╷╷╷╷╷╷╷┈╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╶╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▐▉▉┈╷▐▉▉▍╷▇▉▊╷╷▇▉▋╷╷╷╷╷╷╷╷╷╷▕▇▉▊╷╷▐▉▉┈╷▜▉▇▅▅▉▉▍╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▟▉▉╷╷╷╷╷╷▕▉▉▌╷╷╷╷╷╷╷╷╷╷╵╷╷╷╷╷╷╷╷╷╷╷╷╷┈╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▐▉▉▄▄▇▉▛▏╷▇▉▙▄▟▉▛▘╷╷╷╷╷╷╷╷╷╷╷▝▉▉▅▄▟▉▉╷╷╷▔▀▀▀▉▉▍╷╷╷╷╷╷╷╷╷╷╷▄▄▄▆▇▉▀╷╷╷╷╷╷▕▉▉▌╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╵╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▝▀▀▀▀▀▔╷╷╷▝▀▀▀▀▀╷╷╷╷╷╷╷╷╷╷╷╷╷╷▔▀▀▀▀▀▔╷╷╷▂▂▃▟▉▉▎╷╷╷╷╷╷╷╷╷╷╷▀▀▀▀▀▔╷╷╷╷▂▂▃▟▉▉▎╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▕▜▛▛▛▀▘╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▕▜▛▛▛▀▘╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▁▁╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▁▁╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▐▉▉┈╷▟▉▉╷╷▆▇▉▉▉▇▆▁╷╷▐▉▉▉▇▇▅╷▕▇▇▉▇▇▉▇▇▖╷▗▆▇▉▉▇▅╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▕▉▉▉▇▇▅╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▐▉▉┈╷▟▉▉╷╷▇▉▊╷▕▉▉▌╷╷╷╷▁▁▜▉▉▏▕▉▉╷▇▉▏▜▉▍▕▇▉▛╷▕▉▉▋╷╷╷╷╷╷╷╷╷╷╷▕▆▆▆▆▆▆▏╷╷╷╷▁▁▐▉▉▎╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▐▉▉┈╷▟▉▉╷╷▇▉▊╷▕▉▉▌╷▗▆▇▉▉▉▉▉▏▕▉▉╷▇▉▏▟▉▍▕▉▉▉▇▇▉▛▘╷╷╷╷╷╷╷╷╷╷╷╷▀▀▀▀▀▀╷╷╷▆▇▉▉▉▉▉▍╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷▐▉▉▂▁▟▉▉╷╷▇▉▊╷▕▉▉▌╷▐▉▉▌▁▟▉▉▏▕▉▉╷▇▉▏▟▉▍╷▜▉▉▃▁▁▁╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▕▉▉▙▁▟▉▉▎╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷▀▜▉▉▉▛▀╷╷▜▉▋╷▕▉▉▌╷╷▀▜▉▉▉▛▀╷▕▉▉╷▜▉▏▜▉▍╷╷▀▜▉▉▉▉╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷▀▜▉▉▉▉▛▏╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷╷
▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃▃
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▛▀▔▔▔▀▉▉▉▛▘▔▔▜▉▉▛▀▔▔▔▀▉▉▍▔▔▔▔▀▉▉▉▉▉▘▔▔▉▉▌▔▔▔▔▔▐▉▉▉▛▔▔▔▉▉▔▔▔▔▔▔▔▉▛▀▔▔▔▝▜▉▉▀▔▔▔▀▜▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▏╷▗▇▖╷▝▉▍╷╷╷╷▐▉▉▎▁▂▇┈╷▐▉▇▆▆▆┈╷▐▉▉▉▘╷╷╷▉▉▍╷╷▆▆▆▇▉▉▛╷╷▗▇▉▉▆▆▆▆╷╷▗▇▎╷╺▇▖╷▕▉▏╷▗▇▖╷▕▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉╷╷▔▔┈╷▕▉▇▆▊╷╷▐▉▉▉▉▛▘╷▁▟▉▉▎▔╷╷╶▇▉▛▔╷╻╷╷▉▉▍╷╷▔▔▀▜▉▛╷╷╷▔▀▜▉▉▉▉▘╷▕▇▉▇╴╷╵╷╶▟▉▍╷▔▀▘╷▕▇▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉╷╷▗▅▍╷▕▉▉▉▊╷╷▐▉▉▉▛▔╷▃▇▉▉▉▇▇▆▏╷▝▛╷╷▝▘╷╷▀▜▇▇▇▇▏╷▕▉▏╷▐▇▖╷▕▉▉▉▘╷╷▟▉▉▏╷▗▆▖╷╷▜▉▆▅╷╷▗▇▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▖╷▔▀╷╷▟▉▉▉▊╷╷▐▉▉▎╷╷▝▀▀▜▉▀▀▀▔╷╷▐▙▅▅▅▅╷╷▅▟▛▀▀▔╷▁▟▉▍╷▝▀▘╷▗▉▉▛╷╷▟▉▉▉▖╷▕▀▘╷▗▇▉▛▔╷▗▇▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▇▅▄▅▇▉▉▉▉▉▅▅▇▉▉▅▅▅▅▅▅▟▉▅▄▄▅▅▇▉▉▉▉▉▉▅▅▉▉▅▄▄▅▇▇▉▉▉▇▅▄▅▇▉▉▉▅▅▅▇▉▉▉▉▆▅▄▄▆▇▉▉▅▅▅▇▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉
monospaces programming font [37-1 D:103112 I:364000]

$ fnt install agave

$ fnt list
agave-b-autohinted.ttf [699]
agave-r-autohinted.ttf [2443]
```

If you want to install all available fonts, you could run something like this:

`for a in $(fnt search |sed s,fonts-,,); do fnt install $a; done`

You end up with ~2700 font files, taking up 1.6 GB.

# Thanks

The preview mode works using https://github.com/hpjansson/chafa and https://screenshots.debian.net

# Screenshots

Create your own with http://shell.aiei.ch/typography/

# Missing a font?

Feel free to create an issue, if the font comes with sources and its license is DFSG compliant, I'm happy to package it for a dollar. Free if I like it.

# TODO

Get [ReactOS](https://reactos.org) with bash, and make `fnt` work there.

Maybe add support for non-free and contrib.

Maybe write a fnt.1 manual page.

Maybe add support for individual fonts from https://fontlibrary.org
