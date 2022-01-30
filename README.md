# Shot

> A dead-simple shellscript around scrot and mpv for taking screenshots

# Requirements

- MPV -- https://mpv.io/
- Scrot -- https://github.com/resurrecting-open-source-projects/scrot/
- GNU coreutils (or a `sleep` utility) -- https://www.gnu.org/software/coreutils/

# Installation

## Manual

```bash
sudo install -Dm755 shot /usr/local/bin
```

## Packages

- Linux
  - Gentoo linux: [media-gfx/shot::dinolay](https://ari-web.xyz/gentooatom/media-gfx/shot)

# Customisation

Set the `S` environment variable to customise the sleep time before screenshot-ing passed
to [sleep(1)](https://www.man7.org/linux/man-pages/man1/sleep.1.html) for example:

```bash
S='1m' shot
```
