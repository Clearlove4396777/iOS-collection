
```
自用Surge模块、Loon插件、机场图标以及规则集
```


## 简介
* **Airport_Logo** 
  * 包含自用机场图标
* **LoonPlugin** 
  * 包含自用Loon插件
* **Rule**    
  * 包含 `AppleDownload` `DMM` `Telegram` `TruthSocial`远程规则集
* **sgmodule**  
  * 包含自用Surge（Shadowrocket）模块

 
## 使用说明
* 安装`Rule`:

**Loon**
 

```ini
https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/AppleDownload.list, policy=[Replace with your Policy Group], tag=AppleDownload,enabled=true
```
```ini
https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/DMM.list, policy=[Replace with your JP Policy Group],tag=DMM,enabled=true
```
```ini
https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/TelegramNL.list, policy=[Replace with your EU Policy Group],tag=TelegramNL,enabled=true
```
```ini
https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/TelegramSG.list, policy=[Replace with your SG Policy Group],tag=TelegramSG,enabled=true
```
```ini
https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/TelegramUS.list, policy=[Replace with your US Policy Group],tag=TelegramNL,enabled=true
```
```ini
https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/TruthSocial.list, policy=[Replace with your US Policy Group],tag=Truth Social,enabled=true
```
**Surge**



```ini
RULE-SET,https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/AppleDownload.list, [Replace with your Policy Group]
```
```ini
RULE-SET,https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/DMM.list, [Replace with your JP Policy Group]
```
```ini
RULE-SET,https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/TelegramNL.list, [Replace with your EU Policy Group]
```
```ini
RULE-SET,https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/TelegramSG.list, [Replace with your SG Policy Group]
```
```ini
RULE-SET,https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/TelegramUS.list, [Replace with your US Policy Group]
```
```ini
RULE-SET,https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Rule/TruthSocial.list, [Replace with your US Policy Group]
```



- 建议**AppleDownload**的流量分配给公共代理服务或低倍率结算流量消耗的节点
- 建议**DMM**使用🇯🇵策略组
-  建议**TelegramNL**使用🇪🇺策略组—推荐DC2&DC4用户使用
-  建议**TelegramSG**使用🇸🇬策略组—推荐DC5用户使用
-  建议**TelegramUS**使用🇺🇸策略组—推荐DC1&DC3用户使用
- 建议**TruthSocial**使用🇺🇸策略组




## 安装链接
  *需要启用`重写`、`脚本`、`MitM`功能

  * Loon:
    * 🆕点击一键安装: [AirPort_Logo](https://www.nsloon.com/openloon/import?iconset=https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/Airport_Logo/Airport_Logo.json "AirPort_Logo") 
    * 🆕点击一键安装: [Bilibili.plugin](https://www.nsloon.com/openloon/import?plugin=ttps://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/LoonPlugin/Bilibili.plugin "Bilibili.plugin") 
    * 🆕点击一键安装: [Emby.plugin](https://www.nsloon.com/openloon/import?plugin=ttps://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/LoonPlugin/Emby.plugin "Emby.plugin") 
    * 🆕点击一键安装: [Weibo.plugin](https://www.nsloon.com/openloon/import?plugin=ttps://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/LoonPlugin/Weibo.plugin "Weibo.plugin")
    * 🆕点击一键安装: [YoutubeAD.plugin](https://www.nsloon.com/openloon/import?plugin=ttps://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/LoonPlugin/YoutubeAD.plugin "YoutubeAD.plugin")  
    * 🆕点击一键安装: [newBing.plugin](https://www.nsloon.com/openloon/import?plugin=ttps://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/LoonPlugin/newBing.plugin "newBing.plugin")  

  * Quantumult X:
    * 🆕点击一键安装: [AirPort_Logo](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FClearLuv%2FiOS_collecton%2Fmain%2FAirport_Logo%2FAirport_Logo.json%22%0A%5D "AirPort_Logo 自用机场图标")

    
  * Surge(Shadowrocket):
    
    * `模块`链接: [115.sgmodule](https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/sgmodule/115.sgmodule " 115离线")
    *  `模块`链接: [Bilibili.sgmodule](https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/sgmodule/Bilibili.sgmodule " Bilibili合集")
    *  `模块`链接: [NeteaseMusicAD.sgmodule](https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/sgmodule/NeteaseMuiscAD.sgmodule " 网易云音乐去广告")
    *  `模块`链接: [Weibo.sgmodule](https://raw.githubusercontent.com/ClearLuv/iOS_collecton/main/sgmodule/Weibo.sgmodule " 微博去广告")







