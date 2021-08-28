## bliot 开发板配置文件

文件列表：

- .config
- BL_SMGW.dts
- mt76x8.mk

使用方法：

- 将设备树配置文件 `BL_SMGW.dts` 放到 target/linux/ramips/dts 目录下
- 使用 `mt76x8.mk` 替换 `target/linux/ramips/image/mt76x8.mk`

需要在配置源码之前完成，后续在配置源码（`make menuconfig`）的时候需要选择该配置。

