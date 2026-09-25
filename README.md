# Wingo "Prediction" Overlay — Educational Demonstration

> **Purpose:** This is a *teaching tool*. It imitates the look of the "prediction"
> overlay apps that target players of color/number betting games (often marketed
> around "Wingo"), and then **proves, with live statistics, that the predictions
> are meaningless.** Nothing here connects to any real game, website, or server.

## Why this exists

Apps in this category promise "suggested selections synced to the next round."
In reality, the game's results are generated independently — the app has no way
to know or influence them. The overview these apps ship even admits it:
*the app does not interact with or influence the game's result-generation process.*

That means any "prediction" is, at best, a coin-flip dressed up with countdowns,
"remaining uses," and urgency to feel authoritative. This demo makes that visible:

- It runs its **own** simulated rounds (fair random draws).
- It shows a scam-style overlay with a countdown and a confident "prediction."
- It records every prediction vs. the actual draw and plots the running accuracy.
- Over time the accuracy converges to the mathematical baseline (chance), no
  matter how confident the overlay looks.

## What it is NOT

- It is **not** connected to any real betting game, app, or backend.
- It does **not** predict, and cannot predict, any real-world outcome.
- It contains **no** anti-analysis, obfuscation, payment, or account code.

## How to use

Open `index.html` in any browser. Watch the "prediction" panel and, below it,
the truth panel showing actual accuracy vs. the expected chance baseline.
Use it in security/consumer-awareness talks, classrooms, or write-ups about how
color-prediction scams manufacture false confidence.

## Files

- `index.html` — the full self-contained demonstration (no build, no network).
