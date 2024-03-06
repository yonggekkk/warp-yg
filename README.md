# Warp and Warp +
#### 

 1.One-click multipurpose WARP script supports direct installation of pure IPV4 and pure IPV6 VPS and is supported by mainstream Linux systems
```
bash <(wget -qO- https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh 2> /dev/null)
```
or
```
bash <(curl -Ls https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh)
```

#### Be careful!!!: If IP lost, VPS operation stuck, script download failed, script interface failed to enter, etc., please use the command below to terminate Warp, then restart or install Warp.

 1-Termination of warp-go :
 
 ```kill -15 $(pgrep warp-go)```

 2-Termination of wgcf :  
 
 ```systemctl stop wg-quick@wgcf```


---------------------------------------------------------------------
### 2. Android, Linux and Mac

1.Copy the [Config file] to an editor.

###  Multi-platform IP peer WARP optimization + unlimited generation of WARP-Wireguard configurations.

##Run the below command in the termux(Android Shell), linux or mac.The command for finding the clean IP/Ports is from Warp Cloudflare.
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/endip.sh -o endip.sh && chmod +x endip.sh && bash endip.sh
```


--------------------------------------------------------------
### 3. Windows platform warp official client prefers peer IP application

Note: The default can only be operated on the C drive or desktop

How to use: Unzip the download (WIN WIN WIRP optional IP-V23.11.15.zip) file, reference usage and video tutorial

-----------------------------------------------------------
### Warp Multifunctional VPS One -button Discover Face Map
```
![43bb749b327c7e3bd5c03f927f3a69d](https://github.com/yonggekkk/warp-yg/assets/121604513/61d2d6c0-9594-4799-9188-084bad886a66)
```
-----------------------------------------------------
### Thank you Star🌟 in the upper right corner


--------------------------------------------------------------
#### https://github.com/ViRb3/wgcf
#### WARP-GO：https://gitlab.com/ProjectWARP/warp-go
#### Related function reference source： [P3terx](https://github.com/P3TERX/warp.sh)、[fscarmen](https://github.com/fscarmen/warp)、[Enthusiastic CF netizens](https://github.com/badafans)Provided by WARP ednpoint preferred IP script and registration program

---------------------------------------
#### statement：

#### This project uses base64 encryption, you can decrypt yourself, please do not use it, [The reason for the encryption is here](https://ygkkk.blogspot.com/2022/06/github.html)

#### All code comes from the integration of the GitHub community and ChatGPT; if you need an open source code, please mention it to your contact mailbox
