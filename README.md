# Dell-Inspiron-7579-Hackintosh
***
当前 macOS 版本 11.3 Beta 8 (20E5231a) / 当前 OC 版本 0.6.8  理论上支持 macOS 10.15 - 11.3 Beta 8

![image](https://github.com/ayive/Dell-Inspiron-7579-Hackintosh/blob/main/%E6%88%AA%E5%B1%8F/%E6%88%AA%E5%B1%8F2021-04-16%20%E4%B8%8A%E5%8D%8811.07.35.png)

## 配置清单
***
- Dell Inspiron 7579

    - Intel i5-7200U
    - 16GB RAM
    - (1920x080) 触摸屏显示器（Touchscreen display）
    - SK hynix SC308 SATA 256GB 
    - Intel Wireless-AC 3165
    - Integrated_Webcam_HD：
        - 型号ID：	UVC Camera VendorID_3034 ProductID_22722
    - 禁用设备
        - 读卡器（SD card reader）

- 固件版本

    - BIOS version 1.31.0

## 解锁CFG Lock
| 名称     | 偏移量     | 默认变量     | 需要变量 |
| ---------- | :-----------:  | :-----------: | :-----------: |
| CFG Lock    | 0x4C7     | 0x01  （开启）     |0x00  （关闭） |

