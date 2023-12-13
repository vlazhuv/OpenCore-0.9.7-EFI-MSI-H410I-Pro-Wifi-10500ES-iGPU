# OpenCore-0.9.7-EFI-MSI-H410I-Pro-Wifi-10500ES-iGPU
# MacOS Sonoma 14.2
# Hackintosh

## 配置

| Items       | Model               |
| ----------- | ------------------- |
| Motherboard | MSI H410I Pro Wifi |
| CPU         | Intel Core i5-10500ES |
| RAM         | JAZER 2x32GB DDR4 2666 MHz |
| Hard Disk   | SanDisk 1TB nvme        |
| GPU         | UHD 630             |
| Sound Card  | Realtek AL1200      |
| Ethernet    | Intel Ethernet Connection I219-V |
| WLAN & Bluetooth        | BCM 94352Z |


## 功能
- [x] 板载声卡
- [x] 板载网卡
- [x] 核显硬解
- [x] wifi/蓝牙
- [x] 睡眠 / 唤醒
- [x] USB2.0 / USB 3.0
- [x] DRM
- [x] 核显dp/hdmi输出

## 教程
https://dortania.github.io/OpenCore-Install-Guide/

## 关于WI-FI的说明
因为Sonoma取消了对BCM94352Z的免驱动支持，所以需要使用OpenCore Legacy Patcher（OCLP）进行修复，具体教程可参考：
https://zhuanlan.zhihu.com/p/646774043
需要注意的是，如果无法使用“ Start Root Patching”，可重启后重复操作。
