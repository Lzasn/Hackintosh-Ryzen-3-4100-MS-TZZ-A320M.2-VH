![OpenCore_with_text_Small](https://github.com/user-attachments/assets/49f199f8-6059-4386-bd19-5c7eabf65c29)


## Hackintosh-Ryzen-3-4100-MS-TZZ-A320M.2-VH

>  [!CAUTION]
>
>  本仓库仅用于存放OpenCore的相关文件，不承担因使用了此仓库下载EFI引导文件导致的引导失败、功能异常（缺失）、系统运行异常以及一切均与所有者无关的后果问题

> [!NOTE]
>
> 如果你的电脑硬件配置和我上传的EFI引导所使用的硬件配置很相似，那么你可以尝试能不能正常使用，否则请自行生成EFI并根据你的电脑硬件进行修改

![Static Badge](https://img.shields.io/badge/%E6%94%AF%E6%8C%81%E7%9A%84macOS%E7%89%88%E6%9C%AC-Catalina%2010.15%20~%20Sequoia%2015.1-block?logo=apple)  ![Static Badge](https://img.shields.io/badge/OpenCore%E7%89%88%E6%9C%AC-1.0.1-33163)


## 参考

[主页 - 国光的黑苹果安装教程：手把手教你配置 OpenCore (sqlsec.com)](https://apple.sqlsec.com/)

[mikigal/Ryzen-hackintosh(github.com)](https://github.com/mikigal/ryzen-hackintosh)

[JeoJay127/RapidEFI-Tool(github.com)](https://github.com/JeoJay127/RapidEFI-Tool)

[OpenCore安装指南 (sumingyd.github.io)](https://sumingyd.github.io/OpenCore-Install-Guide/)

## 硬件配置

- CPU：AMD Ryzen 3 4100（基准频率：3.80GHz，4核8线程）
- GPU：柏能/蓝宝石 AMD RX 460白金版（4GB显存）/ 七彩虹网驰 NVIDIA GTX 1060（6GB显存）
- 主板：铭瑄 MS-挑战者 A320M.2-VH
- 内存：镁光 DDR4 3200MHz 16GB
- 网卡：Realtek RTL8111（1Gbps）/ lntel AX210 WiFi6e 160MHz（2.4Gbps）
- 声卡：Realtek ALC662
- 硬盘：七彩虹 CN600 M.2 512GB（PCle3.0）


## 完美程度

> [!NOTE]
>
> ”已勾上“代表该项功能可正常使用；“未勾上”代表该项功能无法实现

> [!IMPORTANT]
>
> lntel AX210无线网卡只能用单向的隔空投送，若需要双向隔空投送功能请考虑更换博通WiFI网卡<br/>
> iPhone镜像需要T2芯片支持，黑苹果目前无解



- [x] 睡眠唤醒
- [x] CPU睿频
- [x] 以太网
- [x] 声音输出/麦克风
- [x] CPU/GPU传感器（需要添加SMCRadeonSensors.kext才能正常读取显卡温度 / 风扇转速）
- [x] 显卡（Matel/VDA）
- [x] 隔空投送
- [x] 接力
- [x] 随航
- [x] 跨设备粘贴
- [x] 通用控制
- [ ] iPhone镜像

## 截图
<img width="316" alt="43733B61A16CD7366AC13C86F65CE824" src="https://github.com/user-attachments/assets/fd352b42-65e3-4f9b-bfe2-46c4588db9ac" />



