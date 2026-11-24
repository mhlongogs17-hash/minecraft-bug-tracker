# Minecraft Bug Tracker🎮

A simple web app for Minecraft players to report, track, and manage bugs they find in the game.


**Live app:** https://mhlongogs17-hash.github.io/minecraft-bug-tracker/
**Code:** https://github.com/mhlongogs17-hash/minecraft-bug-tracker

---

## The Problem

Minecraft players keep seeing the same bugs, but they have nowhere to track them.

Example — Bug #1:
> No beds inside village houses. You go into a village at night, no beds, zombies chasing you.

So instead of just complaining about bugs, I built a tool to track them.

## What It Does

- **Report a bug** — Enter Game, Version, Device, Mode, and Bug Details
- **Save a bug** — Click "Save bug!" and it appears in Saved Bugs
- **Validation** — Game, Device, and Mode are dropdowns, so users can't type "GTA" or misspell "Andriod". Bug Details is the ONLY place you can write freely.
- **Live in browser** — No install needed, just open the link

## How To Use It

1. Open the live app link
2. Choose Game: Minecraft
3. Type Version: e.g. `1.21` or `26.3`
4. Choose Device: Android / PC / Mac
5. Choose Mode: Single / Multiplayer / Online
6. Write Bug Details: e.g. `No beds in village houses`
7. Click **Save bug!**
8. Your bug appears under **Saved bugs.**

## What I Used, How I Used It

| Tool | What I Used It For | How |
| :--- | :--- | :--- |
| **HTML** | Structure | Welcome, Bug Form, Saved Bugs sections |
| **CSS** | Layout & Style | Centered with `max-width: 700px` + `margin: 0 auto`, stacked inputs with `display: block`, Minecraft green button, responsive with `width: 100%` |
| **JavaScript** | Behaviour | `document.getElementById()` to find inputs, `saveBug()` to save bugs, validation with alerts, `createElement()` to add bugs to list |
| **VS Code** | Code editor | Wrote all code, used Terminal for Git |
| **GitHub** | Save + Share | Saved versions with commits, hosted live site with GitHub Pages |
| **Git** | Version control | `git add .`, `git commit -m "..."`, `git push` |

## Project Structure

```
minecraft-bug-tracker/
├── index.html   # Whole app — HTML structure + CSS style + JavaScript logic
└── README.md    # This file
```


## Author

**Given Mhlongo**
Aspiring Software Engineer | Learning Python, HTML, CSS & JavaScript | Future BCom @ UP (2027)
Building in public

LinkedIn: https://www.linkedin.com/in/given-mhlongo
GitHub: https://github.com/mhlongogs17-hash

> "Discipline beats motivation. Code every day, debug your failures, and build your future."

