# ai-delivery

[**中文说明**](README_zh.md)

*A collection of skills for non-technical people to build real software projects using AI.*

---

## Who is this for?

This repo is for people who:

- Have an idea for an app, website, or tool
- Don't know how to code
- Want to get something built without spending months learning to program

> **Note for developers:** The skills here are written for non-technical users. If you are a developer, you can directly use the `.claude/skills/dev-delivery.md` file in your own projects.

---

## What can you build?

- A personal website or blog
- A small web app (e.g., an expense tracker, a habit tracker)
- A tool to automate repetitive tasks on your computer
- A simple chatbot or automation workflow

---

## What do you need?

1. **A clear idea** — what you want to build, even in plain words
2. **Claude Code** — a free AI coding tool from Anthropic
3. **A computer** — Mac, Windows, or Linux

---

## How does it work?

```
You describe what you want
        ↓
AI creates a development plan (in plain words)
        ↓
You review and approve
        ↓
AI builds and tests, step by step
        ↓
You verify the result — if something is wrong, AI fixes it
        ↓
Delivery (or a list of decisions you need to make)
```

---

## Skills available

| Skill | What it does |
|-------|-------------|
| `dev-delivery` | Guides AI through the full cycle: understand → plan → build → test → deliver |

---

## How to use

**Step 1:** Download Claude Code from [claude.ai/code](https://claude.ai/code) (free)

**Step 2:** In your project folder, run:
```bash
git clone https://github.com/maxilen/ai-delivery.git ./.claude/
```

**Step 3:** Tell Claude Code:
> "Use the dev-delivery skill to help me build [your idea]"

Claude will take it from there.

---

## FAQ

**Q: Do I need to know how to code?**
No. You describe what you want in plain language.

**Q: What if I want to change something midway?**
Just say so. AI will adjust and keep going.

**Q: What if the project gets stuck?**
AI will give you a list of things to decide. You make the call, then AI continues.

**Q: What if it doesn't work?**
You can always try again or describe the problem differently. AI will attempt to fix it.

---

## Directory

```
ai-delivery/
├── README.md          ← English (you are here)
├── README_zh.md       ← 中文完整版
└── .claude/
    └── skills/
        └── dev-delivery.md
```
