# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

A static HTML portfolio of vibe-coded web pages. No build system, bundler, or runtime dependencies — just open HTML files directly in a browser. GitHub Pages deploys from the `main` branch.

## Adding a New Page

When adding a new HTML file to the portfolio, update **all** of the following:

1. **Rename** the file to a short, meaningful English name (e.g., `modeltea.html`, `recruitment-timeline-2026.html`).
2. **`README.md`** — add a new row to the 作品 table with: page link, description, and model name.
3. **`index.html`** — add a new card entry in the card grid, matching the existing Comic Style layout and interactions. Use `target="_blank"` on all card links.

## File Naming Rules

- Use short, meaningful English names in kebab-case.

## Model Assignment

| Content type           | Model               |
| ---------------------- | ------------------- |
| 招聘时间轴、动画类页面 | deepseek-v4-pro     |
| 组件（日期选择器等）   | Qwen3.8-Max-Preview |
| 创意/趣味页面          | Qwen3.8-Max-Preview |
| 桌面环境体验类页面     | Qwen3.8-Max         |

## Style Kit

This project uses [StyleKit](https://www.stylekit.top/) design systems. When generating or modifying the portfolio index page (`index.html`), follow the specified style kit rules strictly.

Current style kit for `index.html`: [Comic Style](https://www.stylekit.top/zh/styles/comic-style) — 漫画风格，灵感源自漫画书和日式漫画，浓重墨线边框、网点填充、对话气泡、动作线。

When a style kit is provided in the prompt:

1. Read the style kit rules carefully before generating code.
2. Output a self-check after generation verifying all FORBIDDEN / REQUIRED rules are satisfied.
3. Do not deviate from the style kit's token dictionary (borders, shadows, typography, spacing).

## Viewing

Open any `.html` file directly in a browser:

```bash
open recruitment-timeline-2026.html
```
