<div align="center">
  <img src="https://lsky.saklit.com/i/2026/06/23/6a39f03ae0d66.png" alt="SakBot" width="120" />
  <h1 align="center">SakBot</h1>
  <p align="center">
    基于 .NET 10 构建的 QQ 机器人 Web 管理面板
    <br />
    适配 OneBot 11 标准协议 · 提供多用户一站式管理体验
  </p>
  <p>
    <a href="https://qm.qq.com/q/GCbHaNoOYy"><img src="https://img.shields.io/badge/QQ群-点击加入-1976D2?style=flat-square&logo=tencentqq" alt="QQ群" /></a>
    <a href="https://alist.saklit.com/SakBot"><img src="https://img.shields.io/badge/下载-最新版本-4CAF50?style=flat-square" alt="下载" /></a>
    <a href="https://sakbot.saklit.com/"><img src="https://img.shields.io/badge/文档-在线查看-FF4081?style=flat-square" alt="文档" /></a>
    <img src="https://img.shields.io/badge/.NET-10.0-512BD4?style=flat-square&logo=dotnet" alt=".NET" />
    <img src="https://img.shields.io/badge/OneBot-11-FF6F00?style=flat-square" alt="OneBot" />
  </p>
</div>

---

## 📖 这是什么？

SakBot 是一款基于 .NET 10 构建的 QQ 机器人 Web 管理面板，适配 OneBot 11 标准协议，提供多用户一站式管理体验。

## ✨ 功能特性

| 功能 | 说明 |
|------|------|
| 🎮 **Minecraft 玩家管理** | 玩家 CRUD，封禁/解封，密码管理，白名单配置，QQ 与 Minecraft 账号绑定 |
| 💬 **跨服聊天与 TAB** | QQ 群与 Minecraft 服务器双向消息互通，多服务器 TAB 列表同步，支持多群多服分组 |
| 👤 **用户系统** | 签到系统，货币金币系统，称号头衔系统，自定义 QQ 群命令 |
| 📋 **机器人白名单** | QQ 群/用户白名单管理，控制机器人使用权限，支持群号与 QQ 号精确匹配 |
| 📊 **仪表盘** | 实时监控面板，展示机器人运行状态、在线玩家数、服务器连接状态等核心数据 |
| 🔄 **自动更新** | SakBot 自动检测新版本并一键更新，无需手动下载替换文件 |

## 🖥 环境要求

| 平台 | 要求 |
|------|------|
| **Windows** | 开箱即用，无额外环境依赖 |
| **Linux** | 需要安装 Chrome 浏览器环境 |

## 📥 下载

通过 [下载列表](https://alist.saklit.com/SakBot) 获取对应版本。

若下载速度缓慢，可添加 [QQ交流群](https://qm.qq.com/q/GCbHaNoOYy) 获取。

### Windows

| 版本 | 说明 |
|------|------|
| `SakBot_Windows_版本号.zip` | 精简版 |
| `SakBot_Windows_Complete_版本号.zip` | 完整版（含 Chrome） |

### Linux

| 版本 | 说明 |
|------|------|
| `SakBot_Linux_版本号.tar.gz` | 精简版 |
| `SakBot_Linux_Complete_版本号.tar.gz` | 完整版（含 Chrome） |

---

## 🚀 Windows 快速部署

### 1. 下载并解压

下载对应版本后，将压缩包解压到任意目录（建议路径不含中文和空格）。

### 2. 启动 SakBot

双击 `SakBot.exe` 即可启动，首次启动会自动创建 `Data/` 目录并生成数据库文件。

### 3. 访问管理面板

启动成功后，浏览器访问 **http://localhost:5100** 进入 Web 管理面板。

### 4. 常见问题

> **端口被占用：** 如果 5100 端口被占用，可修改 `appsettings.json` 中的 `Listen.Port` 配置项。

---

## 🐧 Linux 快速部署

### 1. 安装 Chrome 环境

```bash
# Debian / Ubuntu
wget -q -O - https://dl.google.com/linux/linux_signing_key.pub | apt-key add -
echo "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main" > /etc/apt/sources.list.d/google-chrome.list
apt update && apt install -y google-chrome-stable

# CentOS / RHEL
yum install -y google-chrome-stable
```

### 2. 下载并解压

```bash
tar -xzf SakBot_Linux_对应版本号.tar.gz -C /opt/SakBot
cd /opt/SakBot
```

### 3. 赋予执行权限

```bash
chmod +x SakBot
```

### 4. 启动 SakBot

```bash
./SakBot
```

首次启动会自动创建 `Data/` 目录并生成数据库文件。

### 5. 访问管理面板

启动成功后，浏览器访问 **http://<服务器IP>:5100** 进入 Web 管理面板。

---

<div align="center">
  <a href="https://qm.qq.com/q/GCbHaNoOYy">QQ交流群</a>
  ·
  <a href="https://alist.saklit.com/SakBot">下载页面</a>
  <br />
  <sub>Copyright © 2025 SakBot</sub>
</div>
