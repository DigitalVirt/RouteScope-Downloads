<p align="center"><a href="https://digitalvirt.com"><picture><source media="(prefers-color-scheme: dark)" srcset="docs/branding/digitalvirt-dark.svg"><img src="docs/branding/digitalvirt-light.svg" alt="DigitalVirt" width="267" height="50"></picture></a></p>
<h1 align="center">RouteScope Downloads</h1>
<p align="center">RouteScope 是 <a href="https://digitalvirt.com">DigitalVirt</a> 旗下的网络路径追踪工具。</p>

本仓库只分发官方构建产物与校验信息，不包含应用源码。

**[下载最新版本 / Latest Release](https://github.com/DigitalVirt/RouteScope-Downloads/releases/latest)** · **[DigitalVirt 官网](https://digitalvirt.com)**

| 平台 | 下载文件 | 说明 |
| --- | --- | --- |
| macOS | `.dmg` | Apple 芯片；系统要求见 Release |
| Windows x64 | `Setup-x64.exe` / `win-x64-portable.zip` | 安装版 / 免安装便携版；Intel、AMD 电脑 |
| Windows ARM64 | `Setup-arm64.exe` / `win-arm64-portable.zip` | 安装版 / 免安装便携版；Windows on ARM |
| Android | `.apk` | 当前为开发调试包 |
| HarmonyOS NEXT | `.hap` | 当前为未签名开发测试包，需签名或通过开发工具部署 |

各平台可能使用不同版本号，以 Release 文件名和 `release-manifest.json` 为准。便携版解压运行 `RouteScope.exe`，包含 .NET 运行时，地图需要 WebView2。Windows 当前为未签名开发版。

下载后可使用 `SHA256SUMS.txt` 或 Release 附带的 MD5 信息核对文件完整性。GitHub 下载与官网现有光鸭网盘并行提供。
