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
