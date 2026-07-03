# exec-ea — Executive Assistant plugin

Skills for an AI executive assistant, designed to run in Claude Cowork over a **local markdown memory** folder.

**Skills** (namespaced `/exec-ea:<name>`):
- `brief` — the daily executive brief
- `draft` — draft an email/reply in the exec's voice (never sends)
- `research` — cited research → saved to memory
- `nudge` — set a proactive watch
- `remind` — time-based reminder
- `follow-up` — track commitments / show what's slipping

The skills are **generic** — they read and write a local memory workspace and follow its `_protocol.md`. All personal / organisation context lives in that **local** memory folder (`preferences.md`, `entities/`, etc.) and is **never** part of this repo.
