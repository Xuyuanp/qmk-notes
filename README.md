# qmk-notes

## **WARNING**

**绝对不要在插着电源时热插拔耳机线！！！！！可能会烧坏控制器***

## 编译固件

### 方法一：在线编译
https://config.qmk.fm/#/crkbd/rev1/LAYOUT_split_3x6_3

![image](https://github.com/Xuyuanp/qmk-notes/assets/2245664/48775466-9c25-4a47-b93a-83e3c4ee9fdb)

修改keymap之后compile，然后点firmware下载固件

### 方法二： 本地编译

https://docs.qmk.fm/#/newbs_getting_started

## 刷固件

刷固件需要在插上usb之后按一下reset键（和zmk不一样）

### qmk toolbox

mac和win有gui工具，https://github.com/qmk/qmk_toolbox

### cli

```bash
qmk flash <firmware>
```

## Vial

vial是基于qmk的固件，可以热更新keymap，不用重新刷固件

https://get.vial.today/manual/first-use.html

