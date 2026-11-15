# 学习通助手下载与更新

此仓库用于发布激活码版程序和在线更新信息。

## 下载

- [浏览器激活码版](https://github.com/Flouspi/chaoxing-helper-releases/releases/latest/download/study-helper-browser.exe)：通过 Microsoft Edge 打开课程。
- [PC 客户端激活码版](https://github.com/Flouspi/chaoxing-helper-releases/releases/latest/download/study-helper-pc.exe)：配合已安装的学习通 PC 客户端使用。
- [版本说明](https://github.com/Flouspi/chaoxing-helper-releases/releases/latest)

下载后双击 EXE，无需安装 Python。首次使用需向提供者发送机器码，并填写收到的激活码；账号和验证码只在学习通官方页面输入。

## 程序内更新

建议使用 BETA1.9.3 或更新版本。激活码版可以在程序顶部点击“检查更新”，查看说明并下载新版。下载完成后，停止本轮课程任务，再点击“安装并重启”。

此前没有在线更新入口的旧版，需要手动换上 BETA1.9.3 或更新版本一次。将新 EXE 放回原文件夹并保留 `.runtime`，可沿用本机配置。

程序会核对更新信息签名、下载大小和 SHA-256，再安装对应版本。更新保留本机激活与 API 设置；课程记录以平台实际显示为准。

使用说明和迭代日志已内置在程序里。

## 磁盘与缓存

BETA1.9.3 的运行组件首次展开后会重复使用，优先放在空间充足、可写的非系统固定磁盘。运行组件按 4 GiB 预算管理，回收未使用的旧组件，运行中的组件受保护。没有合适的非系统磁盘时才使用系统盘缓存。

临时文件跟随组件缓存并在退出后清理。账号、授权和 API 配置保留；实际路径见程序文件夹的 `.runtime/缓存位置.txt`。
