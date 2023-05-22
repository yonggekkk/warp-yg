### 相关说明及注意点请查看[warp系列视频说明](https://www.youtube.com/playlist?list=PLMgly2AulGG-WqPXPkHlqWVSfQ3XjHNw8) [更新日志](https://ygkkk.blogspot.com/2022/09/cfwarp-script.html)

### 一、WARP多功能VPS一键脚本，支持纯IPV4、纯IPV6的VPS直接安装，主流linux系统均支持

```
wget -N https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh && bash CFwarp.sh
```

#### 1、强制终止warp-go：```kill -15 $(pgrep warp-go) ```

#### 2、终止wgcf：```systemctl stop wg-quick@wgcf```

#### 3、关于warp在线监测机制（仅支持方案一）：

---------------------------------------------------------------------

### 二、多平台优选WARP对端IP脚本
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/endip.sh -o endip.sh && chmod +x endip.sh && ./endip.sh
```
--------------------------------------------------------------
### 三、Windows平台warp官方客户端优选对端IP应用程序

使用方法：解压下载的（WIN端warp自选IP(手动+自动).zip）文件，参考使用方法及视频教程

--------------------------------------------------------------

### 以上脚本源码备份[Gitlab地址](https://gitlab.com/rwkgyg/CFwarp)
-----------------------------------------------------------
### WARP多功能VPS一键脚本界面图
![98ae45b09a62a30f4281bdae8586c6d](https://user-images.githubusercontent.com/121604513/230701599-1701d8a4-367c-41ab-bdae-ed05cf5100d1.png)

