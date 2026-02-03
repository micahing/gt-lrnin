# Get Started with Gemini CLI

![Hello Friend](https://media.tenor.com/x4jqWpQc8JMAAAAM/mr-robot-elliot-alderson.gif)

Hello, friend. You ever see someone in a movie type green text into a black screen and wish that was you? Good news.

Heynong man. Let's start fresh. This guide gets you set up with Gemini CLI in under 10 minutes.

Want the official docs? Here you go: [Gemini CLI Docs](https://geminicli.com/docs)

---

## Wait, What Even Is This?

Gemini CLI is what's called an "AI coding agent." Think of it like a really smart assistant that lives in your terminal (that black rectangle). You type questions or requests, it responds. But unlike ChatGPT in a browser, this thing can actually *do stuff* on your computer — read files, write code, help you organize things.

**What people use these for:**
- Writing and editing documents
- Brainstorming ideas
- Learning new things (it explains stuff well)
- Automating boring repetitive tasks
- Writing code (even if you're not a programmer)

There are a few of these tools out there — Gemini CLI (Google), Claude Code (Anthropic), GitHub Copilot, etc. They're all similar vibes. This guide focuses on Gemini CLI because it's free and works well.

---

## Before You Start: Stay Safe

These tools are powerful, which means you should know the basics before diving in. Here's the quick version:

**Do:**
- Review what the tool wants to do before saying yes
- Start with low-stakes stuff while you're learning
- Ask it to explain what it's doing if you're unsure

**Don't:**
- Paste passwords, SSNs, or sensitive personal info
- Let it access work files with confidential data
- Approve actions you don't understand (unless you want to)

These tools can read and write files on your computer. That's what makes them useful, but it's also why you want to pay attention. It's like hiring a contractor — helpful, but you still want to see what they're doing before they knock down a wall.

For a deeper dive, the [OpenSSF Security Guide for AI Code Assistants](https://best.openssf.org/Security-Focused-Guide-for-AI-Code-Assistant-Instructions) is the real deal.

---

## What You'll Need

- A Google account (free, like the coffin flop footage they can't stop showing)
- A Mac
- **Node.js 20+** (we'll install it in Step 3)

That's it. No gift receipt needed.

---

## Step 1: Open Terminal

Press **Cmd + Space** to open Spotlight, type **Terminal**, and hit Enter.

You'll see a window with a blinking cursor. This is where fsociety lives. This is where you become the villain (ALL CAPS when you spell the man name).

![Step 1: Open Terminal](images/terminal/step-1-open-terminal.svg)

---

## Step 2: Install Homebrew

Homebrew is like the banana stand of Mac software. Copy and paste this entire command:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Press Enter and follow any prompts.

**What to look for:** "Installation successful!" — Not this:

![I've made a huge mistake](https://media.giphy.com/media/11BAxHG7paxJcI/giphy.gif)

**Password note (normal):** Homebrew may ask for your Mac password. When you type, you won’t see letters (or dots) appear — that’s normal. Just type it carefully and press Enter.

> **Important:** After installation, Homebrew will show you two or three commands to run. Copy and paste those commands one at a time exactly as shown. They look something like:
> ```bash
> echo >> /Users/yourname/.zprofile
> eval "$(/opt/homebrew/bin/brew shellenv)"
> ```
>
> Don't skip this part. And don't copy this example. That's the move of someone who has no hunger for it.

![Step 2: Install Homebrew](images/terminal/step-2-install-homebrew.svg)

---

## Step 3: Install Node.js

```bash
brew install node
```

**What to look for:** Text scrolling by. When you see the `$` prompt again, sit down — be humble.

![Step 3: Install Node.js](images/terminal/step-3-install-node.svg)

---

## Step 4: Install Gemini CLI

```bash
npm install -g @google/gemini-cli
```

**What to look for:** Installation complete with no red error messages. If you see red, that's bad. Real bad, like "No soup for you" bad.

![Step 4: Install Gemini CLI](images/terminal/step-4-install-gemini.svg)

---

## Step 5: Create Your Workspace

Let's make a folder for your AI projects:

```bash
mkdir mr-robot && cd mr-robot
```

You're now inside your new `mr-robot` folder. Control is an illusion, but this folder is real.

![Step 5: Create Workspace](images/terminal/step-5-create-workspace.svg)

---

## Step 6: Launch Gemini

```bash
gemini
```

That's it. One word. Like "Gabagool" but for AI.

![Step 6: Launch Gemini](images/terminal/step-6-launch-gemini.svg)

---

## Step 7: Sign In with Google

Gemini will ask how you want to authenticate.

**Select option 1** (Login with Google).

A browser window will open. Sign in with your Google account and approve access.

**What to look for:** Back in Terminal, you'll see Gemini ready for input. The robot talks back now. People can change.

![Step 7: Google Sign-In Prompt](images/terminal/step-7-sign-in-prompt.svg)

![Step 8: Gemini Ready](images/terminal/step-8-gemini-ready.png)

**Note:** Some Google accounts (like certain Workspace accounts) may be asked for a Google Cloud project. If that happens, follow the on-screen prompts.

---

## First Things to Try

Here are some starter prompts. Rap about it, write about it, think about it:

**Ask it to explain something:**
```
Explain how to use the terminal and gemini-cli like I'm Buster Bluth
```

**Have it write code:**
```
Write a Python script that counts down from 10 and says "Heynong man!" at the end
```

**Get creative:**
```
Give me 5 startup ideas that George Costanza would pitch to Mr. Peterman
```

**Go full villain:**
```
Write me a short rap verse about coding in the style of MF DOOM
```

---

## More Ideas

Here’s where it gets real. You can use Gemini to actually lighten your workload. No more doing everything yourself like Tony trying to run the family.

---

## Get the Sample Projects

Want to try the Financial Advisor project from this repo? Here's how to download it to your mr-robot folder.

In Terminal, run:

```bash
cd ~/mr-robot && curl -L https://github.com/micahing/gt-lrnin/archive/main.zip -o gt-lrnin.zip && unzip gt-lrnin.zip && mv gt-lrnin-main/projects . && rm -rf gt-lrnin-main gt-lrnin.zip
```

That's one long command — just copy the whole thing and paste it.

Now you've got a `projects` folder inside `mr-robot`. Try the Financial Advisor:

```bash
cd ~/mr-robot/projects/financial-advisor
gemini
```

It'll automatically load instructions that make Gemini act like a patient financial advisor. Not in the waste management business, but it'll help you manage your money.

---

## Free Tier Limits

Good news: Gemini CLI is free with your Google account if you sign in with **Login with Google**.

- 60 requests per minute
- 1,000 requests per day

If you use an **API key** instead, the free limits are lower. That's plenty. And remember: you don't need to keep the receipt.

For the latest limits and pricing details, check the official docs: [Gemini CLI Docs](https://geminicli.com/docs)

---

<details>
<summary>Prefer a visual interface? (Click to expand — not that there's anything wrong with that)</summary>

### GUI Alternatives

If the command line isn't your thing:

- **VS Code + Gemini Code Assist** - A code editor with AI built in. Like if Microsoft made a robot that actually helps. [Get VS Code](https://code.visualstudio.com/)

- **Google AI Studio** - Web-based playground at [aistudio.google.com](https://aistudio.google.com). For when you want to point and click.

- **GeminiDesk** - Unofficial desktop app (third-party, use at your own discretion — we're all trying to find the guy who made this)

The CLI is more powerful, but these are fine. Her?

</details>

---

*Made for Jamba*
