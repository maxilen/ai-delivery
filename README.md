# ai-delivery

---

## 作者简介 / About Me

我是一个做了 20 多年的互联网行业人力资源从业者，自己没有任何技术基础，所知都跟技术团队一起工作时耳濡目染的。

I am a 20+ year HR professional in the internet industry with zero technical background. Everything I know about technology comes from working alongside engineering teams and picking things up along the way.

技术专业人员可以无视本 repo，但对技术小白的你，这里面的每一个字都是我能用最通俗的话写出来的。

If you are a technical professional, you can ignore this repo. But if you are a non-technical person like me, every word here is written in the simplest language I know.

---

## 这是什么 / What Is This

一组帮你用 AI 做开发的工具。

A collection of tools (called "skills") that help you develop things using AI.

你不需要会写代码，不需要懂技术。只需要你知道自己想要什么——比如"我想做一个网站"或"我想做一个记账的小工具"。

You do not need to know how to code or understand technology. You only need to know what you want — for example, "I want to make a website" or "I want to build a small expense tracker."

然后把这件事告诉 AI，AI 会帮你把事情做出来。

Tell the AI what you want, and it will help you build it.

---

## 这个 skill 能做什么 / What This Skill Does

dev-delivery 是这个仓库里第一个上线的 skill。

dev-delivery is the first skill in this repository.

它的核心功能：**帮你把一个想法变成真实可以用的东西**。

Its core function: **turn your idea into something real you can actually use.**

比如：
For example:

- "我想做一个个人主页"
- "I want to make a personal website"
- "我想做一个可以记录我每天做了什么的工具"
- "I want to build a tool to track what I do every day"
- "我想做一个小工具，把我上传的 Excel 文件自动整理成报表"
- "I want a tool that takes my uploaded Excel file and automatically organizes it into a report"

不管大小，AI 都可以帮你做。

Big or small, the AI can help you build it.

---

## 我需要准备什么 / What You Need to Prepare

### 1. 一个想法（最重要的）

### 1. An Idea (The Most Important Thing)

知道自己想要什么。能说清楚就行，不需要想好怎么做。

Know what you want. Just be able to describe it. You do not need to know how to build it.

### 2. 一个 Claude Code 账号

### 2. A Claude Code Account

这个 skill 是给 Claude Code 用的。Claude Code 是 Anthropic 公司出的 AI 编程工具，有免费额度。

This skill works with Claude Code, an AI coding tool by Anthropic. It has a free tier.

注册地址：https://claude.ai

Sign up here: https://claude.ai

### 3. 一台电脑（Mac 或 Windows 都可以）

### 3. A Computer (Mac or Windows)

不需要高配置，能打开浏览器、能打字就行。

No need for a powerful machine. Any computer that can open a browser and type will do.

---

## 怎么用 / How to Use It

### 第一步：把 skill 下载到你的项目文件夹

### Step 1: Download the Skill to Your Project Folder

打开命令行，进入你想放项目的文件夹，运行：

Open your terminal, go to the folder where you want your project, and run:

```bash
git clone https://github.com/maxilen/ai-delivery.git ./.claude
```

这行命令的意思是：把这个仓库里的 skill 文件下载到你当前文件夹的 `.claude/skills/` 目录里。

This command downloads the skill files into a `.claude/skills/` folder inside your current directory.

### 第二步：告诉 Claude Code 你想做什么

### Step 2: Tell Claude Code What You Want to Build

在同一个文件夹里，打开 Claude Code：

In the same folder, open Claude Code:

```bash
claude
```

然后直接说你的需求，比如：

Then just say what you want, for example:

> "我想做一个个人主页，帮我用 dev-delivery skill 开发"

> "I want to build a personal website, use the dev-delivery skill to help me develop it"

Claude Code 会自动发现这个 skill 并开始工作。

Claude Code will automatically find this skill and start working.

---

## 这个 skill 是怎么工作的 / How It Works

dev-delivery 会按以下步骤帮你做开发：

dev-delivery helps you develop in these steps:

### 第一步：AI 先了解你的项目

### Step 1: AI Learns About Your Project

AI 会先读你项目里的文件，了解你用的是什么技术、有什么模块。

The AI first reads files in your project to understand the technology stack and modules.

### 第二步：AI 写出开发计划

### Step 2: AI Writes a Development Plan

AI 会把要做的事情拆成最小的单元，比如"先做登录页"、"再做数据保存"。

The AI breaks down the work into the smallest units, for example "first build the login page, then build data storage."

每一步都会写清楚要做什么、怎么测试。

Each step clearly states what to do and how to test it.

这个计划会先给你看，你同意了才会开始做。

The plan is shown to you first. It only starts after you approve.

### 第三步：AI 开发和测试

### Step 3: AI Develops and Tests

AI 按计划一步步开发，每做完一步会真实运行测试，确保没问题。

The AI follows the plan step by step, running real tests after each step to make sure everything works.

不是随便说"测了"，而是真正跑命令、看结果、记录下来。

It does not just say "tested." It actually runs commands, checks results, and records them.

### 第四步：集成测试

### Step 4: Integration Testing

当几个部分拼在一起时，AI 会做回归测试，确保新加的东西没有把之前的功能弄坏。

When parts are combined together, the AI runs regression tests to make sure new changes do not break existing features.

### 第五步：交付

### Step 5: Delivery

完成后 AI 会告诉你：
- 哪些功能做好了
- 怎么验证它真的 work
- 如果还有需要你决定的事情，会列出来让你选

After completion, the AI tells you:
- Which features are done
- How to verify they actually work
- If there are things that need your decision, it lists them for you to choose

---

## 我需要懂技术吗 / Do I Need Technical Knowledge

不需要。

No.

你只需要：
- 说清楚你想要什么
- 看 AI 给你的计划，觉得不对的地方说出来
- AI 做完了，帮你验证一下是不是你要的

You only need to:
- Clearly describe what you want
- Review the plan AI gives you and speak up if something looks wrong
- Help verify the result is what you wanted after AI finishes

技术的事，AI 和这个 skill 会帮你处理。

Technology stuff is handled by the AI and this skill.

---

## 中途想改需求怎么办 / What If I Want to Change Mid-Way

随时可以说"不对，我想要改成 xxx"。

You can say "no, I want to change this to xxx" at any time.

AI 会停下来，重新调整计划，然后继续。

The AI will stop, adjust the plan, and continue.

---

## 常见问题 / FAQ

**Q: 这个是完全免费的吗？**  
A: 这个 skill 本身免费。Claude Code 有免费额度，用完需要付费。但日常小项目基本够用。

**Q: Is this completely free?**  
**A:** The skill itself is free. Claude Code has a free tier. You only pay when you exceed the free limit. For small everyday projects, the free tier is usually enough.

---

## 技术专业人员请看 / For Technical Professionals

如果你懂技术，这个 repo 的 skill 文件（`.claude/skills/dev-delivery.md`）是一个结构化的 AI 开发流程规范，可以直接在你的项目里加载使用，支持 Claude Code、Cursor 等主流 AI 编程工具。

If you are a technical professional, the skill file (`.claude/skills/dev-delivery.md`) in this repo is a structured AI development workflow specification. It can be loaded directly into your projects and works with Claude Code, Cursor, and other major AI coding tools.

---

## 这个 repo 还会陆续增加更多 skill

This repo will continue adding more skills over time.

如果你有好的想法，欢迎提 issue 或 pull request。

If you have good ideas, feel free to open an issue or pull request.
