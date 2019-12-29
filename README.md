# NUC7i5BEK Hackintosh 10.14.6 EFI

---

intel NUC7i5BEK 微型电脑黑苹果安装和使用EFI，目前只在10.14.6上验证通过。

## 说明

1. 该EFI可供安装和使用，目前仅测试macOS 10.14.6
2. 支持传感器，可显示CPU温度频率等信息
3. 具体配置如下

   1. CPU Intel(R) Core(TM) i5-7260U CPU @ 2.20GHz

   2. 显卡 Intel Iris Plus Graphics 640

   3. 内存 8G*2

   4. 硬盘 Nvme Samsung SSD 970 EVO 250GB

   5. 系统 macOS Mojave 版本 10.14.6（版号 18G2022）

   6. Clover 引导版本 5101

## 使用方法

1. 制作安装镜像，推荐使用「黑果小兵」的镜像

2. 打开EFI分区，替换EFI目录

3. 进入安装，如遇跑马结束，安装完成但选择国家时重启，请自行在Clover界面屏蔽非必要驱动

## 已知问题

- 热重启时黑屏时间很久很久

- 可支持内置HDMI+Type-c转接HDMI的双显示输出，但存在以下问题：

1. 双显示器同时接入开机则内置HDMI显示器无输出，Type-c显示器概率性花屏

2. （无论单双屏）黑屏节能后，内置HDMI显示器存在概率性花屏

3. （无论单双屏）黑屏节能后，Type-C转接头需重新插拔才有输出

## 鸣谢

黑果小兵：[黑果小兵的部落阁](https://blog.daliansky.net)

 Intel NUC7系列黑苹果安装和日常使用EFI：[intel-nuc7-hackintosh](https://github.com/NathanDai/intel-nuc7-hackintosh)

群「[一起黑苹果](https://jq.qq.com/?_wv=1027&k=56GTaUh)」的管理员「奥利奥（13410548314）」
