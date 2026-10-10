# 飞凡科技 Windows 客户端
本仓库仅用于分发客户端安装包和更新说明，不包含项目源码或用户数据。

**当前为 Windows x64 内部未签名测试版，仅供已创建账号的受邀用户使用。**

## 下载
打开 [最新版本](https://github.com/AhKeiya/feifan-client-releases/releases/latest)，在 Assets 中下载名称以 Feifan 开头、以 win-x64-portable.zip 结尾的完整 ZIP。
请不要下载 GitHub 自动生成的 Source code 文件，它们不是客户端。

将整个 ZIP 解压到当前 Windows 用户可写的固定目录，运行 ChainDeskWinUiPrototype.exe。不要在压缩包里直接运行，也不要只复制 EXE。
无需安装 Codex、Visual Studio 或 .NET SDK。支持范围为 Windows 10 22H2 x64 / Windows 11 x64。

## 更新
新版自动检查并下载完整安装包，当前任务结束、原交易结果核验完成后再安装和重开。也可在“版本与更新”中检查更新。
下载支持服务器提供一致 ETag 时的断点续传。更新保留本机账号配置、钱包和交易记录。
普通用户下载无需 GitHub 账号或 Token。不要上传本机数据目录、私钥、助记词、密码或 API Key。

## 校验与说明
每版提供 ZIP 的 SHA256 和带发布密钥签名的 latest.json。客户端会核验更新清单、版本、大小及 ZIP 摘要。
更新清单签名不等于 Windows Authenticode 代码签名，程序仍可能显示未知发布者。
具体修复及未完成事项以每次发行说明和包内使用说明为准。
