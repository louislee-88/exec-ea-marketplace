---
description: Draft an email or reply in the executive's voice for approval. Never sends.
disable-model-invocation: true
---

# Draft

Draft the message described in: **"$ARGUMENTS"**

- Write in the executive's voice — pull tone/sign-off/length from `preferences.md`.
- Pull relevant context from memory (`entities/`, `events/`, `commitments.md`) and connectors when available.
- Present the draft for review. End with: **"Approve / edit / dismiss?"**
- Do **NOT** send. Sending only happens later via the connector with explicit confirmation.
- When the exec edits your draft, append the change to `feedback/drafts.md` so the voice improves over time (per `_protocol.md`).
