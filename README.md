# The AI Agency Ladder

A single-page **scrollytelling** field note for the ALVA team — on what it actually
looks like to go from *chatting with one AI assistant* to *conducting a squad of agents*.

> You're already using AI. You're just standing on the bottom rung.

## The five rungs

1. **One assistant, one task** — ask → answer
2. **Give it hands** — connect it to your tools (it reads & writes your systems)
3. **Give it memory & a workspace** — context that persists between sessions
4. **From one agent to a squad** — a lead, a developer, a designer, a tester; you assign, they deliver
5. **The shift** — operator → orchestrator

## How to view it

This is a **single self-contained file** — no install, no build step.

- **Easiest:** download `index.html` and open it in any browser (works offline).
- Or clone the repo and open `index.html`.

Everything (HTML + CSS + JS) lives in `index.html`. The only external request is
Google Fonts (falls back to system fonts offline).

## Want a shareable URL later?

This repo is private, so there's no public link by design. If you ever want one,
enable **GitHub Pages** on the default branch — the site is plain static HTML and
will work as-is.

## Stack

Vanilla HTML / CSS / JS. Scroll-driven via `IntersectionObserver`, a sticky ladder
rail that fills as you climb, ambient glow that morphs per rung, full reduced-motion
support, and zero horizontal overflow on mobile.

---

*Built — of course — by handing it to an agent.*
