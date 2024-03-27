### Relevant Instructions and Notes: [WARP Series Video Instructions](https://www.youtube.com/playlist?list=PLMgly2AulGG-WqPXPkHlqWVSfQ3XjHNw8) [Changelog](https://ygkkk.blogspot.com/2022/09/cfwarp-script.html)

### I. WARP Multifunctional One-click Script, Supports Direct Installation on VPS with Pure IPv4 or Pure IPv6, Compatible with Mainstream Linux Systems
```bash
bash <(wget -qO- https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh 2> /dev/null)
```
or
```bash
bash <(curl -Ls https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh)
```

#### Please Note: If IP Loss, VPS Lagging, Script Download Failure, or Inability to Enter Script Interface Occurs, Terminate warp with the Following Commands, Then Restart or Reinstall warp

1. Terminate warp-go:
```bash
kill -15 $(pgrep warp-go)
```

2. Terminate wgcf:
```bash
systemctl stop wg-quick@wgcf
```

---------------------------------------------------------------------

### II. Cross-platform Preferred WARP Peer IP + Unlimited WARP-Wireguard Configuration Generation One-click Script, Recommended for Use on Local Networks with Apple and Android Phones
```bash
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/endip.sh -o endip.sh && chmod +x endip.sh && bash endip.sh
```

Replit Platform One-click Unlimited WARP-Wireguard Configuration Generation (Requires Login and Fork to Run): [Replit WARP-Wireguard Register](https://replit.com/@yonggekkk/WARP-Wireguard-Register)

--------------------------------------------------------------
### III. Windows Platform WARP Official Client Preferred Peer IP Application

Note: Can Only Operate on C Drive or Desktop by Default

Usage: Unzip the downloaded (WIN-end-warp-optional-IP-v23.11.15.zip) file, Refer to Usage Instructions and Video Tutorial

-----------------------------------------------------------
### WARP Multifunctional VPS One-click Script Interface Image
![Script Interface](https://github.com/yonggekkk/warp-yg/assets/121604513/61d2d6c0-9594-4799-9188-084bad886a66)

-----------------------------------------------------
### Thank You for Your Star in the Upper Right Corner 🌟
[![Stargazers Over Time](https://starchart.cc/yonggekkk/warp-yg.svg)](https://starchart.cc/yonggekkk/warp-yg)

--------------------------------------------------------------
#### Thanks to WGCF Source Project Code Address: [WGCF Repository](https://github.com/ViRb3/wgcf)
#### Thanks to CoiaPrant, WARP-GO Source Project Code Address: [WARP-GO Repository](https://gitlab.com/ProjectWARP/warp-go)
#### Related Function References: [P3terx](https://github.com/P3TERX/warp.sh), [fscarmen](https://github.com/fscarmen/warp), End-User IP Script and Registration Program Provided by Enthusiastic CF Netizens

---------------------------------------
#### Disclaimer:

#### This project uses base64 encryption, which can be decrypted by oneself. Those who mind, please do not use it. [Reasons for Encryption](https://ygkkk.blogspot.com/2022/06/github.html)

#### All code comes from the GitHub community and ChatGPT integration; If you need open source code, please provide your contact email by raising Issues.
