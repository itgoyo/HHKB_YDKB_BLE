# HHKB_YDKB_BLE

<<<<<<< HEAD
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
https://ydkb.github.io/?hhkb_ble-0#H4sIAAAAAAAAA+2TXY4bMQyDL8QH618+yyD3v0YpJ4tNgbbbp2KALjxQJghJS5+d67rEEpIpfWqduuAIJAqNDX4VgSjEIA6JBy6hiVqaNnRBBapQgzo0oAktaEM3bMGEDlOYwRwW4JZWsIZtON10ucINzpeAJ7xo8YZvxEIIQhGGYF+BSEQhGrGRCylIRRod6Ug2nshCNnKjFkpQijKUo5guTnfxadSmqRda0Io2tKMDnWjO3uiNvbAFW7EN27Fn+p3YhU04Q4d4FvlwOlkksGogsMapeWqd2qcOsbKBOlxkwA7ZQSvBHHK1+STc4TNoGTVBEzMhjJjm40H/xa2f6xxiihOlvI4xXUlifuVURMHxDoSZ+sz4ZENTfESMPA+ij+D04Mke3IP4EzjecT+1x/Ykr7VmvAHPEajQ2Sxf5JUKeV9H+8c1zZ2rN5O9ruzv19d5b4rT468kB3D9dc7/oPjpzt28139HRG/RyV0UQ2TdopO7KL7/Nd9EviTy+AEhQroHkAkAAA==

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

### 充电过程红灯强光亮


=======
配置链接：
https://ydkb.github.io/?hhkb_ble-0#H4sIAAAAAAAAA+2TXY4bMQyDL8QH618+yyD3v0YpJ4tNgbbbp2KALjxQJghJS5+d67rEEpIpfWqduuAIJAqNDX4VgSjEIA6JBy6hiVqaNnRBBapQgzo0oAktaEM3bMGEDlOYwRwW4JZWsIZtON10ucINzpeAJ7xo8YZvxEIIQhGGYF+BSEQhGrGRCylIRRod6Ug2nshCNnKjFkpQijKUo5guTnfxadSmqRda0Io2tKMDnWjO3uiNvbAFW7EN27Fn+p3YhU04Q4d4FvlwOlkksGogsMapeWqd2qcOsbKBOlxkwA7ZQSvBHHK1+STc4TNoGTVBEzMhjJjm40H/xa2f6xxiihOlvI4xXUlifuVURMHxDoSZ+sz4ZENTfESMPA+ij+D04Mke3IP4EzjecT+1x/Ykr7VmvAHPEajQ2Sxf5JUKeV9H+8c1zZ2rN5O9ruzv19d5b4rT468kB3D9dc7/oPjpzt28139HRG/RyV0UQ2TdopO7KL7/Nd9EviTy+AEhQroHkAkAAA==

偶尔会出现连续点击的bug
有文章说左右shift+p 关闭节电模式就好了，我验证一下看看是不是有效
>>>>>>> c09309164a68fbb489bd2f524fe009ae32a23ebc
