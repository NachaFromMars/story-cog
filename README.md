# story-cog — Creative writing and storytelling via CellCog

> Write short fiction, novels, screenplays, fan fiction, and more through the CellCog SDK. Runs async in the background and notifies you when your story is ready.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
story-cog brings creative writing to OpenClaw through the CellCog SDK. It handles short fiction, novels, screenplays, fan fiction, world building, character development, and narrative design. Generation follows a fire-and-forget async pattern — prompts are sent via `create_chat` with a `notify_session_key` so long-form work runs without blocking the agent. Requires the `cellcog` skill installed first.

## Features
- **Formats** — short fiction, novels, screenplays, fan fiction
- **Craft** — world building, character development, narrative design
- **Async** — fire-and-forget with `notify_session_key` completion signal
- **CellCog-powered** — `create_chat` for story prompts

## Usage / Quick Start
```bash
clawhub install cellcog   # required dependency
```
Then trigger: *"Write a short sci-fi story about a lighthouse keeper on Mars"*

## Trigger Keywords (OpenClaw)
write story, creative writing, novel, screenplay, world building, character development, narrative design, fan fiction

## Related Skills
- **cellcog** — required SDK (`clawhub install cellcog`)
- [think-cog](https://github.com/NachaFromMars/think-cog) — complex reasoning via CellCog

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
