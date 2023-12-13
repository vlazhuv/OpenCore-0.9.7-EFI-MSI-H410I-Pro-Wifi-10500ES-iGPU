# OpenCore-0.9.7-EFI-MSI-H410I-Pro-Wifi-10500ES-iGPU
# MacOS Sonoma 14.2
# Hackintosh

<img width="476" alt="截屏2023-12-13 16 29 44" src="https://github.com/vlazhuv/OpenCore-0.9.7-EFI-MSI-H410I-Pro-Wifi-10500ES-iGPU/assets/47969038/3f9d598a-6ae3-4d59-a3c8-5626d2df3a9c">
<img width="945" alt="截屏2023-12-13 16 31 06" src="https://github.com/vlazhuv/OpenCore-0.9.7-EFI-MSI-H410I-Pro-Wifi-10500ES-iGPU/assets/47969038/7b0bcdeb-e132-4127-aa93-0be8052e810d">
<img width="927" alt="截屏2023-12-13 16 31 35" src="https://github.com/vlazhuv/OpenCore-0.9.7-EFI-MSI-H410I-Pro-Wifi-10500ES-iGPU/assets/47969038/c172d6dc-fab4-4d95-aee4-c97b4597917e">

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
