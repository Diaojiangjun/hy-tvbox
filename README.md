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

注意：`tvbox.json` 中的 `spider` 使用 GitHub raw 地址（jsDelivr 不支持分发 `.jar`）。国内网络若无法下载 raw 地址，可改用加速前缀，例如 `https://ghproxy.net/https://raw.githubusercontent.com/Diaojiangjun/hy-tvbox/main/jar/custom_spider.jar`。
