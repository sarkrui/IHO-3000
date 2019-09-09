### 长虹 IHO-3000 实现安装第三方应用和移除网络运营商限制
#### 固件下载
请转至 [release](https://github.com/sarkrui/IHO-3000/releases) 页

#### 安装说明
解压压缩包，将 `bootargs.bin` `fastboot.bin` `recovery.img` `update.zip` 皆放置于 U 盘，根目录，将长虹盒子关机，插入 U 盘，使用绣花针短接 CPU `1` `2` 针脚，开机，待出现安卓机器人页面方可将针移走。

![](https://i.imgur.com/ImppS8z.jpg)
#### 注意事项
* 整个 U 盘只能有一个分区，不能包含 EFI 分区
* 短接时，请将绣花针放置于两引脚间隙处，尽量保持稳固
