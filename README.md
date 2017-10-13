## wangcb.cc上的小壁虎们
### 主用配置(ss):
```
ss://Y2hhY2hhMjA6Q1RZREREREREQlVH@ss.wangcb.cc:8080#ss.wangcb.cc
```
使用方法：将上面这串URL导入到客户端内

若主用配置无法使用，请去[备用配置](#%E5%A4%87%E7%94%A8%E9%85%8D%E7%BD%AE)
### ss客户端下载:
- Windows
    + [https://github.com/shadowsocks/shadowsocks-windows/releases](https://github.com/shadowsocks/shadowsocks-windows/releases)
- Android
    + [https://github.com/shadowsocks/shadowsocks-android/releases](https://github.com/shadowsocks/shadowsocks-android/releases)
- OS X
    + [https://github.com/shadowsocks/ShadowsocksX-NG/releases](https://github.com/shadowsocks/ShadowsocksX-NG/releases)
- iOS
    + [Wingy(App Store)](https://itunes.apple.com/us/app/wingy-http-s-socks5-proxy-utility/id1178584911)

### 备用配置:
所有备用配置使用[v2ray软件](https://www.v2ray.com/)作为代理软件。使用此软件，通常通过配置文件连接。
- 基于[mKCP](https://www.v2ray.com/chapter_04/mkcp.html)底层传输的备用配置
    + 配置文件:[client_mkcp.json](./client_mkcp.json)
- 基于WebSocket底层传输的备用配置，注意此配置使用了Cloudflare CDN代理，有着较好的穿透性，但也损失了较大性能。
    + 配置文件:[client_ws.json](./client_ws.json)
- 基于http底层传输的备用配置
    + 配置文件:[client_http.json](./client_http.json)

### v2ray客户端下载:
- Windows, Linux, OS X
    + [官方v2ray-core](https://github.com/v2ray/v2ray-core/releases)
- Android
    + [Actinium](https://github.com/V2Ray-Android/Actinium/releases)
- iOS
    + [Shadowrocket(App Store, 付费软件$2.99)](https://itunes.apple.com/us/app/shadowrocket/id932747118?mt=8)
