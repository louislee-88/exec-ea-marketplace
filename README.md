# exec-ea-marketplace

A Claude plugin marketplace containing the **exec-ea** plugin — a set of AI executive-assistant skills (`brief`, `draft`, `research`, `remind`, `follow-up`, `nudge`) that run in **Claude Cowork** over a local markdown memory folder.

## Install (Cowork)
Claude Cowork → **Plugins → Add from a repository** → `louislee-88/exec-ea-marketplace` → install **exec-ea**.

Then point Cowork at your own local memory folder (the skills read/write it). Try `/exec-ea:brief`.

## What's in here
- `.claude-plugin/marketplace.json` — the catalog
- `exec-ea/` — the plugin (skills + manifest)

The skills are **generic**. All personal / organisation context lives in your own **local** memory folder and is never part of this repo.
