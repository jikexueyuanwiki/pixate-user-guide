# 连接到你的设备

[OS X]()

[Windows]()

为了看到你正在创建的东西，你需要连接你的设备到 Studio。Android 和 iOS 设备的连接有一些不同，但都需要 Pixate 移动应用。在继续下面的步骤之前，下载并安装
[Android](https://play.google.com/store/apps/details?id=com.pixate.pixate&hl=en) 或 [iOS](https://itunes.apple.com/us/app/pixate/id883304734?mt=8) 客户端。

*请注意，下面的步骤需要连接到网络。这并不代表你要连接到互联网，只要正常的连到网络就可以。当所有方法都有效时，那么这些方法是有序的，考虑到安装的容易程度和连接强度。开始第一种方法。如果不可以工作，那就尝试第二种方法等。*


## 连接到 OS X  

### BONJOUR  

**iOS** - WiFi 和蓝牙必须开启

**Android** - WiFi 和蓝牙必须开启，设备和计算机必须连接到同一网络中，没有 IP/AP 隔离。

1.启动 Pixate Studio 然后创建一个新的原型或者打开一个现有的文件。Pixate Studio 需要在你的移动设备建立连接之前打开。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices1.png)

2.在你的设备上打开 Pixate 移动应用，默认选择 **Studio** 并且一个计算机名称的列表会被显示出来。这些系统都是 Pixate Studio 打开的。轻触你的系统的名字。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices2.png)

3.在 Studio 里，点击右上角的 **Connect** 菜单。这将会显示正在尝试连接你的系统的设备的列表。找到你的设备然后点击绿色打钩。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices3.png)

当设备连接上时，你会看到手机图标变绿了。不连接设备时，点击垃圾桶图标。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices4.png)

[回到顶部]()


### IP ADDRESS/PORT

**iOS** - WiFi 和蓝牙必须开启，设备和计算机必须连接到同一网络中。

**Android** - WiFi 和蓝牙必须开启，设备和计算机必须连接到同一网络中，没有 IP/AP 隔离。

1.启动 Pixate Studio 然后创建一个新的原型或者打开一个现有的文件。Pixate Studio 需要在你的移动设备建立连接之前打开。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices5.png)

2.在原型中，点击屏幕上方的 **Connect** 菜单。获取你的计算机的 IP 地址和端口号，点击信息图标，在你的计算机名字旁边。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices6.png)

3.打开 Pixate 应用然后点击 **Manual Enter IP Address**。这会提示你从 Connect 菜单进入你的计算机信息页面。或者，你可以点击你的 IP 地址界面底部的 **Scan QR code**，扫描 Connect 菜单中的二维码。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices7.png)

4.你的设备现在应该显示在 Connect 菜单里面。找到你的设备然后点击选择目录连接。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices8.png)

当设备连接上时，你会看到手机图标变绿了。不连接设备时，点击垃圾桶图标。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices9.png)

[回到顶部]()

### USB TETHERING-ANDROID ONLY

*请注意，这个方法需要第三方的 USB 驱动程序的安装。你需要启用你设备上的网络共享，在进行下一步骤之前。这个能在 **Settings > Wireless and Networks > More > Tethering and Hotspots** 找到。*

1.安装 [this USB driver](http://www.makeuseof.com/tag/configure-android-usb-tethering-mac-os-x/) 允许 Android 网络共享。按照所有指示安装。

2.通过 USB 连接你的设备，在 System Preferences > Network 选择你的设备获取本地的 IP 地址。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices10.png)

3.在你的 Android 设备上，点击 **Manual Enter IP Address** 然后输入你移动设备的 **IP 地址** 和从 **Connect** 菜单获取的你的计算机端口号。当你已经点击 **Connect**。

如果所有的网络连接都被禁用（WiFi 等）设备的 IP 地址将会变成一个显示在 **Connect** 菜单下面。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices11.png)

4.你的设备现在应该显示在 Connect 菜单里面。找到你的设备然后点击选择目录连接。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices12.png)

当设备连接上时，你会看到手机图标变绿了。不连接设备时，点击垃圾桶图标。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices13.png)

[回到顶部]()


### BLUETOOTH - ANDROID ONLY

*请注意，在进行下面这些步骤之前你需要使用蓝牙配对你的计算机和设备。*

1.启动 Pixate Studio 然后创建一个新的原型或者打开一个现有的文件。Pixate Studio 需要在你的移动设备建立连接之前打开。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices1.png)

2.点击 **Pixate Helper App**（Pixate 标志在菜单栏上），然后点击 **gear icon** 选择 **Bluetooth (Android) > Turn On Bluetooth Classic**。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices15.png)

3.你的设备现在应该显示在 Connect 菜单里面。找到你的设备然后点击选择目录连接。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices16.png)

当设备连接上时，你会看到手机图标变绿了。不连接设备时，点击垃圾桶图标。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices17.png)

[回到顶部]()

## 连接到 Windows 

### IP ADDRESS/PORT

**iOS** - WiFi 和蓝牙必须开启，设备和计算机必须连接到同一网络中。

**Android** - WiFi 和蓝牙必须开启，设备和计算机必须连接到同一网络中，没有 IP/AP 隔离。

1.启动 Pixate Studio 然后创建一个新的原型或者打开一个现有的文件。Pixate Studio 需要在你的移动设备建立连接之前打开。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices1.png)

2.在原型中，点击屏幕上方的 **Connect** 菜单。获取你的计算机的 IP 地址和端口号，点击信息图标，在你的计算机名字旁边。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices6.png)

3.打开 Pixate 应用然后点击 **Manual Enter IP Address**。这会提示你从 Connect 菜单进入你的计算机信息页面。或者，你可以点击你的 IP 地址界面底部的 **Scan QR code**，扫描 Connect 菜单中的二维码。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices7.png)

4.你的设备现在应该显示在 Connect 菜单里面。找到你的设备然后点击选择目录连接。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices8.png)

当设备连接上时，你会看到手机图标变绿了。不连接设备时，点击垃圾桶图标。

![image](https://raw.githubusercontent.com/ClearChan/pixate-user-guide/master/images/connect-devices9.png)

[回到顶部]()

