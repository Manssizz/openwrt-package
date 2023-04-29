# Openwrt Package by Manssizz
Collaboration Openwrt package from many repository sources.

### Compatible
- Openwrt Lede
- Openwrt 19.07 (untested)

### How to use
```bash
### For lede
cd lede
sed -i '$a src-git Cendrawasih_Packages https://github.com/manssizz/openwrt-packages.git' feeds.conf.default
./scripts/feeds update -a && ./scripts/feeds install -a

### For Openwrt 19.07
sed -i '$a src-git Cendrawasih_Packages https://github.com/manssizz/openwrt-packages.git' feeds.conf.default
./scripts/feeds update -a && ./scripts/feeds install -a
```