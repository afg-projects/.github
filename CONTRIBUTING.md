# 贡献指南

感谢你关注 AFG Projects！

## 🚀 开始之前

建议你先做这几件事：

1. 阅读目标仓库的 `README.md`
2. 搜索现有 Issues，避免重复提问或提案
3. 如果是架构级改动，优先先讨论、后实现

## 📋 推荐贡献流程

### 1. Fork 或创建分支

```bash
# Fork 仓库后克隆
git clone https://github.com/<your-username>/<repo>.git

# 或在有权限时创建功能分支
git checkout -b feature/your-feature-name
```

### 2. 编写代码

- 用尽量聚焦的改动解决一个明确问题
- 遵循项目代码规范（PMD 检查）
- 添加必要的测试

### 3. 提交 PR

- 写清改动范围和原因
- 说明验证方式
- 关联相关 Issue

## ✅ 我们希望看到的 PR 特征

| 特征 | 说明 |
|------|------|
| 范围清晰 | 一个 PR 解决一个问题 |
| 提交信息规范 | 使用 Conventional Commits 格式 |
| 测试覆盖 | 行为变化时补测试 |
| 文档同步 | 接口变化时补文档 |

## 🎯 提交信息格式

使用 Conventional Commits 格式：

```
<type>(<scope>): <subject>

<body>

<footer>
```

常用类型：
- `feat`: 新功能
- `fix`: Bug 修复
- `docs`: 文档更新
- `refactor`: 重构
- `test`: 测试相关
- `chore`: 构建/工具相关

## 🏗️ 架构级改动

以下改动建议先开 Issue 或 Discussion 讨论：

1. API / SPI 变化
2. 模块依赖关系变化
3. 核心组件重构
4. 安全相关改动

## 💬 需要帮助时

- 使用 GitHub Discussions 提问
- 确认是缺陷时开 Bug Report Issue
- 功能建议开 Feature Request Issue