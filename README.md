# My Skills

A collection of AI coding skills and utilities for Claude Code, Codex CLI, Cursor, and other AI coding agents.

## Skills

### API Development
- **api-dev** - Scaffold, test, document, and debug REST and GraphQL APIs

### Code
- **code** - Coding workflow with planning, implementation, verification, and testing
- **codeconductor** - Code conductor skills
- **code-docs-search-exa** - Code documentation search
- **coding** - Coding style memory that adapts to your preferences
- **debug-pro** - Expert debugging with deep code execution flow analysis

### Design
- **superdesign** - Expert frontend design guidelines
- **ui-ux-pro-max** - UI/UX design intelligence and implementation guidance
- **ui-ux-pro-max-skill** - Additional UI/UX skills

### Languages & Frameworks
- **python** - Python coding guidelines and best practices
- **qmd** - Local search/indexing CLI (BM25 + vectors + rerank) with MCP mode

### Utilities
- **markdown-formatter** - Format and beautify markdown documents
- **tmux** - Remote-control tmux sessions for interactive CLIs

### Specialized
- **pua** - AI agent role system (P10/P7/P9 flavors)
- **superpowers** - Claude Code skill collection for advanced workflows

## Installation

Installation differs by harness. If you use more than one, install skills separately for each one.

### Claude Code

#### Official Marketplace

Install skills from the official marketplace:

```bash
/plugin install superpowers@claude-plugins-official
/plugin install code@claude-plugins-official
```

#### Manual Installation

Copy the skill folder to your Claude Code skills directory:

```bash
# For macOS/Linux
cp -r <skill-folder> ~/.claude/skills/

# For Windows
xcopy /E /I <skill-folder> %USERPROFILE%\.claude\skills\
```

### Codex CLI

#### Official Marketplace

```bash
/plugins
# Search for the skill name and select Install Plugin
```

#### Manual Installation

Copy the skill folder to your Codex CLI skills directory:

```bash
# ~/.codex/skills/ on macOS/Linux
cp -r <skill-folder> ~/.codex/skills/
```

### Cursor

#### Official Marketplace

Search for skills in Cursor's plugin marketplace.

#### Manual Installation

```bash
# ~/.cursor/rules/ for cursor rules
cp -r <skill-folder> ~/.cursor/rules/
```

### Kiro

#### Manual Installation

```bash
# ~/.kiro/skills/
cp -r <skill-folder> ~/.kiro/skills/
```

### OpenCode

#### Marketplace

```bash
/plugin marketplace add obra/superpowers-marketplace
/plugin install superpowers@superpowers-marketplace
```

#### Manual Installation

```bash
# ~/.opencode/skills/
cp -r <skill-folder> ~/.opencode/skills/
```

### VSCode (GitHub Copilot)

Instructions for each skill vary. Check the individual skill's documentation.

## Directory Structure

```
my-skill/
├── api-dev/           # API development skills
├── code/              # Core coding workflow
├── codeconductor/     # Code conductor
├── code-docs-search-exa/  # Documentation search
├── coding/            # Coding style preferences
├── debug-pro/         # Debugging expertise
├── markdown-formatter/   # Markdown formatting
├── pua/               # AI agent PUA rhetoric
├── python/            # Python guidelines
├── qmd/               # Local search/indexing
├── superdesign/       # Frontend design
├── superpowers/       # Advanced workflows
├── tmux/              # Tmux integration
├── ui-ux-pro-max/     # UI/UX design
└── ui-ux-pro-max-skill/  # Additional UI/UX
```

## Contributing

When contributing skills:
1. Each skill should have its own directory
2. Include a `SKILL.md` file with clear documentation
3. Add `_meta.json` for marketplace compatibility
4. Test the skill with your coding agent before submitting