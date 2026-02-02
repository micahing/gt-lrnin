# Get Started with Gemini CLI

![Hello Friend](https://media.tenor.com/x4jqWpQc8JMAAAAM/mr-robot-elliot-alderson.gif)

Hello, friend. You ever see someone in a movie type green text into a black screen and wish that was you? Good news.

Heynong man. Let's start fresh. This guide gets you set up with Gemini CLI in under 10 minutes.

---

## What You'll Need

- A Google account (free, like the coffin flop footage they can't stop showing)
- Your Mac

That's it. No gift receipt needed.

---

## Step 1: Open Terminal

Press **Cmd + Space** to open Spotlight, type **Terminal**, and hit Enter.

You'll see a window with a blinking cursor. This is where fsociety lives. This is where you become the villain (ALL CAPS when you spell the man name).

---

## Step 2: Install Homebrew

Homebrew is like the banana stand of Mac software. Copy and paste this entire command:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Press Enter and follow any prompts.

**What to look for:** "Installation successful!" — Not this:

![I've made a huge mistake](https://media.giphy.com/media/11BAxHG7paxJcI/giphy.gif)

> **Important:** After installation, Homebrew will show you two commands to run. Copy and paste those commands exactly as shown. They look something like:
> ```bash
> echo >> /Users/yourname/.zprofile
> eval "$(/opt/homebrew/bin/brew shellenv)"
> ```
>
> Don't skip this part. That's the move of someone who has no hunger for it.

---

## Step 3: Install Node.js

```bash
brew install node
```

**What to look for:** Text scrolling by. When you see the `$` prompt again, sit down — be humble.

---

## Step 4: Install Gemini CLI

```bash
npm install -g @anthropic-ai/gemini-cli
```

**What to look for:** Installation complete with no red error messages. If you see red, that's bad. Real bad, like "No soup for you" bad.

---

## Step 5: Create Your Workspace

Let's make a folder for your AI projects:

```bash
mkdir mr-robot && cd mr-robot
```

You're now inside your new `mr-robot` folder. Control is an illusion, but this folder is real.

---

## Step 6: Launch Gemini

```bash
gemini
```

That's it. One word. Like "Gabagool" but for AI.

---

## Step 7: Sign In with Google

Gemini will ask how you want to authenticate.

**Select option 1** (Login with Google).

A browser window will open. Sign in with your Google account and approve access.

**What to look for:** Back in Terminal, you'll see Gemini ready for input. The robot talks back now. People can change.

---

## First Things to Try

Here are some starter prompts. Rap about it, write about it, think about it:

**Ask it to explain something:**
```
Explain what an API is like I'm Buster Bluth
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

## Ideas for Meals on Wheels

Here's where it gets real. You can use Gemini to actually lighten your workload. No more doing everything yourself like Tony trying to run the family.

![I don't know how to use the body](https://media.giphy.com/media/8k4yBBH7EGT3nnSYod/giphy.gif)

**Draft volunteer recruitment emails:**
```
Write a friendly email recruiting volunteers for Meals on Wheels.
Emphasize flexibility, community impact, and that routes take about
1-2 hours. Keep it warm but not cheesy.
```

**Write grant application sections:**
```
Help me write the "Community Impact" section for a grant application.
We serve 200 seniors weekly, 40% live alone, and we're their primary
social contact. Make it compelling but factual.
```

**Create training materials:**
```
Write a one-page guide for new volunteer drivers. Cover: picking up
meals, delivery etiquette with seniors, what to do if no one answers,
and who to call for emergencies.
```

**Generate social media content:**
```
Give me 5 social media posts celebrating our volunteers. Mix of
heartfelt and lighthearted. No hashtag overload.
```

**Brainstorm fundraising ideas:**
```
Give me 10 creative fundraising event ideas for a Meals on Wheels
chapter. We're a small team, so nothing too labor-intensive.
```

---

## Next Steps

Ready for a real project? Try the [Financial Advisor Assistant](./projects/financial-advisor/) — a sample project that shows how to give Gemini a specific personality. It's not in the waste management business, but it'll help you manage your money.

---

## Free Tier Limits

Good news: Gemini CLI is free with your Google account.

- 60 requests per minute
- 1,000 requests per day

That's plenty. And remember: you don't need to keep the receipt.

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

*Made for James. Now go build something cool. The world is yours.*
