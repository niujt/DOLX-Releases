# DOLX Releases

DOLX 是 Windows 和 macOS 数据库开发工具，支持 Oracle、OceanBase、MySQL 和 Redis。本仓库提供正式安装包和版本说明。

## 下载

[下载最新版本](https://github.com/niujt/DOLX-Releases/releases/latest)

- Windows：选择 `DOLX-Setup-<版本>-Windows-x64.exe`，运行安装程序。
- macOS Apple 芯片：选择 `DOLX-<版本>-macOS-arm64.dmg`，打开后将 DOLX 拖入“应用程序”。
- 安装包内置 Core 与平台 JRE，无需另外安装 Java。
- `SHA256SUMS-<版本>.txt` 提供文件的 SHA-256 校验值。

## 升级

升级前保存 SQL、处理未提交事务并退出 DOLX，然后安装新版本。

安装 0.2.2 或更高版本后，软件会在启动后自动检查更新，并每 6 小时复查一次。发现新版本时显示提醒和对应平台的安装包下载入口；也可通过“设置 → 软件更新”或帮助菜单手动检查。安装由用户完成。
