To pack openwrt ubi image for compatibility with u-boot and factory sysupgrade:
```
git clone https://github.com/gl-inet-builder/openwrt-imagebuilder-ipq-ipq60xx-QSDK_Premium_3.5.git ib
cd ib
mkdir -p bin/ipq/
cp ~/openwrt-ipq60xx-generic-glinet_gl-ax1800-squashfs-nand-factory.bin bin/ipq/openwrt.ubi
make si V=s
```
Firmware is single_img_dir/ax1800-nand-apps.img
