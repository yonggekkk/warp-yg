### 相关说明及注意点请查看[warp系列视频说明](https://www.youtube.com/playlist?list=PLMgly2AulGG-WqPXPkHlqWVSfQ3XjHNw8) [更新日志](https://ygkkk.blogspot.com/2022/09/cfwarp-script.html)

### 一、WARP多功能一键脚本，支持纯IPV4、纯IPV6的VPS直接安装，主流linux系统均支持
```
bash <(wget -qO- https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh 2> /dev/null)
```
或者
```
bash <(curl -Ls https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh)
```

#### 千万要注意：如出现IP丢失、VPS运行卡顿、脚本运行下载失败、无法进入脚本界面等现象，请用以下命令终止warp，再重启或者重装warp

 1、终止warp-go：
 ```kill -15 $(pgrep warp-go)```

 2、终止wgcf：
 ```systemctl stop wg-quick@wgcf```


---------------------------------------------------------------------

### 二、多平台优选WARP对端IP + 无限生成WARP-Wireguard配置 一键脚本，建议苹果手机与安卓手机在本地网络使用
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/endip.sh -o endip.sh && chmod +x endip.sh && bash endip.sh
```

Replit平台一键无限生成WARP-Wireguard配置（须登录fork后才可运行）：https://replit.com/@yonggekkk/WARP-Wireguard-Register

--------------------------------------------------------------
### 三、Windows平台warp官方客户端优选对端IP应用程序

注意：默认只能在C盘或者桌面操作

使用方法：解压下载的（WIN端warp自选IP-v23.11.15.zip）文件，参考使用方法及视频教程

-----------------------------------------------------------
### WARP多功能VPS一键脚本界面图
![43bb749b327c7e3bd5c03f927f3a69d](https://github.com/yonggekkk/warp-yg/assets/121604513/61d2d6c0-9594-4799-9188-084bad886a66)

-----------------------------------------------------
### 交流平台：[甬哥博客地址](https://ygkkk.blogspot.com)、[甬哥YouTube频道](https://www.youtube.com/@ygkkk)、[甬哥TG电报群组](https://t.me/+jZHc6-A-1QQ5ZGVl)、[甬哥TG电报频道](https://t.me/+DkC9ZZUgEFQzMTZl)
-----------------------------------------------------
### 感谢你右上角的star🌟
[![Stargazers over time](https://starchart.cc/yonggekkk/warp-yg.svg)](https://starchart.cc/yonggekkk/warp-yg)

--------------------------------------------------------------
#### 感谢WGCF源项目代码地址：https://github.com/ViRb3/wgcf
#### 感谢CoiaPrant，WARP-GO源项目代码地址：https://gitlab.com/ProjectWARP/warp-go
#### 相关功能参考来源： [P3terx](https://github.com/P3TERX/warp.sh)、[fscarmen](https://github.com/fscarmen/warp)、[热心的CF网友](https://github.com/badafans)提供的warp endpoint优选IP脚本及注册程序

---------------------------------------
#### 声明：

#### 该项目使用base64加密，可自行解密，介意者请勿使用，[加密原因在此](https://ygkkk.blogspot.com/2022/06/github.html)

#### 所有代码来源于Github社区与ChatGPT的整合；如您需要开源代码，请提Issues留下您的联系邮箱
