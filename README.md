# ⭐Xray-core/sing-box 一键脚本快速安装

## 核心

- Xray-core
- v2ray-core[暂停维护]
- sing-box

## 协议

> 以下均使用TLS，支持多种协议组合

- VLESS(Reality、Vision、TCP、WS、gRPC)
- VMess(TCP、WS)
- Trojan(TCP、gRPC)
- Hysteria2
- Tuic

## 功能

- [支持无域名版本的VLESS Reality搭建](https://www.v2ray-agent.com/archives/1680104902581)
- [支持多种分流用于解锁（wireguard、IPv6、任意门、DNS、VMess(ws)、SNI反向代理）](https://www.v2ray-agent.com/archives/ba-he-yi-jiao-ben-yu-ming-fen-liu-jiao-cheng)
- [支持批量添加CDN节点并配合ClashMeta自动优选](https://www.v2ray-agent.com/archives/1684858575649)
- 支持证书自动申请及更新
- [支持订阅以及多VPS组合订阅](https://www.v2ray-agent.com/archives/1681804748677)
- 支持批量新增端口
- 支持核心的升级以及回退
- 支持自主更换伪装站点
- 支持BT下载管理以及域名黑名单管理


# 二、使用指南

- [脚本快速搭建教程](https://www.v2ray-agent.com/archives/1682491479771)
- [垃圾VPS大救星，hysteria2最新协议一键搭建](https://www.v2ray-agent.com/archives/1697162969693)
- [Tuic V5性能提升及使用方法](https://www.v2ray-agent.com/archives/1687167522196)
- [Cloudflare优选IP、自动选择最快节点教程](https://www.v2ray-agent.com/archives/1684858575649)
- [脚本异常处理](https://www.v2ray-agent.com/archives/1684115970026)

# 三、线路推荐

> 再好的协议也比不上一个高品质的VPS。推荐以下线路

- [VPS选购指南,避坑指南](https://www.v2ray-agent.com/archives/1679975663984)
- [CN2 GIA](https://www.v2ray-agent.com/tags/cn2-gia)
- [AS9929](https://www.v2ray-agent.com/tags/as9929)
- [AS4837](https://www.v2ray-agent.com/tags/as4837)
- [日本软银](https://www.v2ray-agent.com/tags/ruan-yin)
- [CMI](https://www.v2ray-agent.com/tags/cmi)

# ⭐安装使用

## 下载脚本

- 支持快捷方式启动，安装完毕后，shell输入【**vasma**】即可打开脚本，脚本执行路径[**/etc/v2ray-agent/install.sh**]

- ⭐Github

```
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/oooobjective/xray/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh
```

# 六、许可证

[AGPL-3.0](https://github.com/mack-a/v2ray-agent/blob/master/LICENSE)
