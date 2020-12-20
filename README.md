# HHKB_YDKB_BLE

YDKB键位修改地址：https://ydkb.github.io
YDKB资料：https://help.ydkb.io/

### 刷机过程
按住最左上角按键不放 (物理位置，一般设置 Esc)，插入数据线，电脑会识别出一个 U 盘名为"HHKB_BLE"，这时可放开 Esc 了。

Win: 将下载的 "HHKB_BLE.BIN" 复制或拖入 U 盘，直接覆盖原文件（重点，不要先复制进去再改名）。然后右键弹出 U 盘或再按一次 Esc 退出，刷机完成。

Mac: 需要先完全删除 "HHKB_BLE.BIN"，再复制文件，具体请严格参照帮助说明里的部分:[点此查看](http://help.ydkb.io/doku.php?id=bootloader:msd-bootloader)

不需要安装任何的驱动和刷机软件。也可以直接上传 U 盘里的 "HHKB_BLE.BIN" 到网站上，读取键盘的当前设置。

如果刷新未成功造成键盘 USB 无法识别，只需要先关掉电池开关，然后重新进入刷机模式正确刷入固件。

进阶方法：同时按左右 shift+b，此时键盘会重启，立即按住 Esc 不放，这样也可以进入刷机的 U 盘模式，好处就是整个操作过程不用插拔数据线。

### 补充说明
Num Lock, Caps Lock, Scroll Lock 这些指示灯，在蓝牙模式下并未同步显示电脑的这三者状态。只是按一下按键就切换显示一次对应指示灯。
如果不同步了，可以使用 Shift + 对应按键，比如 Shift+Capslock，这时 CapsLock 会生效但是对应指示灯的状态不会变。

![](https://i.imgur.com/HXnV4qz.png)
![](https://i.imgur.com/3HMW3sG.png)

个人使用配置链接：
https://ydkb.github.io/?hhkb_ble-0#H4sIAAAAAAAAA+2TXY7bMAyELzQP4j91FiP3v0aHShabAm23T4WBLmQwMTAzIj/J13WJJSRT+tQ6dcERSBQaG3wVgSjEIA6JBy6hiVqaNnRBBapQgzo0oAktaEM3bMGEDlOYwRwW4JZWsIZtON10ucINzj8BT3jR4g3fiIUQhCIMwb4CkYhCNGIjF1KQijQ60pFsPJGFbORGLZSgFGUoRzFdnO7i06hNUy+0oBVtaEcHOtGcvdEbe2ELtmIbtmPP9DuxC5twhg7xLPLhdLJIYNVAYI1T89Q6tU8dYmUDdbjIgB2yg1aCOeRq80u4w2fQMmqCJmZCGDHNx4P+i1s/1znEFCfK1DJ5HWW6ksYoOBlxcMQDYiY/cz750BgfMSPPg+kjPD14ugf5YP6EjnfkT+2xPelrrRlx4HMMKnQ2yxd9pULe19H+cU1z5/rNZK9r+/v1dd6b4vT4K8mBXH+d8z8ofrp3N+/13xHRW3RyF8UQWbfo5C6K76/mm8iXRB4/AFqilYCUCQAA

### Layout1层
Esc->Ctrl
Control->Esc
右下角的两个按钮修改成上下翻页

### Layout2层
主要是方向键改成了组合键的方式也就是现在的Ctrl（原先Esc）+HJKL

### 打开蓝牙功能
左右Shift+W

### 关闭蓝牙功能
左右Shift+Ctrl+W

### 输出当前键盘电量
左右Shift + V （在编辑模式下面，会输出类似91-1这样子的字样）
或者是Fn+E 输出类似90这样子的字样

### 充电过程红灯强光亮

### Bug连击的情况
http://help.ydkb.io/doku.php?id=ble-series:ble-firmware

固件最好升级到最新版本0.8.1可以减少出现连续输出的情况

### Lock Mode (锁定模式) 
Fn+Z 即可进入Lock Mode

部分键盘开始加入此功能 (BLE 系列的都已加入)，在灯光和增加功能里，可以找到如下按钮并设置。

没插 USB 线的时候它才有效。按下后立即关闭蓝牙并且键盘节能，只有同时按下 F 和 J 或者重插 USB 才能唤醒。适合不关开关直接放包里。

注 1：这里指的 F 和 J 是指默认设置里的 F 和 J 的位置，每个键盘都是固定的，目前不能变更。

补充说明：HHKB BLE，BLE660C，BLE980C 这三个静电容的双模改装主控，从 Lock Mode 唤醒键盘，需要长按 F 和 J，3 到 6 秒。

