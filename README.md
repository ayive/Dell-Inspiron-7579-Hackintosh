# Dell-Inspiron-7579-Hackintosh
当前 macOS 版本 13.0.1 (22A400) / 当前 OC 版本 0.8.6<br>理论上支持 macOS 10.15 - 13.0.1

![image](https://github.com/ayive/Dell-Inspiron-7579-Hackintosh/blob/main/%E6%88%AA%E5%B1%8F/%E6%88%AA%E5%B1%8F2022-11-21%2010.37.53.png)

## 配置清单
- Dell Inspiron 7579
		
    - 处理器名称	DualCore Intel Core i5-7200U, 706 MHz (31 x 23)
    - 主板名称	Dell Inspiron 15-7579
    - 主板芯片组	Intel Sunrise Point-LP, Intel Kaby Lake-U
    - 系统内存	16250 MB  (DDR4 SDRAM)
    - 显示设备	
        - 显示适配器	Intel(R) HD Graphics 620  (1 GB)
        - 显示器	AU Optronics B156HAB (Dell 0079Y)  [15.6" LCD] (1920x080) 触摸屏显示器（Touchscreen display）
    - 多媒体	
        - 音频适配器	Realtek ALC225 @ Intel Sunrise Point-LP PCH - High Definition Audio Controller [C1]
    - 存储设备	
        - 硬盘驱动器	ZHITAI SC001 Active 512GB SSD
    - 网络设备	
        - 网络适配器	Intel(R) Dual Band Wireless-AC 3165
    - DMI	
        - DMI BIOS 厂商	Dell Inc.
        - DMI BIOS 版本	1.36.0
    - 禁用设备
        - 读卡器（SD card reader）

## 解锁CFG Lock
| 名称     | 偏移量     | 默认值     | 修改值 |
| ---------- | :-----------:  | :-----------: | :-----------: |
| CFG Lock    | 0x4C7     | 0x01<br>（开启）   |0x00<br>（关闭）   |

## Credits
- [acidanthera](https://github.com/acidanthera) for providing almost all kexts and drivers
- [alexandred](https://github.com/alexandred) for providing VoodooI2C
- [headkaze](https://github.com/headkaze) for providing the very useful [Hackintool](https://github.com/headkaze/Hackintool)
- [daliansky](https://github.com/daliansky) for providing the awesome hotpatch guide [OC-little](https://github.com/daliansky/OC-little)
- [zxystd](https://github.com/zxystd) for providing AirportItlwm and IntelBluetoothFirmware
