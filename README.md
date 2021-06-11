# IOS 解锁 TikTok

> 目录

* [TikTok](#TikTok)
* [准备工作](#准备工作)
* [Surge配置](#Surge)

---

### <a id="TikTok"> TikTok </a>

* iOS系统版本：14.6
* TikTok版本：v19.8.0
* TikTok TF版本：v19.9.0
* 先配置好Surge再打开TikTok否则将会解锁失败，如解锁失败需卸载重装

### <a id="准备工作"> 准备工作 </a>


- 非中国大陆地区AppStore下载 TikTok

- 下载Surge并配置基础节点

---


### <a id="Surge"> Surge </a>


**操作步骤**

1、开启`Surge`(需打开Rewrite、MITM功能)

2、点击`模块``安装新的模块`复制粘贴安装想看国家的对应模块

**日本**
```
https://raw.githubusercontent.com/tangchaoliziyo/TikTok-Unlock/master/TiKok-JP.sgmodule
```
**韩国**
```
https://raw.githubusercontent.com/tangchaoliziyo/TikTok-Unlock/master/TiKok-KR.sgmodule
```

**台湾**
```
https://raw.githubusercontent.com/tangchaoliziyo/TikTok-Unlock/master/TiKok-TW.sgmodule
```

**美国**
```
https://raw.githubusercontent.com/tangchaoliziyo/TikTok-Unlock/master/TiKok-US.sgmodule
```

**英国**
```
https://raw.githubusercontent.com/tangchaoliziyo/TikTok-Unlock/master/TiKok-UK.sgmodule
```

**新加坡**
```
https://raw.githubusercontent.com/tangchaoliziyo/TikTok-Unlock/master/TiKok-SG.sgmodule
```

**泰国**
```
https://raw.githubusercontent.com/tangchaoliziyo/TikTok-Unlock/master/TiKok-TH.sgmodule
```

**加拿大**
```
https://raw.githubusercontent.com/tangchaoliziyo/TikTok-Unlock/master/TiKok-CA.sgmodule
```

**澳大利亚**
```
https://raw.githubusercontent.com/tangchaoliziyo/TikTok-Unlock/master/TiKok-AU.sgmodule
```

3、在代理规则中添加以下`外部规则集`并选择对应的策略

```
https://raw.githubusercontent.com/tangchaoliziyo/TikTok-Unlock/master/TikTok-Unlock.list
```

4、打开Tik Tok开始网上冲浪

---
