# rtl8188eu
RTL8188EU packages on OpenWRT

## 1.Copy to openwrt

openwrt19.07

```
cp -rf rtl8188eu_1907 ../openwrt/package/kernel
mv rtl8188eu_1907 rtl8188eu
```

openwrt23.05

```
cp -rf rtl8188eu_2305 ../openwrt/package/kernel
mv rtl8188eu_2305 rtl8188eu
```

## 2.Selected

kernel modules > wireless Drivers > kmod-rtl8188eu

![](https://note.youdao.com/yws/api/personal/file/WEBff0a7e371a398263d50032eb5b0f3025?method=download&shareKey=e3dca0dbb226d2b1cc0ebd21a0c87b23)

## 3.Test

Tested only on the IMX6ULL board.
