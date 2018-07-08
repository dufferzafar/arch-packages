
# arch packages

I will upload these on AUR once I figure out how to do that. Till then, you can install directly from this repo:

```bash
git clone http://github.com/dufferzafar/arch-packages && cd arch-packages

cd package-you-want-to-install

makepkg -cs

sudo cp *.xz /var/cache/pacman/pkg/
sudo pacman -U *.xz
```
