# hy-tvbox

TVBox 影视接口配置仓库。

## 文件说明

- `tvbox.json`：TVBox 接口配置（订阅地址），包含 spider 与站点列表
- `jar/custom_spider.jar`：自定义爬虫 jar 包
- `jar/custom_spider.jar.md5`：jar 包 MD5 校验值
- `promo.png`：宣传图

## 使用方式

在 TVBox / 影视 App 中添加配置地址，指向本仓库的 `tvbox.json` 原始链接即可：

```
https://raw.githubusercontent.com/Diaojiangjun/hy-tvbox/main/tvbox.json
```

注意：`tvbox.json` 中的 `spider` 指向本仓库的 jsDelivr 公网地址，更新 jar 后如 CDN 未刷新，可访问 `https://purge.jsdelivr.net/gh/Diaojiangjun/hy-tvbox@main/jar/custom_spider.jar` 手动刷新缓存。
