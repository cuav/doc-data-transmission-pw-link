# 概述

---

WP\_LINK是一款WIFI转串口模块，只需要通过电脑或者手机的WIFI

即可连接飞控进行调参和设置,通过简单可靠的UDP通讯

使用内置天线距离可达50米\*，外置天线300-500米\*.

通过CUAV地面站Hflight 即可设置WIFI频道、名称及密码

兼容电脑地面站：Mission Planner、QGC

手机地面站：tower、CUAV  Hflight、QGC

## 系统框架

---

![](/assets/wp-link.png)

### 规格

---

| 无线标准 | IEEE 802.11g、IEEE 802.11b |
| :--- | :--- |
| 无线传输速率 | 11g:最高可达54Mbps   11b:最高达11Mbps |
| 信道数量 | 1-14\(默认11通道\) |
| 频率范围 | 2.4-2.4835G |
| 发射功率 | 18dbm |
| 天线类型 | UFL |
| 无线安全 | WPA/WPA2安全机制 |
| 传输速率 | 57600 |
| 接口协议 | TTL透明 |
| 连接方式及端口 | UDP 14550 |
| **工作环境** |  |
| 工作电压 | 5V +-0.25V |
| 工作电流 | 100MA |
| 工作温度 | -20~+50° |
| 工作湿度 | 10 |
| 存储温度 | 10%-90%RH（不凝结） |
| 存储湿度 | 5%-90%RH（不凝结） |

### 接口定义

---

### 默认SSID及密码

---

默认SSID为CUAVWLINK\_XXXXXX \(XXXXXX为MAC后缀6位\)  
默认密码为（小写）： cuavwlink

