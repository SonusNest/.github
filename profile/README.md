<p align="center">
  <a href="https://github.com/SonusTeam/Sonus">
    <img src="https://file.lingke.ink/sonus/sonus-en.webp" alt="Sonus Logo">
  </a>
</p>

<h1 align="center">Sonus Nest</h1>

<p align="center">
  <a href="https://github.com/SonusTeam/Sonus/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/SonusTeam/Sonus/build.yml?style=flat-square" alt="Build Status">
  </a>
  <a href="https://github.com/SonusTeam/Sonus/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/SonusTeam/Sonus?style=flat-square" alt="License">
  </a>
  <a href="https://github.com/SonusTeam/Sonus/releases">
    <img src="https://img.shields.io/github/v/release/SonusTeam/Sonus?include_prereleases&style=flat-square" alt="Latest Release">
  </a>
  <a href="https://github.com/SonusTeam/Sonus/stargazers">
    <img src="https://img.shields.io/github/stars/SonusTeam/Sonus?style=flat-square" alt="Stars">
  </a>
  <a href="https://github.com/SonusTeam/Sonus/issues">
    <img src="https://img.shields.io/github/issues/SonusTeam/Sonus?style=flat-square" alt="Issues">
  </a>
  <a href="https://discord.gg/Udq8xrruA3">
    <img src="https://img.shields.io/discord/yourserverid?style=flat-square&label=Discord" alt="Discord">
  </a>
</p>

Sonus is an open-source, lightweight cross-platform desktop application developed with Tauri + Rust. As a private music library management player, it not only manages music stored locally on the running device but also enables localized management of music in home private clouds (NAS) or remote servers via WebDAV and SMB protocols.

Sonus 是一款基于 Tauri + Rust 开发的开源、轻量型跨平台桌面应用。作为私人音乐库管理播放器，它不仅能管理运行设备本地存储的音乐，还可通过 WebDAV、SMB 协议，对家庭私有云（NAS）或远程服务器中的音乐进行本地化管理。


## ✨ Features
### ✨ 功能特性

- **Local & Network Music Management**
  - Organize and play music from local storage
  - Connect to WebDAV and SMB servers for remote music management
  - Automatic metadata extraction and organization

- **本地与网络音乐管理**
  - 整理并播放本地存储中的音乐
  - 连接 WebDAV、SMB 服务器，实现远程音乐管理
  - 自动提取并整理音乐元数据


- **Powerful Playback**
  - Support for common audio formats (MP3, FLAC, WAV, etc.)
  - Multiple playback modes (repeat, shuffle, etc.)
  - High-quality audio output

- **强大的播放功能**
  - 支持常见音频格式（MP3、FLAC、WAV 等）
  - 提供多种播放模式（循环、随机等）
  - 高品质音频输出


- **Modern UI**
  - Clean and intuitive interface
  - Light/dark mode support
  - Customizable themes
  - Responsive design for different window sizes

- **现代化界面**
  - 简洁直观的操作界面
  - 支持亮色/暗色模式切换
  - 可自定义主题样式
  - 适配不同窗口尺寸的响应式设计


- **Advanced Library Features**
  - Search and filter by artist, album, genre, etc.
  - Create and manage playlists
  - Album art display and organization

- **进阶的库管理功能**
  - 按艺术家、专辑、流派等维度搜索筛选
  - 创建并管理播放列表
  - 专辑封面展示与整理


## 📥 Installation
### 📥 安装方式

### Windows
- Download the latest installer from the [releases page](https://github.com/SonusTeam/Sonus/releases)
- Run the installer and follow the on-screen instructions

### Windows 系统
- 从 [发布页面](https://github.com/SonusTeam/Sonus/releases) 下载最新安装包
- 运行安装程序并跟随屏幕提示完成安装


### macOS
- Support will be added in version 1.0 stable release

### macOS 系统
- 1.0 正式版将新增对该系统的支持


### Linux
- Support will be added in version 1.0 stable release

### Linux 系统
- 1.0 正式版将新增对该系统的支持


## 🚀 Getting Started
### 🚀 快速开始

1. Launch Sonus after installation
2. Add your music library:
  - Click on "Settings" > "Library"
  - Add local folders or connect to WebDAV/SMB servers
3. Let Sonus scan and index your music collection
4. Browse your library, create playlists, and enjoy your music

1. 安装完成后启动 Sonus
2. 添加音乐库：
  - 点击「设置」>「音乐库」
  - 添加本地文件夹，或连接 WebDAV/SMB 服务器
3. 等待 Sonus 扫描并索引你的音乐集
4. 浏览音乐库、创建播放列表，开始享受音乐


## 🔧 Development
### 🔧 开发指南

### Prerequisites
- [Rust](https://www.rust-lang.org/tools/install)
- [Node.js](https://nodejs.org/)
- [Tauri CLI](https://tauri.app/v2/guides/getting-started/prerequisites/)

### 前置依赖
- [Rust](https://www.rust-lang.org/tools/install)
- [Node.js](https://nodejs.org/)
- [Tauri CLI](https://tauri.app/v2/guides/getting-started/prerequisites/)（Tauri 命令行工具）


### Setup
```bash
# Clone the repository
git clone https://github.com/SonusTeam/Sonus.git
cd Sonus

# Install dependencies
pnpm install

# Start development server
pnpm tauri dev
```

### 环境搭建
```bash
# 克隆仓库
git clone https://github.com/SonusTeam/Sonus.git
cd Sonus

# 安装依赖
pnpm install

# 启动开发服务器
pnpm tauri dev
```


### Building
```bash
# Build for production
pnpm tauri build
```

### 构建打包
```bash
# 构建生产环境包
pnpm tauri build
```


## 📋 Roadmap
The project is currently in the initial development phase. Key upcoming features include:
- Complete WebDAV and SMB support
- Advanced audio quality settings
- Shortcut key configuration
- Enhanced theme customization
- Cross-platform support for macOS and Linux
- Additional metadata management tools

For a detailed list of current development tasks, see our TODO list.

### 📋 开发路线图
目前项目处于初期开发阶段，重点规划功能包括：
- 完善 WebDAV 与 SMB 协议支持
- 进阶音频质量设置
- 快捷键自定义配置
- 增强主题定制功能
- 完善 macOS、Linux 跨平台支持
- 新增音乐元数据管理工具

当前开发任务详情可查看项目 TODO 列表。


## 🤝 Contributing
Contributions are welcome! Please read our [Contributing Guide](https://github.com/SonusTeam/Sonus/CONTRIBUTING.md) before submitting a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### 🤝 参与贡献
欢迎所有形式的贡献！提交 Pull Request 前，请先阅读 [贡献指南](https://github.com/SonusTeam/Sonus/CONTRIBUTING.md)。

1. Fork 本项目
2. 创建功能分支（`git checkout -b feature/AmazingFeature`）
3. 提交修改（`git commit -m 'Add some AmazingFeature'`）
4. 推送到分支（`git push origin feature/AmazingFeature`）
5. 打开 Pull Request


## 🐛 Issues
If you encounter any issues, please report them on our [issue tracker](https://github.com/SonusTeam/Sonus/issues).

### 🐛 问题反馈
如遇到任何问题，欢迎在 [问题跟踪器](https://github.com/SonusTeam/Sonus/issues) 中提交反馈。


## 📄 License
Sonus is licensed under the [GNU General Public License v3.0](https://github.com/SonusTeam/Sonus/LICENSE).

### 📄 许可证
Sonus 基于 [GNU 通用公共许可证 v3.0](https://github.com/SonusTeam/Sonus/LICENSE) 开源。


## 💬 Community
- Discord - Join our community chat
- QQ Group - 755353142

### 💬 社区交流
- Discord - 加入社区聊天群（链接：https://discord.gg/Udq8xrruA3）
- QQ 群 - 755353142


## 🙏 Acknowledgements
Sonus thanks JetBrains RustRover IDE for supporting open source projects

### 🙏 致谢
感谢 JetBrains 提供 RustRover IDE 对开源项目的支持


<p align="center">
Made with ❤️ by the Sonus Nest Team and Contributors.
</p>

<p align="center">
由 Sonus Nest 团队及所有贡献者共同打造 ❤️
</p>
