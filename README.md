# MIR4AV2_OPENWRT_BIN
Xiaomi Mi Router 4A Gigabit Edition v2 Openwrt images

分享个人编译使用的小米路由器4A千兆版v2固件

详见[Releases](https://github.com/roccocx/MIR4AV2_OPENWRT_BIN/releases)列表

# 固件说明
默认网关/管理地址：10.1.67.1

默认密码：password

支持IPV6,SFTP,Argon主题,负载均衡,多线多播,cloudflare-ddns

无FTP,KMS,科学上网插件，广告过滤等

因为本款路由器Flash非常小也没有USB口不能编译添加太多功能，所以这款路由器在我的日常使用定位就是作为WIFI发射路由器，IP分配和网关都是上级x86主路由完成的，

故本款固件并没有编译太多功能，无PASSWALL等任何翻墙插件（体积太大），已添加的软件包已经足够满足我的需求，所以未来更新版本对下列软件包也不会有大的变动，只是会更新openwrt内核版本

添加的的主要软件包：
openssh-sftp-server vsftpd luci-app-accesscontrol luci-app-ddns luci-app-nlbwmon luci-app-statistics luci-app-turboacc luci-app-wifischedule luci-app-argon-config ddns-scripts-cloudflare luci-app-ttyd luci-app-wrtbwmon luci-app-syncdial luci-app-mwan3 luci-app-advanced luci-app-autoreboot luci-app-fan luci-app-firewall luci-app-gpsysupgrade luci-app-opkg luci-app-upnp luci-app-wizard luci-base luci-compat luci-lib-fs luci-lib-ipkg

![Image text](https://raw.githubusercontent.com/roccocx/MIR4AV2_OPENWRT_BIN/main/img/1.png)

![Image text](https://raw.githubusercontent.com/roccocx/MIR4AV2_OPENWRT_BIN/main/img/2.png)

![Image text](https://raw.githubusercontent.com/roccocx/MIR4AV2_OPENWRT_BIN/main/img/3.png)

![Image text](https://raw.githubusercontent.com/roccocx/MIR4AV2_OPENWRT_BIN/main/img/4.png)
