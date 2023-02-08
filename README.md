# Building

Install dependencies:

```
apt install build-essential debhelper
```

Build for armhf:

```
DEB_BUILD_OPTIONS=nocheck dpkg-buildpackage -us -uc -aarmhf -Pcross,nocheck
```