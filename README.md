# 微信运动 api

```
hwstepranksk #抓取cookie
openid #目标openid
```

## HTTP request sample

### 获取朋友圈排行榜信息
``` JavaScript
GET /steprank/getrankandlike?rankid=latestrank HTTP/1.1
Host: hw.weixin.qq.com
Accept-Encoding: deflate
User-Agent: Mozilla/5.0 (Linux; Android 6.0.1; Nexus 5 Build/MOB30D; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/50.0.2661.86 Mobile Safari/537.36 MicroMessenger/6.3.16.64_r75b3df2.780 NetType/WIFI Language/zh_CN
X-Requested-With: com.tencent.mm
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
Cookie: hwstepranksk=yourcookie
Upgrade-Insecure-Requests: 1
Cache-Control: no-cache
```

### 获取指定openid步数
``` JavaScript
GET /steprank/getprofile?openid=anyopenid HTTP/1.1
Host: hw.weixin.qq.com
Accept-Encoding: deflate
User-Agent: Mozilla/5.0 (Linux; Android 6.0.1; Nexus 5 Build/MOB30D; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/50.0.2661.86 Mobile Safari/537.36 MicroMessenger/6.3.16.64_r75b3df2.780 NetType/WIFI Language/zh_CN
X-Requested-With: com.tencent.mm
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
Cookie: hwstepranksk=yourcookie
Upgrade-Insecure-Requests: 1
Cache-Control: no-cache
```

