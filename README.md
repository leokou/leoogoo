# Leoogoo · 分发仓库（Release 二进制）

本仓库是 **Leoogoo 桌面应用**的**二进制分发仓库**（只放安装包与校验信息，**不含源码**）。

- **闭源软件**：本仓库不公开源码；`LICENSE`（MIT）仅约束本仓库内文件的再分发，不要求开放源码。
- **用途**：为 Leoogoo 客户端「自动更新」提供海外下载主源（GitHub Releases，免费无限流量）。
- **版本元数据**：客户端版本检查走官方接口 `GET https://leoogoo-pc.toupiaoya.top/api/update`；本仓库的 Release 资产作为海外直链被 `recommended_url` 引用。

## 下载

| 版本 | 安装包 | SHA256 | 发布说明 |
| --- | --- | --- | --- |
| 最新版 | [Leoogoo_Setup.exe（latest 直链）](https://github.com/leokou/leoogoo/releases/latest/download/Leoogoo_Setup.exe) | 见对应 Release | 见对应 Release |

安装包体积约 27MB（NSIS onedir 静默安装：`/S` 静默、`/S /runAfter` 静默安装后自动启动）。

## 国内用户

国内直连 GitHub 不稳定，Leoogoo 客户端会自动优先走国内镜像（cnb）与 R2 兜底，无需手动切换。

## 版权

© 2026 leokou · MIT License（仅限本仓库二进制文件）
