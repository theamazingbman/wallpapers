# Terry's Favorite Wallpapers

This is a collection of my favorite wallpapers. This install command below if for `fedora`.
## Install - Create directory and download wallpapers

```bash
sudo dnf install curl unzip -y
mkdir -p ~/Pictures/wallpapers && \
curl -fL https://github.com/theamazingbman/wallpapers/archive/refs/heads/main.zip -o /tmp/wallpapers.zip && \
unzip -o -j /tmp/wallpapers.zip -d ~/Pictures/wallpapers && \
rm -f /tmp/wallpapers.zip
```

The command install the unzip tool if you don't already have it downloaded. Then it creates the directory, downloads the wallpapers and unzips them. It will skip any wallpapers if you already have them installed.
