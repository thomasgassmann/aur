# Personal AUR packages

AUR packages maintained by me.

## Build

To build them locally, go to the respective directory and run `makepkg`.

## Install

After building the package, install it using `pacman -U <package>.pkg.tar.zst`.

## Publish

First, regenerate source info:

```bash
makepkg --printsrcinfo > .SRCINFO
```

Then push as [explained here](https://wiki.archlinux.org/title/AUR_submission_guidelines#Publishing_new_package_content).
