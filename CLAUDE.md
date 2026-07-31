# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

A static HTML portfolio of vibe-coded web pages. No build system, bundler, or runtime dependencies — just open HTML files directly in a browser.

## File Naming Rules

- Rename new HTML files to short, meaningful English names (e.g., `modeltea.html`, `recruitment-timeline-2026.html`).
- After renaming, add the file to the table in `README.md`.

## Model Assignment

| Content type           | Model               |
| ---------------------- | ------------------- |
| 招聘时间轴、动画类页面 | deepseek-v4-pro     |
| 组件（日期选择器等）   | Qwen3.8-Max-Preview |
| 创意/趣味页面          | Qwen3.8-Max-Preview |

## Viewing

Open any `.html` file directly in a browser:

```bash
open recruitment-timeline-2026.html
```
