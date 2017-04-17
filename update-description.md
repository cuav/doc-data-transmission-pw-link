# 更新程序说明

目前对于 PW-Link 模块并没有提供在线更新程序，需要用户手动更新程序。需要下载 [烧录软件](http://fw.cuav.net/pc/ESP8266Flasher.rar) 和 [最新版程序包](http://fw.cuav.net/pc/wifilink.rar)。具体的烧录步骤如下：
 
 1. 运行烧录软件，点击 **Advanced** 选项，修改对应选项如图；
 
  ![](/images/pwlink-update-advanced.png)
  
 2. 点击 **Config** 选项，点击红色框框的图标，选择对应更新程序的路径；
 
  ![](/images/pwlink-update-config.png)
  
 3. 点击 **Operation** 选项，使用 **烧录线** 将 TTL 板与 PW-Link 模块相连，选择对应的端口，点击 **Flash** 按钮;
  
  ![](/images/pwlink-update-operation.png)
  
 4. 烧录成功提示图如下；
 
  ![](/images/pwlink-update-msg.png)
 
> 目前最新版本为：1.6.0，支持模块正常运行后，IO0 短接 GND 超过 5S 即恢复网络默认配置的功能，蓝灯常亮或者熄灭表示恢复完成。切记不要同时短接和上电，这样是进入烧录程序模式。