---
tags: [documentation, meta, sessions]
content_type: instructions
audience: ai-agents
created: 2025-11-21
updated: 2025-11-21
---

# AGENTS: sessions/

Use this guide when drafting or revising session notes. Keep the Arena theatrical and consequence-heavy.

## Load This Context First
- `../environment/` for world framing.
- Mechanics: `mechanics`.
- Current cast: `players/characters.md`; add relevant `npcs/*.md` for featured characters. Pay attention to `status` of NPCs and do not include dead NPCs.
- Inspect the notes from the previous session, `session_x_notes.md` for deaths, plot points etc

## Organization
- create 5 files per session using the templates available at `@templates/`
  - `session_x_setup_players.md` which holds pre-session setup to be shared with the players
  - `session_x_setup_gm.md` which holds pre-session info for the game master. 
  - `session_x_encounter.md` holds details of how to run the sessions: npcs, enemies, environment changes etc
  - `session_x_notes.md` holds notes from the played session, actions taken favor granted, items taken, plot lines developed etcre
  - `session_x_snak_shop.md`: follow the advices in @items/AGENTS.md
Within each template file, look for lua braces `{{}}` for content to fill in 


## Session Format (keep consistent)
1. Pre-game interactions: character moments, NPC conversations, world hooks.
2. Combat encounters: deadly for 3-6 PCs considering their level. 
3. Post-combat aftermath: rewards, political interest, reputation shifts, injuries or deaths.
4. Between-session events: downtime that seeds the next setup.


## Writing Rules
- Track consequences and continuity (wounds, debts, patron favors). Consult previous sessions notes.
- Link named NPCs, locations, and mechanics using Obsidian wiki-link syntax.
- Aim for concise headings and bullets where it helps scanning; otherwise flow with narrative prose.

When writing NPC dialog, follow the rules in @npc_dialog_rules.md
