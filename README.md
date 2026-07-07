![](https://visitor-badge.glitch.me/badge?page_id=bleachwrt-visitor-badge)
[![](https://img.shields.io/badge/TG群-点击加入-FFFFFF.svg)](https://t.me/+T-QQ4cpDFx83YTM1)
[![](https://img.shields.io/badge/QQ群-点击加入-FFFFFF.svg)](https://qm.qq.com/cgi-bin/qm/qr?k=zqlN1N9mkYMXCr6fHtnHApQFNmCEj_kV&jump_from=webapi)

![openwrt](https://user-images.githubusercontent.com/47608286/116703960-6fa77e80-a9fd-11eb-8077-f38610a4babc.png)


欢迎来到bleachwrt的源码仓库！
=
[![](https://img.shields.io/badge/-目录:-696969.svg)](#readme) [![](https://img.shields.io/badge/-固件说明-F5F5F5.svg)](#固件说明-) [![](https://img.shields.io/badge/-登陆信息-F5F5F5.svg)](#登陆信息-)  [![](https://img.shields.io/badge/-固件下载-F5F5F5.svg)](#固件下载-) [![](https://img.shields.io/badge/-固件定制-F5F5F5.svg)](#固件定制-) [![](https://img.shields.io/badge/-固件介绍-F5F5F5.svg)](#固件介绍-) [![](https://img.shields.io/badge/-捐助-F5F5F5.svg)](#捐助-) 
------------------------------------------------------

**因精力有限不提供任何技术支持和教程等相关问题解答。不保证插件完全无BUG，特此公告！**

### 恩山链接 x86_64 ：
https://www.right.com.cn/forum/forum.php?mod=viewthread&tid=8480683&fromuid=559447
### 恩山链接 红米AX6000/小米AX3000T/WR30U/多酷TR3000/磊科N60PRO/360T7/NX30PRO 等 mt798x设备 ：
https://www.right.com.cn/forum/forum.php?mod=viewthread&tid=8480686&fromuid=559447
### 恩山链接 小米AC2100/红米AC2100/小米CR660X/小米R3G/NEWIFI-D2 等 mt7621设备 ：
https://www.right.com.cn/forum/forum.php?mod=viewthread&tid=8480687&fromuid=559447
### 恩山链接 R2S/R2C/R4S/R5S/R66S/R68S 等 rockchip设备 ：
https://www.right.com.cn/forum/forum.php?mod=viewthread&tid=8480680&fromuid=559447
### 恩山链接 Raspberry Pi 4/5 ：
https://www.right.com.cn/forum/forum.php?mod=viewthread&tid=8379758&fromuid=559447
### 恩山链接 JDCloud ER1/AX6600/AX1800PRO 小米AX3600/AX9000 等 Qualcomm设备 ：
https://www.right.com.cn/forum/forum.php?mod=viewthread&tid=8480684&fromuid=559447

------------------------------------------------------

## 【免责声明】
**1.仅限完全行为能力人使用本固件，使用本固件即视为使用者的自愿行为;**

**2.本人不对任何人因使用本固件所遭受的任何理论或实际的损失承担责任;**

**3.本人不保证固件的普适性，不保证无bug，不保证绝对的安全稳定。**

----------------------------------------------------

**本固件基于lean大佬的源码编译，外加一些额外的软件包，主要使用源码如下：**

- https://github.com/0x676e67/luci-app-design-config.git
- https://github.com/0x676e67/luci-theme-design.git
- https://github.com/AlexZhuo/luci-app-bandwidthd.git
- https://github.com/BoringCat/luci-app-mentohust.git
- https://github.com/BoringCat/luci-app-minieap.git
- https://github.com/BoringCat/minieap-openwrt.git
- https://github.com/CHN-beta/rkp-ipid.git
- https://github.com/destan19/OpenAppFilter.git
- https://github.com/EasyTier/luci-app-easytier.git
- https://github.com/esirplayground/luci-app-poweroff.git
- https://github.com/frainzy1477/luci-app-clash.git
- https://github.com/FUjr/QModem.git
- https://github.com/fw876/helloworld.git
- https://github.com/garypang13/luci-theme-edge.git
- https://github.com/ghosthgytop/luci-app-npc.git
- https://github.com/hejiadong0608/luci-app-msd_lite.git
- https://github.com/honwen/luci-app-aliddns.git
- https://github.com/iwrt/luci-app-ikoolproxy.git
- https://github.com/jerrykuku/go-aliyundrive-webdav.git
- https://github.com/jerrykuku/lua-maxminddb.git
- https://github.com/jerrykuku/luci-app-argon-config.git
- https://github.com/jerrykuku/luci-app-go-aliyundrive-webdav.git
- https://github.com/jerrykuku/luci-theme-argon.git
- https://github.com/kiddin9/luci-app-dnsfilter.git
- https://github.com/linkease/istore.git
- https://github.com/lucikap/luci-app-ua2f.git
- https://github.com/lwb1978/openwrt-gecoosac.git
- https://github.com/mchome/luci-app-dogcom.git
- https://github.com/mchome/openwrt-dogcom.git
- https://github.com/miaoermua/luci-app-leigod-acc.git
- https://github.com/MilesPoupart/luci-app-vssr.git
- https://github.com/NateLol/luci-app-bearDropper.git
- https://github.com/NONGFAH/luci-app-athena-led.git
- https://github.com/openwrt-develop/luci-theme-atmaterial.git
- https://github.com/Openwrt-Passwall/openwrt-passwall2.git
- https://github.com/Openwrt-Passwall/openwrt-passwall.git
- https://github.com/Openwrt-Passwall/openwrt-passwall-packages.git
- https://github.com/ParticleG/luci-app-macvlan.git
- https://github.com/pymumu/luci-app-smartdns.git
- https://github.com/pymumu/openwrt-smartdns.git
- https://github.com/QiuSimons/luci-app-daed.git
- https://github.com/QiuSimons/luci-app-dae.git
- https://github.com/QiuSimons/vmlinux-btf.git
- https://github.com/riverscn/openwrt-iptvhelper.git
- https://github.com/rosywrt/luci-theme-rosy.git
- https://github.com/rufengsuixing/luci-app-adguardhome.git
- https://github.com/sbwml/luci-app-alist.git
- https://github.com/sbwml/luci-app-mosdns.git
- https://github.com/selfcan/luci-app-homebox.git
- https://github.com/selfcan/luci-app-onliner.git
- https://github.com/sirpdboy/luci-app-advanced.git
- https://github.com/sirpdboy/luci-app-chatgpt-web.git
- https://github.com/sirpdboy/luci-app-cupsd.git
- https://github.com/sirpdboy/luci-app-ddns-go.git
- https://github.com/sirpdboy/luci-app-eqosplus.git
- https://github.com/sirpdboy/luci-app-partexp.git
- https://github.com/sirpdboy/luci-theme-opentopd.git
- https://github.com/sirpdboy/netspeedtest.git
- https://github.com/Tencent-Cloud-Plugins/tencentcloud-openwrt-plugin-ddns.git
- https://github.com/thinktip/luci-theme-neobird.git
- https://github.com/tty228/luci-app-serverchan.git
- https://github.com/vernesong/OpenClash.git
- https://github.com/xiaoqingfengATGH/luci-theme-infinityfreedom.git
- https://github.com/Zxilly/UA2F.git


### 固件说明 [![](https://img.shields.io/badge/-固件说明-F5F5F5.svg)](#固件说明-) 
---------------------------------------------------

1、本固件本人保证没加入任何后门**

2、强烈建议不保留配置刷入本固件，可以减少很多问题，如果此前是刷的本人固件可以同版本保留配置升级**

3、不管什么问题请先自己学习研究再寻求帮助，群里的人没有义务来帮你以及回复一些无聊与无知的问题，需要帮助的可以去某**



### 补充说明 [![](https://img.shields.io/badge/-补充说明-F5F5F5.svg)](#补充说明-) 
---------------------------------------------------
**主要提供x86_64及R2S，R4S固件**

**固件主要分为高大全版(plus)和精简版(mini)**

**文件下载请看文件夹名称下载**

**如文件夹名中：\x86_64\2021-04-03__05-03-19--plus-daily表示x86_64高大全版本，编译时间为2021年4月3日**

**固件每日凌晨4点自动重新编译发布，保留历史版本，下载最新版本即可**


### 登陆信息 [![](https://img.shields.io/badge/-登陆信息-F5F5F5.svg)](#登陆信息-) 
---------------------------------------------------------------------------------------  

**初始管理地址：192.168.1.1**

**初始管理用户：root**

**初始管理密码：password**

---------------------------------------------------------------------------------------

### 固件下载 [![](https://img.shields.io/badge/-固件下载-F5F5F5.svg)](#固件下载-) 

**x86_64下载链接：https://openwrt.mpdn.fun/?dir=lede/x86_64/**

**R2S/R4S/R5S/R66S/R68S下载链接：https://openwrt.mpdn.fun/?dir=lede/rockchip/**

**Xiaomi_Redmi-AX6000下载链接：https://openwrt.mpdn.fun/?dir=lede/mtk/**

**Xiaomi_(Redmi/mi)-AC2100下载链接：https://openwrt.mpdn.fun/?dir=lede/mtk/**

**树莓派Raspberry Pi 4下载链接：https://openwrt.mpdn.fun/?dir=lede/bcm/**

**谷歌云下载链接：https://drive.google.com/drive/folders/1g2ROF2M9ZsUEgGHm-Mo3Ap5m4Azr9zk9?usp=sharing**

**加入固件电报群：https://t.me/+T-QQ4cpDFx83YTM1**

--------------------------------------------------------------

### 固件定制：[![](https://img.shields.io/badge/-固件定制-F5F5F5.svg)](#固件定制-)

**另外如果觉得插件太多会影响稳定性，需要精简一些的话**

**可提供有偿定制固件服务，有需要的可以联系我**

**提供全平台的定制服务，不仅仅是x86，其他各种硬路由平台也支持。**

**比如x86/高通(gdock)/博通(k3)/MTK(k2p,newifi3)/atheros/marvell/allwinner/qemu等**

**定制链接：http://openwrt2020.mikecrm.com/y3E3EtB**

**联系我：**

**电报：https://t.me/yxw1991**

**qq：(2637183346) http://wpa.qq.com/msgrd?v=3&uin=2637183346&site=qq&menu=yes**




--------------------------------------------------------------


## 固件介绍 [![](https://img.shields.io/badge/-固件介绍-F5F5F5.svg)](#固件介绍-)


![xm1](img/menu/large-plus-20250623.png)
![xm1](img/menu/large-mini-20250623.png)
![xm1](img/plugin/01-状态-概览.png)
![xm1](img/plugin/01-状态-实时监控.png)
![xm1](img/plugin/02-系统-TTYD终端.png)
![xm1](img/plugin/00-iStore-全部软件.png)
![xm1](img/plugin/03-Docker-概览.png)
![xm1](img/plugin/04-服务-PassWall.png)
![xm1](img/plugin/04-服务-PassWall2.png)
![xm1](img/plugin/04-服务-OpenClash.png)
![xm1](img/plugin/04-服务-ShadowSocksRPlus+.png)
![xm1](img/plugin/04-服务-MosDNS.png)
![xm1](img/plugin/04-服务-应用过滤.png)
![xm1](img/plugin/04-服务-雷神加速器.png)
![xm1](img/plugin/05-管控-集客AC控制器.png)
![xm1](img/plugin/08-网络-TurboACC网络加速.png)
![xm1](img/plugin/09-带宽监控-实时流量监测.png)

**感谢LEAN大，感谢Lienol大 等大神分享源码，你可以随意使用其中的源码，但请注明出处。**


## 捐助 [![](https://img.shields.io/badge/-捐助-F5F5F5.svg)](#捐助-) 

**如果你觉得此项目对你有帮助，请捐助我们，以使项目能持续发展，更加完善。··请作者喝杯咖啡~~~**

**你们的支持就是我的动力！**

### 捐助方式

|     <img src="https://img.shields.io/badge/-支付宝-F5F5F5.svg" href="#赞助支持本项目-" height="25" alt="图飞了😂"/>  |  <img src="https://img.shields.io/badge/-微信-F5F5F5.svg" height="25" alt="图飞了😂" href="#赞助支持本项目-"/>  | 
| :-----------------: | :-------------: |
|<img src="https://user-images.githubusercontent.com/47608286/116705490-2a844c00-a9ff-11eb-9b90-8e7378aae332.jpg" width="150" height="150" alt="图飞了😂" href="#赞助支持本项目-"/>|<img src="https://user-images.githubusercontent.com/47608286/116706779-94512580-aa00-11eb-9e0c-ade6ca5f0a87.png" width="150" height="150" alt="图飞了😂" href="#赞助支持本项目-"/>|

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-orange.svg" alt="图飞了😂" title="返回顶部" align="right"/>
</a>

[![](https://img.shields.io/badge/TG群-点击加入-FFFFFF.svg)](https://t.me/+T-QQ4cpDFx83YTM1)
[![](https://img.shields.io/badge/QQ群-点击加入-FFFFFF.svg)](https://qm.qq.com/cgi-bin/qm/qr?k=zqlN1N9mkYMXCr6fHtnHApQFNmCEj_kV&jump_from=webapi)
