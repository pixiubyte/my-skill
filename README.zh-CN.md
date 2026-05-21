# My Skills

[English Version](./README.md)

面向 Claude Code、Codex CLI、Cursor 等 AI 编程助手的技能集合。

## 技能列表

### API 开发
- **api-dev** - REST 和 GraphQL API 的快速构建、测试、文档编写与调试

### 代码
- **code** - 包含规划、实现、验证、测试的编码工作流
- **codeconductor** - 代码指挥技能
- **code-docs-search-exa** - 代码文档搜索
- **coding** - 适应你偏好的编码风格记忆
- **debug-pro** - 深度代码执行流分析与专业调试

### 设计
- **superdesign** - 前端设计指南
- **ui-ux-pro-max** - UI/UX 设计智能与实现指导
- **ui-ux-pro-max-skill** - 额外的 UI/UX 技能

### 语言和框架
- **python** - Python 编码规范与最佳实践
- **qmd** - 本地搜索/索引 CLI（BM25 + 向量 + 重排），支持 MCP 模式

### 工具
- **markdown-formatter** - Markdown 文档格式化与美化
- **tmux** - 远程控制 tmux 会话

### 专精
- **pua** - AI 代理角色系统（P10/P7/P9 风格）
- **superpowers** - Claude Code 高级工作流技能集

## 安装

不同工具的安装方式不同。如需在多个工具中使用，请分别安装。

### Claude Code

#### 官方市场

```bash
/plugin install superpowers@claude-plugins-official
/plugin install code@claude-plugins-official
```

#### 手动安装

```bash
# macOS / Linux
cp -r <技能文件夹> ~/.claude/skills/

# Windows
xcopy /E /I <技能文件夹> %USERPROFILE%\.claude\skills\
```

### Codex CLI

#### 官方市场

```bash
/plugins
# 搜索技能名称，选择 Install Plugin
```

#### 手动安装

```bash
# macOS / Linux
cp -r <技能文件夹> ~/.codex/skills/
```

### Cursor

#### 官方市场

在 Cursor 插件市场中搜索。

#### 手动安装

```bash
# ~/.cursor/rules/
cp -r <技能文件夹> ~/.cursor/rules/
```

### Kiro

```bash
# ~/.kiro/skills/
cp -r <技能文件夹> ~/.kiro/skills/
```

### OpenCode

#### 市场安装

```bash
/plugin marketplace add obra/superpowers-marketplace
/plugin install superpowers@superpowers-marketplace
```

#### 手动安装

```bash
# ~/.opencode/skills/
cp -r <技能文件夹> ~/.opencode/skills/
```

### VSCode (GitHub Copilot)

各技能安装方式不同，请查看对应技能文档。

## 目录结构

```
my-skill/
├── api-dev/           # API 开发技能
├── code/              # 核心编码工作流
├── codeconductor/     # 代码指挥
├── code-docs-search-exa/  # 文档搜索
├── coding/            # 编码风格偏好
├── debug-pro/         # 调试专家
├── markdown-formatter/   # Markdown 格式化
├── pua/               # AI 代理 PUA 话术
├── python/            # Python 规范
├── qmd/               # 本地搜索
├── superdesign/       # 前端设计
├── superpowers/       # 高级工作流
├── tmux/              # Tmux 集成
├── ui-ux-pro-max/     # UI/UX 设计
└── ui-ux-pro-max-skill/  # 额外 UI/UX
```

## 贡献

贡献技能时请确保：
1. 每个技能有独立目录
2. 包含清晰的 `SKILL.md` 文档
3. 添加 `_meta.json` 以兼容市场
4. 在编码助手中测试后再提交