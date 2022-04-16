# Hackintosh-EFI-M720Q
## 联想 ThinkCentre M720Q，黑苹果EFI

### 软件版本
| 软件 | 版本 |
| --- | :--: |
| 系统 | macOS Big Sur 11.6.5 (20G527) |
| 引导 | OpenCore v0.79 |

### 自选硬件列表
|   硬件    |   型号  |
| -------- | :----: |
| 主机 | 联想 ThinkCenter M720Q |
| CPU | Intel Core i9 9900T |
| 内存 | 杂牌，DDR4 2666 8G*2 |
| 硬盘 | 铠侠RC10，nvme 512GB |
| 无线网卡 | 联想拆机卡（ngff，1个缺口），博通BCM94352Z |

### 完成度
+ 声卡正常驱动
+ Wi-Fi、蓝牙正常驱动。Big Sur 11.6.5 (20G527) 下可以隔空投送；Monterey下隔空投送只能接受，不能发送
+ HDMI、DP接口均能亮屏，VGA接口未测试
+ 睡眠可唤醒
+ USB定制，所有USB接口（含Type-C）正常
+ Sata硬盘装Win10，OC可引导Win10
+ 引导界面图形化，开机有“duang”声音

### 缺陷
+ CPU显示不正确
+ 初始安装，使用黑果小兵的镜像 macOS Big Sur 11.5.2 (20G95)，安装完毕未升版本，直接连接蓝牙音响，声音会有断断续续的卡顿现象，升级到11.6.5 (20G527)，蓝牙声音正常
+ 隔空投送，Monterey下只能接受，不能发送；Big Sur下搜索iPhone设备，略微有两三秒延迟，才能找到

### 备注
1. PlatformInform 模拟机型，选择 Macmini8,1
2. 隔空投送问题未解决，建议不要升级Monterey

### 效果图
![关于本机.png](https://github.com/demon3434/Hackintosh-EFI-M720Q/blob/main/OpenCore%20v0.79%20%26%20macOS%20Big%20Sur%2011.6.5%20(20G527)/1.%E5%85%B3%E4%BA%8E%E6%9C%AC%E6%9C%BA.png)
![蓝牙.png](https://github.com/demon3434/Hackintosh-EFI-M720Q/blob/main/OpenCore%20v0.79%20%26%20macOS%20Big%20Sur%2011.6.5%20(20G527)/2.%E8%93%9D%E7%89%99.png)
![Hackintool系统信息.png](https://github.com/demon3434/Hackintosh-EFI-M720Q/blob/main/OpenCore%20v0.79%20%26%20macOS%20Big%20Sur%2011.6.5%20(20G527)/3.Hackintool%E7%B3%BB%E7%BB%9F%E4%BF%A1%E6%81%AF.png)
