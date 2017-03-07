# 软件使用说明

### HFlight 连接方式

---

**HFlight** 安卓手机地面站是 **雷讯（CUAV）** 官方推广的手机地面站，完美地兼容本公司所有产品，欢迎广大模友下载使用。软件下载链接：[HFlight](http://fw.cuav.net/apk/HFlight.apk)。

对于 PW-Link 无线数传模块，HFlight 获取和显示飞控信息的步骤如下：

 1. 确认 PW-Link 与 Pix 飞控已经连接正常；

 2. 手机搜索 WiFi 网络，连接名称为：**CUAVWlink_XXXXXX** 的网络，操作如下图；
 
  ![](images/pwlink-net-connected.png)

 3. 打开 HFlight 手机软件，选择 **UDP** 连接方式，操作如图；
  
  ![](images/pwlink-connected-type.png)

 4. 确认 UDP 服务器通信端口，检查端口是否为 **14550**；
 
  ![](/images/pwlink-udp-setting.png)

 5. 最后点击 **连接** 按钮，成功获取飞控信息后，数据界面会显示出来；

### HFlight 修改配置

---

HFlight 提供了修改 PW-Link 网络配置的窗口，允许修改网络的 **名称**、**密码**、**信道** 和 **获取版本信息**。具体的操作方式是，首先打开 HFlight 手机软件的侧边栏菜单，点击系统按钮，进入到系统设置界面，长按网络设置图标即可。操作如图所示：
 
 ![](/images/pwlink-net-cfg1.png)

PW-Link 配置窗口的具体操作步骤是，首先点击查询按钮获取 PW-Link 模块的网络信息，获取成功后，修改对应的选项即可。操作如图所示：

 ![](/images/pwlink-net-cfg2.png)

> 注意：请不要在无人机的飞行过程中修改配置，以免出现通信异常。

### Mission Planner 连接方式

---

电脑端的地面站软件以 Mission Planner 进行操作说明。具体步骤如下：

 1. 电脑使用无线网卡连接网络 **CUAVWlink_XXXXXX**，密码 **cuavwlink**；
 
 2. 打开 Mission Planner 软件，选择右上角选项 **UDP** 方式，点击连接按钮；
 
 3. 最后，在弹出的端口编辑栏输入 **14550**，点击确认；
 
 4. 等待数据接收完成；
 
> 注意：有部分用户反映，电脑已经连接上了 PW-Link 网络，但是 Mission Planner 无法接收到数据。出现这个问题的原因是因为你禁用了网络权限导致的。 解决办法是，打开 **控制面板** -> **Windows 防火墙** -> **允许应用通过防火墙进行通信** -> **打开 MP 全部网络权限**。
 

