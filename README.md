# 拾页 · 桌面试用版下载

个人收藏与笔记工具。把链接或文件整理为存档，使用自己的模型 API 进行总结。资料保存在使用者自己的电脑。

## 下载

打开 [下载页面](https://github.com/fundops-notes/shiye-downloads/releases/latest)，在 Assets 中选择：

- **Shiye-Windows-Trial.zip**：Windows 10/11 x64，内含 Python。
- **Shiye-Mac-Trial.zip**：目标 macOS 13+，Apple 芯片与 Intel，尚待 Mac 实机验收。

如果 latest 没有显示版本，请打开 [全部版本](https://github.com/fundops-notes/shiye-downloads/releases)。当前均为预发布试用包，不需要仓库邀请即可下载。

## 开始使用

1. 解压整个文件夹到固定位置。
2. Windows 双击「启动拾页.cmd」；Mac 双击「启动拾页.command」。
3. 首次启动联网准备运行依赖，可能需要下载较多文件。不是完全离线包，无需手动安装 Python。
4. 网页自动打开，用同时显示的邀请码注册本机账号，再配置自己的模型 API。
5. 保持启动窗口打开；任务结束后按 Ctrl+C / Control+C 退出。

API 费用以自己的服务商账单为准，不提供共享密钥或赠送额度。平台专用提取、本机 Whisper 通过单独入口按需安装；图片 OCR 不含在基础包中。可用平台受来源网站与网络限制，云端语音接口仍需实际 Key 验证。

## 数据与更新

- Windows 数据：`%LOCALAPPDATA%/Shiye`
- Mac 数据：`~/Library/Application Support/Shiye`

更新前退出旧版并在网页中备份。新程序沿用上述数据位置。不要发送数据库、API Key、credential.key 或自己的数据目录给他人。

## 验证范围

Windows 包已在隔离目录用自带 Python 完成依赖安装、服务启动、静态资源、注册和登录后读取验证；现有 108 项后台测试通过。Mac 包仅完成文件、脚本与 Windows 上后端验证，尚未 Mac 实机验收。公开下载不表示全部平台、语音接口均已验证。

开发仓库保持私有。本仓库发布安装包与说明；包内包含运行所需源码及第三方许可。发现问题可提交 Issue，但请先去掉密钥和个人资料。
