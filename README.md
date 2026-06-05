# The AI Agency Ladder

A single-page **scrollytelling** field note for the team — on what it actually
looks like to go from *chatting with one AI assistant* to *conducting a squad of agents*.

**Live:** https://bangmarbot.github.io/ai-agency-ladder/

> You're already using AI. You're just standing on the bottom rung.

## The five rungs

1. **One assistant, one task** — ask → answer
2. **Give it hands** — connect it to your tools (it reads & writes your systems)
3. **Give it memory & a workspace** — context that persists between sessions
4. **From one agent to a squad** — a lead, a developer, a designer, a tester; you assign, they deliver
5. **The shift** — operator → orchestrator

## How to view it

- **Easiest:** open the live link → https://bangmarbot.github.io/ai-agency-ladder/
  (works on any device, including phones).
- **Offline:** download `index.html` and open it in any browser.

It's a **single self-contained file** — no install, no build step. Everything
(HTML + CSS + JS) lives in `index.html`; the only external request is Google
Fonts (falls back to system fonts offline).

## Stack

Vanilla HTML / CSS / JS. Scroll-driven via `IntersectionObserver`, a sticky ladder
rail that fills as you climb, ambient glow that morphs per rung, full reduced-motion
support, and zero horizontal overflow on mobile.

---

*Built — of course — by handing it to an agent.*
