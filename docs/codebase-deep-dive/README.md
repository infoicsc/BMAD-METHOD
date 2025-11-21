# BMAD-METHOD 代码库深度解析文档

> 完整的技术文档系列，帮助你深入理解并定制 BMAD-METHOD 框架

## 📚 文档清单

### 核心文档（已完成）

1. **[00 - 索引导航](./00-索引导航.md)** - 文档总索引和阅读指南
2. **[01 - 项目架构总览](./01-项目架构总览.md)** - 整体架构、技术栈、设计理念
3. **[03 - 代理系统深度解析](./03-代理系统深度解析.md)** - Agent 完整规范和实现细节
4. **[09 - 定制化开发完全指南](./09-定制化开发完全指南.md)** - 创建自定义组件的实战指南
5. **[10 - 企业内部定制方案](./10-企业内部定制方案.md)** - 企业级改造和部署方案

## 🚀 快速开始

### 新手路径
```
00 索引导航 → 01 项目架构总览 → 03 代理系统深度解析
```

### 定制开发路径
```
01 项目架构总览 → 09 定制化开发指南 → 10 企业内部定制方案
```

### 深度研究路径
阅读所有文档，从架构到实现细节全面理解。

## 📖 文档特点

- ✅ **详细**: 每个文档 30-120 分钟阅读时间
- ✅ **实战**: 包含大量代码示例和真实案例
- ✅ **深入**: 从设计理念到实现细节
- ✅ **可操作**: 提供具体的定制化指导

## 🎯 文档目标

通过这些文档，你将能够：

1. **完全理解** BMAD-METHOD 的架构和设计
2. **深入掌握** Agent、Workflow、Task 三大核心系统
3. **熟练定制** 创建自己的 Agent、Workflow 和 Module
4. **企业改造** 将框架定制为公司内部专用工具

## 📊 项目核心指标

| 指标 | 数值 |
|------|------|
| 源代码规模 | 3.6MB |
| Agent 数量 | 19 个 |
| Workflow 数量 | 63+ |
| 支持 IDE | 15 个 |
| 模块数量 | 5 个 |

## 🔑 核心概念速查

- **Agent**: 代表特定专业角色的 AI 助手
- **Workflow**: 结构化的多步骤流程
- **Task**: 可重用的流程控制逻辑（XML）
- **Module**: Agent、Workflow、Task 的集合
- **Track**: 不同规模项目的执行路径（Quick/BMad/Enterprise）

## 🛠️ 关键文件路径

```
src/core/                          # 核心框架
├── agents/bmad-master.agent.yaml  # 主协调器
├── tasks/workflow.xml             # 工作流引擎
└── _module-installer/             # 安装系统

src/modules/bmm/                   # BMad Method 主模块
├── agents/                        # 8 个 Agent
└── workflows/                     # 30+ 工作流

tools/cli/                         # CLI 工具
├── bmad-cli.js                    # CLI 入口
├── commands/                      # 命令实现
└── lib/yaml-xml-builder.js        # 编译器
```

## 💡 快速参考

### 创建自定义 Agent
```bash
/bmad:bmb:agents:bmad-builder
*create-agent
```

### 创建自定义 Workflow
```bash
/bmad:bmb:agents:bmad-builder
*create-workflow
```

### 验证和构建
```bash
npm run validate:schemas
npm run build
```

### 安装到项目
```bash
npx bmad-method@alpha install
```

## 🌟 推荐使用场景

### 适合
- ✅ 需要深度理解框架的架构师
- ✅ 计划定制化的企业团队
- ✅ 想要贡献代码的开发者
- ✅ 研究 AI Agent 系统的学习者

### 不适合
- ❌ 只想快速使用的用户（请看官方文档）
- ❌ 不需要定制的团队

## 📞 获取帮助

- 📖 查看官方文档: [README.md](../../README.md)
- 💬 社区讨论
- 🐛 提交 Issue
- 🤝 贡献代码

## 📅 文档版本

- **版本**: 1.0.0
- **基于项目版本**: v6.0.0-alpha.7
- **生成日期**: 2025-11-21
- **维护者**: BMAD Community

## 🙏 致谢

感谢 BMAD-METHOD 项目提供了如此优秀的框架设计。本文档旨在帮助更多开发者理解和使用这个强大的工具。

---

**开始你的深度学习之旅** ➡️ [00 - 索引导航](./00-索引导航.md)
