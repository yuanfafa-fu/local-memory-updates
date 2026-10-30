# local-memory-updates

Local Memory Console 的公网更新源：存放 Tauri 更新清单 `latest.json` 与签名安装包。

- 客户端编译内端点为 `https://github.com/yuanfafa-fu/local-memory-updates/releases/latest/download/latest.json`
- 安装包由 minisign 更新签名保护，trusted comment 绑定版本号
- 源码仓库为私有仓，此仓仅承载发布产物的公开下载
