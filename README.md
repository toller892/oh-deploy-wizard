# oh-deploy-wizard

[English](#english) | [中文](#中文)

---

## English

### One-Click Deployment Assistant for OpenClaw

Simplify OpenClaw deployment with guided setup, automatic configuration, and health monitoring.

#### Features

- 🚀 **One-Click Deploy**: Automated installation and configuration
- 🔧 **Smart Configuration**: Interactive setup wizard with validation
- 📊 **Health Monitoring**: Real-time status checks and alerts
- 🐳 **Docker Support**: Containerized deployment option
- 🔄 **Auto Updates**: Keep OpenClaw up-to-date automatically
- 🛡️ **Security Hardening**: Apply best practices automatically

#### Quick Start

1. **Clone this repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/oh-deploy-wizard.git
   cd oh-deploy-wizard
   ```

2. **Run the wizard**
   ```bash
   node index.js deploy
   ```

3. **Follow the prompts**
   - Choose deployment type (local/docker/cloud)
   - Configure channels (Telegram/WhatsApp/Discord)
   - Set up models and providers
   - Review and confirm

#### Usage Examples

**Deploy OpenClaw:**
```bash
node index.js deploy
```

**Check health:**
```bash
node index.js health
```

**Update OpenClaw:**
```bash
node index.js update
```

**Backup configuration:**
```bash
node index.js backup
```

#### Deployment Types

- **Local**: Direct installation on your machine
- **Docker**: Containerized deployment with docker-compose
- **Cloud**: Deploy to VPS (DigitalOcean, AWS, etc.)

#### Configuration Wizard

The wizard guides you through:
1. System requirements check
2. OpenClaw installation
3. Channel configuration
4. Model provider setup
5. Security settings
6. First run verification

#### Health Checks

Monitors:
- Gateway status
- Node connectivity
- Channel connections
- Model availability
- Resource usage
- Error rates

#### Requirements

- Node.js >= 18
- npm >= 9
- Docker (optional)
- 2GB RAM minimum

#### License

MIT

---

## 中文

### OpenClaw 一键部署助手

通过引导式设置、自动配置和健康监控简化 OpenClaw 部署。

#### 功能特性

- 🚀 **一键部署**：自动化安装和配置
- 🔧 **智能配置**：交互式设置向导，带验证
- 📊 **健康监控**：实时状态检查和告警
- 🐳 **Docker 支持**：容器化部署选项
- 🔄 **自动更新**：保持 OpenClaw 最新版本
- 🛡️ **安全加固**：自动应用最佳实践

#### 快速开始

1. **克隆仓库**
   ```bash
   git clone https://github.com/YOUR_USERNAME/oh-deploy-wizard.git
   cd oh-deploy-wizard
   ```

2. **运行向导**
   ```bash
   node index.js deploy
   ```

3. **按提示操作**
   - 选择部署类型（本地/Docker/云端）
   - 配置通道（Telegram/WhatsApp/Discord）
   - 设置模型和提供商
   - 审查并确认

#### 使用示例

**部署 OpenClaw：**
```bash
node index.js deploy
```

**检查健康状态：**
```bash
node index.js health
```

**更新 OpenClaw：**
```bash
node index.js update
```

**备份配置：**
```bash
node index.js backup
```

#### 部署类型

- **本地**：直接安装在你的机器上
- **Docker**：使用 docker-compose 容器化部署
- **云端**：部署到 VPS（DigitalOcean、AWS 等）

#### 配置向导

向导会引导你完成：
1. 系统要求检查
2. OpenClaw 安装
3. 通道配置
4. 模型提供商设置
5. 安全设置
6. 首次运行验证

#### 健康检查

监控项目：
- Gateway 状态
- Node 连接性
- 通道连接
- 模型可用性
- 资源使用
- 错误率

#### 依赖要求

- Node.js >= 18
- npm >= 9
- Docker（可选）
- 最少 2GB 内存

#### 许可证

MIT
