# ai-delivery

[**中文说明**](README_zh.md)

*A collection of skills for non-technical people to build real software projects using AI.*

---

## About Me

I am a 20+ year HR professional in the internet industry with zero technical background. Everything I know about technology comes from working alongside engineering teams and picking things up along the way.

Technical professionals can ignore this repo. But if you are a non-technical person like me, every word here is written in the simplest language I know.

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
- A simple AI-powered assistant for your work
- A data processing or report generation tool

---

## What do you need?

1. **A clear idea of what you want** — You don't need technical details. "I want a website where I can track my expenses" is enough.
2. **Claude Code** — A free AI tool from Anthropic. Download at [code.claude.com](https://code.claude.com).
3. **A computer** — Mac, Windows, or Linux. That's it.

---

## How does it work?

**Step 1 — Download the skill**

```bash
git clone https://github.com/maxilen/ai-delivery.git
```

Place the skill file into your project folder:

```bash
# If you already have a project folder:
cp ai-delivery/.claude/skills/dev-delivery.md /your-project/.claude/skills/

# If you are starting from scratch, just keep the skills folder in your project:
cp -r ai-delivery/.claude /your-new-project/
```

**Step 2 — Tell Claude Code what you want**

Open Claude Code in your project folder and say something like:

```
Use the dev-delivery skill to help me build [your idea]
```

Claude Code will load the skill, understand your project, create a development plan, execute it, test it, and deliver the result.

---

## What does the workflow look like?

The skill breaks everything into small steps:

1. **Understand your project** — Claude reads your files and understands what you already have
2. **Make a plan** — Breaks the work into the smallest possible pieces, plans how to test each piece
3. **Build step by step** — Works through each piece, tests as it goes
4. **Integration testing** — When pieces are combined, runs regression tests
5. **Deliver or pause for decisions** — If something needs your input, it clearly lists your options and waits

You can pause at any time, think, change your mind, and tell Claude to continue. The skill keeps track of where you left off.

---

## Do you need to understand technology?

No. You just describe what you want. Claude Code with this skill handles all the technical work.

However, you do make decisions. For example:
- "I like option A better" — or —
- "This doesn't feel right, can we change it?"

These decisions are part of the creative process, not the technical process.

---

## Can I change my mind mid-project?

Yes. That's normal and expected.

Just say things like:
- "I want to add a feature: ..."
- "Actually, can we change X to Y?"
- "The current result is good, but I need it to do Z instead"

The skill keeps track of your project state and continues from where you left off.

---

## What if I get stuck?

The skill will tell you exactly what it needs from you, in plain language. For example:

```
I need your input on two things:

1. Should the login use email or phone number?
   - Option A: Email (more professional)
   - Option B: Phone number (faster for users)

2. Should we store data locally or in the cloud?
   - Option A: Local (free, private, but only accessible on this device)
   - Option B: Cloud (accessible anywhere, but requires an account)
```

You just pick an option and the work continues.

---

## Directory structure

```
ai-delivery/
├── README.md             ← English (you are here)
├── README_zh.md          ← 中文完整版
└── .claude/
    └── skills/
        └── dev-delivery.md
```
