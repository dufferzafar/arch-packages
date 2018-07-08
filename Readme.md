
# arch packages

PKGBUILDs for tools I couldn't find on AUR.

I still need to figure out how to upload these on AUR.

**Installing a package from this repo.**

```bash
git clone http://github.com/dufferzafar/arch-packages && cd arch-packages

cd package-you-want-to-install

makepkg -cs

sudo cp *.xz /var/cache/pacman/pkg/
sudo pacman -U *.xz
```

## mmake-bin

> ['modern make'](https://github.com/tj/mmake/) by tjhollowaychuck

PKGBUILD copied from: https://aur.archlinux.org/cgit/aur.git/tree/PKGBUILD?h=mmake-bin

and updated for 1.3.0 version, which was released about an year ago.

