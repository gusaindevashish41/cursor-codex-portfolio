# Step 1: Setting Up Cursor, Claude Code & Codex What I Did, What Broke, and How I Fixed It

This repo documents my completion of Step 1 in the 100Hires portfolio assessment. 
The task: install Cursor IDE, add the Claude Code and Codex extensions, create a public GitHub repository, and document the full process including the issues I hit along the way.


# Tools Installed

**Cursor IDE** = Version 3.5.38 — Windows 11
**Claude Code extension (by Anthropic)** = Version 2.1.153 — Signed in via GitHub
**Codex extension (by OpenAI)** = Version 26.519.32039 — Signed in with email
**GitHub account** = gusaindevashish41

---

## Steps Completed

1. Received Step 1 instructions from Alex Kravets (CEO, 100Hires) on May 27, 2026
2. Downloaded and installed Cursor IDE from cursor.com
3. Opened Extensions panel (Ctrl+Shift+X), searched "Claude Code", installed and signed in via GitHub
4. Searched "Codex", installed the OpenAI Codex extension, signed in with email
5. Created public GitHub repository "cursor-codex-portfolio"
6. Cloned the repo into Cursor using Command Palette (Ctrl+Shift+P → Git: Clone)
7. Wrote this README documenting the full process
8. Committed and pushed to GitHub

---

## Issues Encountered & How I Solved Them

### Issue 1: Codex Extension — No Sign-In pop -up Appeared

After installing the Codex extension, I expected a login popup — the description said 
it would appear automatically. Nothing showed up. I spent time checking settings, menus, 
and the extensions panel looking for a sign-in button. Searched YouTube and Google but 
couldn't find a clear answer from documentation alone.

Eventually a YouTube tutorial showed the fix: you don't wait for a popup — you have to 
manually open the extension yourself. Once I did that, the login option appeared. 
Signed in with my email and it worked.

### Issue 2: Git Not Installed — Repository Wouldn't Clone

When I tried to clone the repo in Cursor using the Command Palette 
(Ctrl+Shift+P → Git: Clone), nothing happened. Tried multiple times, same result.

After asking both ChatGPT and Claude to debug it, I found the answer: Git wasn't 
installed on my machine, and Cursor requires Git to be installed separately for any 
version control to work. Downloaded Git from git-scm.com, installed it, restarted 
Cursor — clone worked immediately.

---

## Reflection

Two things stood out from this process.

First, the irony of using AI tools to set up AI tools. When the Git clone wasn't 
working, my first instinct was to ask ChatGPT and Claude to debug it. That loop — 
AI helping me install AI — didn't feel like cheating; it felt like the correct move. 
I think that's how AI-assisted work actually functions: you don't stop and figure 
things out alone when a tool is right there.

Second, the Codex issue was a reminder that even well-documented tools can have 
unintuitive UX. The description said a popup would appear; it didn't. If I'd taken 
that literally and waited, I'd still be waiting. Searching, watching a YouTube video, 
and testing the fix myself was faster than trusting the documentation was complete.

Having Claude Code and Codex both running inside Cursor is a different experience than 
switching between browser tabs — the context stays in one place. I'll know in a few 
sessions whether that actually speeds things up or just adds noise.