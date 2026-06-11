# MCP & OpenClaw DevStudio

一站式 MCP 协议与 OpenClaw 智能体低代码开发平台，降低 AI 应用开发门槛。

## 核心功能

### 1. MCP Server Builder
- 可视化配置 MCP Server
- 30+ 预置模板（MySQL、PostgreSQL、Redis、GitHub、Notion 等）
- 一键生成 Python/TypeScript 代码
- Hot-Reload 热更新

### 2. OpenClaw Skill Workshop
- 拖拽式技能编排（类似 Node-RED）
- 自动生成 SKILL.md + Python 异步函数
- 隔离测试沙箱
- 版本管理与回滚

### 3. Debug & Monitor
- 实时通信日志
- 调用链路追踪
- 性能指标分析
- 成本统计与优化建议

## 快速开始

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建生产版本
npm run build
```

## 技术栈

- **前端**: React + TypeScript + TailwindCSS + shadcn/ui
- **后端**: Node.js + Express
- **MCP SDK**: @modelcontextprotocol/sdk
- **流程图**: React Flow
- **部署**: Docker Compose / Kubernetes

## 项目结构

```
mcp-openclaw-devstudio/
├── packages/
│   ├── mcp-server-builder/      # MCP Server 可视化工具
│   ├── skill-workshop/          # Skill 低代码开发平台
│   ├── debug-monitor/           # 调试监控平台
│   └── core-engine/             # 核心引擎
├── apps/
│   ├── web/                     # 主应用
│   └── cli/                     # 命令行工具
└── docs/                        # 文档
```

## 适用场景

- 腾讯 AI 应用开发岗位 - 加速 MCP 协议集成
- OpenClaw 智能体开发 - 降低 Skill 开发门槛
- 企业私有化部署 - 内置安全沙箱与权限控制
- AI 教学与培训 - 可视化学习 MCP 协议

## License

MIT
