###For some reason xiaomi a1 shields the telecom call feature, but the hardware is supported and is now retrieved.
#You must first do the following, and these operations will not affect any function and once and for all.[Here](https://github.com/wonderil/Xiaomi-A1-CDMA-gsm-support/blob/master/z.md)

##Used code

```
# This file will be read by resetprop
# Example: Change dpi
# ro.sf.lcd_density=320
persist.camera.HAL3.enabled=1
persist.camera.eis.enable=1
ro.vendor.audio.sdk.fluencetype=fluencepro
ro.telephony.default_network=22,20
```
Major changes build.prop
Has the following features
```
CDMA-gsm support  Enable Camera2 API, Add fix for EIS (Electronic Image Stabilization), Fix bad video sound, ARCore Apps by Arnova8G2, fixes long camera start on Mi A1 without disabling SELinux, Xml pack of different vendors.
```
##image
![p](https://raw.githubusercontent.com/wonderil/Xiaomi-A1-CDMA-gsm-support/master/image/Screenshot_20180501-212758.png)



###关于 
####本项目使用[xda](https://forum.xda-developers.com/mi-a1/how-to/magisk-module-xiaomi-mi-a1-fixes-v6-t3745484)提供的文件。在此基础上进行增加.目的是为了解决电信(cdma)无法在xiaomi A1 上无法打电话的问题.如果使用的工具和方法侵犯了您的利益，联系后删除。