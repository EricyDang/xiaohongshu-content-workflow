<p align="center">
  <a href="#english">English</a> | <a href="#chinese">中文</a>
</p>

<a id="english"></a>
# Xiaohongshu Content Workflow

A reusable Codex skill for planning, writing, packaging, and QA-ing Xiaohongshu-ready content without relying on private IP, personal character assets, or account-specific unpublished creative work.

## What This Skill Does

This workflow helps create complete Xiaohongshu publishing packages across multiple content formats:

- image-text carousels
- emotional story posts
- two-panel comics or light illustrations
- single posters
- product, venue, or service recommendation posts
- tutorials and checklists
- short video scripts
- comment-driven operation posts
- post-launch reviews and optimization notes

It is designed for creators, operators, content assistants, designers, and AI agents who need a repeatable structure for turning a topic into a publishable Xiaohongshu post.

## Repository Structure

```text
xiaohongshu-content-workflow/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── brand-system.md
    ├── content-types.md
    ├── copywriting.md
    ├── publishing-package.md
    ├── qa-ops.md
    └── visual-prompts.md
```

## Files

### `SKILL.md`

Main Codex skill file. It defines when the skill should trigger and gives the core workflow for creating Xiaohongshu content packages.

### `agents/openai.yaml`

UI-facing metadata for the skill, including display name, short description, and default prompt.

### `references/content-types.md`

Helps choose the right Xiaohongshu workflow based on the goal: growth, saves, conversion, engagement, review, or series building.

### `references/publishing-package.md`

Defines the full publishing package structure, including cover script, page scripts, copy, hashtags, visual spec, image prompts, and QA checklist.

### `references/copywriting.md`

Reusable title patterns, opening hooks, body-copy structures, comment prompts, hashtag patterns, and wording to avoid.

### `references/visual-prompts.md`

Prompt templates for covers, carousel pages, two-panel comics, posters, product posts, venue posts, and short video storyboards.

### `references/brand-system.md`

Guidance for using authorized brand, account, product, or visual identity inputs while avoiding private IP leakage.

### `references/qa-ops.md`

Publishing QA, visual QA, privacy checks, engagement design, and post-launch review framework.

## Example Use Cases

```text
Use this workflow to create a Xiaohongshu carousel about beginner skincare mistakes.
```

```text
Use this workflow to generate a product recommendation post for a study desk lamp.
```

```text
Use this workflow to turn my topic into a full publishing package with title options, page scripts, image prompts, body copy, hashtags, and QA checklist.
```

```text
Use this workflow to write a short video script for Xiaohongshu with hook, scenes, captions, and comment prompt.
```

## Default Output

A full publishing package usually includes:

```text
## Topic
## Target Audience
## Content Goal
## Main Title
## Backup Titles
## Cover Script
## Page Scripts Or Video Script
## Xiaohongshu Body Copy
## Comment Prompt
## Hashtags
## Visual Direction
## Base Image Prompt Template
## Complete Image Prompts
## Pre-publish QA Checklist
## Reusable Content Formula
```

## Privacy And IP Boundary

This skill intentionally does not include any private character, personal IP, unpublished artwork, or account-specific creative asset.

When a visual subject is needed, use placeholders such as:

```text
{visual_subject}
{brand}
{product}
{venue}
{account_persona}
{target_audience}
```

Only use brand assets, character settings, logos, screenshots, names, faces, or private materials when the user explicitly provides them and confirms they may be used.

## Validation

The skill has been validated with Codex skill validation:

```text
Skill is valid!
```

## License

Add a license that matches your publishing intent before distributing this repository broadly.

---

<a id="chinese"></a>
## 中文

这是一个可复用的 Codex 技能，用于规划、撰写、打包和质检小红书内容，避免依赖私有 IP、个人角色资产或账号专属的未公开创作物。

### 这个技能做什么

它可以帮助生成完整的小红书发布包，覆盖：

- 图文轮播
- 情绪故事帖
- 两格漫画或轻插画
- 单图海报
- 产品、探店或服务种草
- 教程和清单
- 短视频脚本
- 评论区运营
- 发布后复盘和优化

### 仓库结构

```text
xiaohongshu-content-workflow/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── brand-system.md
    ├── content-types.md
    ├── copywriting.md
    ├── publishing-package.md
    ├── qa-ops.md
    └── visual-prompts.md
```

### 文件说明

- `SKILL.md`：技能主入口，定义触发场景和核心工作流
- `agents/openai.yaml`：技能列表里显示的名称、简介和默认提示词
- `references/content-types.md`：根据目标选择合适的小红书内容工作流
- `references/publishing-package.md`：完整发布包结构、页脚本、文案、标签和质检
- `references/copywriting.md`：标题、开头、正文、评论引导和标签模板
- `references/visual-prompts.md`：封面、轮播页、海报、短视频分镜等提示词模板
- `references/brand-system.md`：品牌、账号人设、视觉系统和授权边界
- `references/qa-ops.md`：发布前质检、隐私检查、互动设计和复盘框架

### 使用示例

```text
Use this workflow to create a Xiaohongshu carousel about beginner skincare mistakes.
```

```text
Use this workflow to generate a product recommendation post for a study desk lamp.
```

```text
Use this workflow to turn my topic into a full publishing package with title options, page scripts, image prompts, body copy, hashtags, and QA checklist.
```

```text
Use this workflow to write a short video script for Xiaohongshu with hook, scenes, captions, and comment prompt.
```

### 默认输出

完整发布包通常包括：

```text
## 选题
## 目标人群
## 内容目标
## 主标题
## 备选标题
## 首页图脚本
## 分页脚本或视频脚本
## 小红书正文
## 评论区引导
## 话题标签
## 视觉方向
## 基础图片提示词模板
## 完整图片提示词
## 发布前质检清单
## 可复用内容公式
```

### 隐私与 IP 边界

这个技能不会默认包含任何私有角色、个人 IP、未公开作品或账号专属创意资产。

需要视觉主体时，建议使用：

```text
{visual_subject}
{brand}
{product}
{venue}
{account_persona}
{target_audience}
```

只有在用户明确提供并确认可用时，才使用品牌素材、角色设定、logo、截图、姓名、头像或其他私有资料。

### 验证

该技能已通过 Codex 技能验证：

```text
Skill is valid!
```

### 许可

在广泛分发仓库之前，请添加与你的发布意图一致的许可协议。
