# Xiaomi A1 CDMA-gsm support [English](https://github.com/wonderil/Xiaomi-A1-CDMA-gsm-support/blob/master/en.md)
###由于一些原因xiaomi a1屏蔽了电信打电话的功能，但是硬件是支持的，现在找回。
#你必须先进行如下操作，且这些操作不会影响任何功能，且一劳永逸。[这里](https://github.com/wonderil/Xiaomi-A1-CDMA-gsm-support/blob/master/z.md)

##使用的代码

```
# This file will be read by resetprop
# Example: Change dpi
# ro.sf.lcd_density=320
persist.camera.HAL3.enabled=1
persist.camera.eis.enable=1
ro.vendor.audio.sdk.fluencetype=fluencepro
ro.telephony.default_network=22,20
```
主要用于修改build.prop
有以下功能
```
CDMA-gsm support  Enable Camera2 API, Add fix for EIS (Electronic Image Stabilization), Fix bad video sound, ARCore Apps by Arnova8G2, fixes long camera start on Mi A1 without disabling SELinux, Xml pack of different vendors.
```
##图片
![p](https://raw.githubusercontent.com/wonderil/Xiaomi-A1-CDMA-gsm-support/master/image/Screenshot_20180501-212758.png)



###关于 
####本项目使用[xda](https://forum.xda-developers.com/mi-a1/how-to/magisk-module-xiaomi-mi-a1-fixes-v6-t3745484)提供的文件。在此基础上进行增加.目的是为了解决电信(cdma)无法在xiaomi A1 上无法打电话的问题.如果使用的工具和方法侵犯了您的利益，联系后删除。

