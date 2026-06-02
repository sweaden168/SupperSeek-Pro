# SupperSeek Pro

**毫秒级全盘文件搜索引擎 — Windows 高性能桌面搜索工具**

基于 Rust 内核 + Tauri 桌面框架 + React 前端构建，通过直接解析 NTFS MFT 记录实现超越系统原生的毫秒级文件检索体验。

---

## 核心功能

- ⚡ **毫秒级全盘搜索** — 直接解析 NTFS MFT，不依赖系统索引，1 秒内返回百万级结果
- 👁️ **100+ 格式预览** — 图片、文档(PDF/Word/Excel/PPT)、视频、PSD、AI 等，无需安装第三方软件
- 🏷️ **文件标签管理** — 自定义标签，快速分类与筛选
- ⭐ **收藏与工作区** — 自建收藏夹、项目管理，高效组织文件
- 🔒 **文件保险柜** — AES-256 加密存储敏感文件
- 📦 **文件归档** — 一键归档压缩，节省磁盘空间
- 🔄 **USN Journal 实时同步** — 文件增删改自动感知，索引始终最新
- 🎨 **主题系统** — 多款主色调 + 明暗模式，自由切换
- 🔔 **消息中心** — 官方公告、版本更新实时通知

---

## 下载

| 版本 | 说明 | 下载 |
|------|------|------|
| **安装版** | 通过 Setup 安装到系统 | [下载](https://github.com/sweaden168/SupperSeek-Pro/releases/latest) |
| **便携版** | 解压即用，不留系统痕迹 | [下载](https://github.com/sweaden168/SupperSeek-Pro/releases/latest) |

---

## 系统要求

- Windows 10 / 11 (64-bit)
- 不需要管理员权限（便携版）
- 推荐 8GB+ 内存

---

## 技术栈

| 层级 | 技术 |
|------|------|
| 搜索内核 | Rust — 直接解析 NTFS MFT 主文件表 |
| 桌面框架 | Tauri 2.x — 轻量级跨平台桌面框架 |
| 前端 | React + TypeScript + Tailwind CSS |
| 动效 | Framer Motion |

---

## 网站

https://supperseek.sweaden.com

---

© 2026 SupperSeek. All rights reserved.
