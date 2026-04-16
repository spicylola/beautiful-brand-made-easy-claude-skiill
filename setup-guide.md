# Setup Guide
## Beautiful Brand Design Made Easy

*Four ways to use this skill — from easiest to most technical.*

---

## ⭐ The Easiest Way — Claude Projects (Recommended)

Claude Projects lets you upload your skill file once and Claude reads it automatically every time you start a new conversation. No copy-pasting. Ever.

**Works on the free Claude.ai plan.**

### Step 1 — Create a free Claude account

1. Go to **claude.ai** in your browser
2. Click **Sign up**
3. Enter your email and create a password
4. Verify your email — you're in

### Step 2 — Create a new Project

1. In the left sidebar, look for **Projects**
2. Click **New Project**
3. Give it a name — e.g. `Brand Kit Builder`

### Step 3 — Upload the skill file

1. Inside your new Project, find **Project Knowledge** or **Add Content**
2. Click **Upload files**
3. Select `SKILL.md` from this zip
4. Claude confirms it's been added — you're done with setup

### Step 4 — Start a new chat inside the Project

1. Click **New Chat** from inside the Project (not from the main sidebar)
2. Type something like: `Let's build my brand kit`
3. Claude already knows the skill — it starts guiding you immediately

**That's it. No prompts to copy. No setup to repeat. Every new chat inside this Project automatically has the skill loaded.**

**Tips:**
- Upload moodboard images directly into the chat using the paperclip icon
- To build a kit for a different brand later, just start a new chat in the same Project
- Your conversation history is saved so you can always come back

---

## Option B — Custom System Prompt (Claude Pro)

If you're on Claude Pro, you can make this skill activate on every Claude conversation automatically — not just inside a Project.

### Steps

1. Go to **claude.ai** and click your profile icon → **Settings**
2. Find **Custom Instructions** or **System Prompt**
3. Open `SKILL.md` from this zip in any text editor
4. Copy the full prompt (the block starting with `You are an expert brand designer...`)
5. Paste it into the custom instructions field and save

From now on every Claude conversation starts with this skill active — no setup needed.

---

## Option C — Claude Code (For Developers)

Claude Code is a command-line tool that reads files directly from your computer. No uploading, no copy-pasting — just point it at the folder.

### Step 1 — Install Claude Code

Make sure **Node.js** is installed first (nodejs.org), then:

```bash
npm install -g @anthropic-ai/claude-code
```

### Step 2 — Navigate to the skill folder

Unzip your download and navigate to it:

```bash
cd ~/Downloads/beautiful-brand-design-made-easy
claude
```

Claude Code reads all files in the folder including `SKILL.md` automatically.

### Step 3 — Start building

```
Let's build my brand kit using the skill in SKILL.md
```

### Step 4 — Let Claude save the file for you

When your kit is ready, say:

```
Save this as my-brand-kit.html in the current directory
```

Then open it:

```bash
open my-brand-kit.html     # Mac
start my-brand-kit.html    # Windows
```

---

## Option D — Manual Copy-Paste (Any Plan, No Setup)

Works instantly with any free Claude account — no project or configuration needed.

### Steps

1. Go to **claude.ai** → **New Chat**
2. Open `SKILL.md` from this zip in any text editor
3. Copy the full prompt block starting with `You are an expert brand designer...`
4. Paste into Claude and hit Enter
5. Follow the conversation

When Claude generates your HTML:
1. Copy all the code
2. Paste into a text editor and save as `my-brand-kit.html`
3. Double-click to open in any browser

---

## Which Option Is Right For Me?

| Method | Plan | Tech level | Setup |
|---|---|---|---|
| ⭐ Claude Projects | Free | Beginner | 3 min once |
| Custom system prompt | Pro | Beginner | 2 min once |
| Claude Code | Free | Developer | 10 min once |
| Manual copy-paste | Free | Anyone | 1 min per chat |

**Not sure? Use Claude Projects** — easiest, free, and once set up you never think about it again.

---

## Tips For Best Results

- **Share moodboards** — upload images, screenshots, or inspiration photos via the paperclip icon
- **Be specific about your audience** — "women 25–35 who love wellness" beats "everyone"
- **No logo? No problem** — Claude creates a beautiful text-based wordmark
- **Iterate freely** — say "make the colors warmer" or "try a different font" and Claude updates the kit
- **Save your HTML files** — you can get up to 4: brand kit, website mockup, physical mockups, and business card. Open in browser, print to PDF, or host online

---

## What To Do With Your Brand Kit

- **Share with your team** — just send the `.html` file
- **Print to PDF** — browser → File → Print → Save as PDF
- **Reference while designing** — keep it open alongside Figma or Canva
- **Hand to a developer** — hex codes, fonts, specs all right there
- **Host online** — upload to any web host and link to it as your public brand page

---

## Troubleshooting

| Problem | Fix |
|---|---|
| Claude stopped mid-generation | Type `continue` |
| HTML looks broken | Make sure you copied everything including `<!DOCTYPE html>` and `</html>` |
| Want to change something | Tell Claude exactly what: "make the background darker" |
| Not happy with colors | Say "I want something more warm/bold/minimal" |
| Can't upload image | Describe it instead: "like Glossier — clean, pink, minimal" |
| Project not reading skill | Make sure you started the chat from inside the Project, not the main sidebar |

---

*Beautiful Brand Design Made Easy · by Lola · v2.0 · 2026*
*Questions? Reach out via your Luhlah purchase page.*
