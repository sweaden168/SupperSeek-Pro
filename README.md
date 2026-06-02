# SupperSeek Pro

极致性能的本地文件搜索与管理工具。

## 1. 项目简介

SupperSeek Pro 是一款专为 Windows 设计的本地文件搜索与管理工具。它结合了 **Everything** 的毫秒级搜索性能和 **ACDSee** 的专业级文件预览体验，同时内置“数字保险库”功能，确保本地数据的绝对私密与安全。

## 2. 核心功能

- **毫秒级搜索**: 直接解析 NTFS MFT，实现瞬时全盘索引。
- **专业级预览**: 选中文件按 `空格键` 即可快速预览图片、视频、PDF 及各类文档。
- **数字保险库**: AES-256 加密存储，保护您的私密文件。
- **高级过滤**: 支持按类型、大小、日期、扩展名等多种维度组合查询。
- **AI 助手**: 内置 AI 助手，协助您管理文件与确认需求。

## 3. 安装指南

### 前置要求

- Node.js (v18+)
- npm 或 yarn

### 安装步骤

1. 克隆仓库：
   ```bash
   git clone <repository-url>
   cd supperseek-pro
   ```

2. 安装依赖：
   ```bash
   npm install
   ```

3. 配置环境变量：
   复制 `.env.example` 为 `.env`，如需本地邮件验证码服务，请填写对应的邮箱服务配置。

## 4. 使用说明

### 开发环境运行

```bash
npm run dev
```
启动后访问 `http://localhost:32173`。

### 生产环境构建

```bash
npm run build
npm start
```

### 快捷键

- `空格键`: 快速预览选中文件。
- `Esc`: 关闭预览窗口或弹出层。
- `上下方向键`: 在文件列表中导航。
- `双击`: 打开文件或所在目录。

## 5. 项目结构

- `/src`: 前端源代码 (React + Tailwind CSS)。
- `/server.ts`: 后端 Express 服务器，集成 Vite 中间件。
- `/PRD.md`: 产品需求文档与更新日志。
- `/scripts`: 项目启动与构建脚本。

## 6. 技术栈

- **Frontend**: React 19, Tailwind CSS, Framer Motion, Lucide Icons.
- **Backend**: Express, Node.js (模拟 Rust/Tauri 逻辑)。
- **Tooling**: Vite, TypeScript.

---
© 2026 SupperSeek Pro Team. 保留所有权利。
