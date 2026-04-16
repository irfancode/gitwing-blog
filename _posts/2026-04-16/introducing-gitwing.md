---
layout: post
title: "Introducing GitWing: Native Git for Apple Silicon"
date: 2026-04-16
author: Irfan Code
category: announcements
excerpt: A new native macOS Git tool built with SwiftUI that brings worktree management, AI commits, and blazing-fast performance to your workflow.
---

# Introducing GitWing: Native Git for Apple Silicon

After analyzing the current state of Git tools on macOS, I realized there was a gap: **a truly native, Apple Silicon-first Git tool** that combines menu bar convenience with powerful features.

## Why GitWing?

Most Git tools today fall into two categories:
1. **Electron-based GUIs** (GitKraken, GitHub Desktop) — Bloated, slow, high RAM usage
2. **Terminal apps** (lazygit, tig) — Great, but require living in the terminal

GitWing bridges this gap with a **native SwiftUI menu bar app** that's:
- ⚡ **Blazing fast** — Native SwiftUI, no Electron
- 🖥️ **Menu bar app** — Always accessible, no window clutter
- 🤖 **AI-powered** — Smart commit messages
- 🎯 **Worktree management** — Quick branch switching
- 👁️ **Diff viewer** — Beautiful syntax-highlighted diffs

## Features

### Menu Bar Workflow
GitWing lives in your menu bar. Click the wing icon (🦅) to access:
- Worktree switching
- Quick commits
- Diff viewing
- Command palette

### AI Commits
GitWing analyzes your staged changes and suggests meaningful commit messages. Uses local Ollama for privacy, or connect to OpenAI/Anthropic.

### Native Performance
Built 100% in SwiftUI for macOS 14+. Optimized for Apple Silicon with universal binaries.

## Getting Started

```bash
# Clone the repo
git clone https://github.com/irfancode/gitwing.git

# Open in Xcode
open GitWing/Sources/GitWing.xcodeproj

# Build and run
⌘R
```

## What's Next

- [ ] Command palette (⌘K)
- [ ] GitHub/GitLab integration
- [ ] Pull request creation
- [ ] Branch visualization
- [ ] Keyboard shortcuts

## Join the Project

GitWing is open source under MIT license. Contributions welcome!

**Repository:** [github.com/irfancode/gitwing](https://github.com/irfancode/gitwing)