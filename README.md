# Lyricomatics

A recording-room collaborator for **song lyrics**.

Not a DAW. Not a generator wrapper. Not an album factory. An [Agent Skill](https://agentskills.io) that briefs the writer, stays in the genre’s mouth, and cuts lines that sound like a caption.

[![License: MIT](https://img.shields.io/badge/license-MIT-111111?style=flat-square)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent_Skills-standard-111111?style=flat-square)](https://agentskills.io)
[![skills.sh](https://skills.sh/b/Master0fFate/Lyricomatics)](https://skills.sh/Master0fFate/Lyricomatics)

```bash
npx skills add Master0fFate/Lyricomatics
```

## Install

The CLI discovers `SKILL.md` at the repo root and wires it into the agents you use.

```bash
# this project
npx skills add Master0fFate/Lyricomatics

# every agent on the machine
npx skills add Master0fFate/Lyricomatics -g -y

# inspect before installing
npx skills add Master0fFate/Lyricomatics -l
```

Manual drop, if you prefer a folder:

| Harness | Path |
| --- | --- |
| Shared / Pi | `~/.agents/skills/lyricomatics` |
| Pi (alt) | `~/.pi/agent/skills/lyricomatics` |
| Claude Code | `~/.claude/skills/lyricomatics` |
| Codex | `~/.codex/skills/lyricomatics` |
| Project | `.agents/skills/lyricomatics` |

Restart the agent if it does not hot-pick new skills.

## Use

Ask to write, rewrite, workshop, or critique **song lyrics**, or say `use lyricomatics`.

On Pi: `/skill:lyricomatics`.

Give it a pocket and a situation when you have them. A title and a mood is not enough — it will ask a few sharp questions. Say **just write it** if you want it to skip the interview and still cast the song in silence.

It will not wake up for playlists, mixing, mastering, or music-generator prompts.

## How it works

**ROOM WORK** — a session, not a numbered QC gate.

```text
LISTEN → CAST → CUT → SING → BLEED → OFFER
```

| Stage | What happens |
| --- | --- |
| **LISTEN** | 3–6 questions if the brief is thin. Pocket, stakes, voice, bans. |
| **CAST** | Narrator, addressee, form, one image system, title candidates. |
| **CUT** | Draft or rewrite. Skip this on critique-only jobs. |
| **SING** | Speak-test, or scansion on the page if you cannot speak it. |
| **BLEED** | Anti-slop pass. No invented grief to “humanize” a celebration. |
| **OFFER** | Labeled lyric sheet, optional alts, 2–4 questions. Notes only if you asked for notes. |

The agent loads two reference files before ink: a family pocket and the anti-slop knife, not the whole tree.

## Genre pockets

Lyric craft only. No production recipes. Seventeen family files are the law: hip-hop, pop, R&B, country, rock, metal, folk, blues, jazz, theatre, gospel, Caribbean, Afro, Latin, East Asian pop, electronic, punk.

Hybrids pick a **primary** pocket. The secondary file donates its kill list, not a second personality.

If they name a niche those files cannot cover (angelcore, phonk, corridos tumbados, a regional split), the agent maps the nearest family, then does a **bounded** lyric-only lookup. The web does not replace the folder. No network: it says so and approximates. Vague "sad song" still gets questions, not a search.

## Layout

```text
lyricomatics/
├── SKILL.md              # contract the agent loads first
├── references/           # on-demand craft, never a bulk read
│   ├── briefing.md
│   ├── room-work.md
│   ├── anti-slop.md
│   └── genres/           # one file per family
└── assets/               # blank brief + lyric sheet
```

Markdown only. No runtime, no plugins. Network is optional, and only when they name a niche the family files cannot cover.

## What it will not do

- Mix, master, or prompt a music generator
- Clone living catalogs (“in the style of” means attitude, not a lift)
- Cosplay a dialect it was not given
- Dump a twelve-item questionnaire
- Tax every happy song with an empty chair

## License

MIT. See [LICENSE](LICENSE) and [NOTICE](NOTICE).

Independent work. Not affiliated with any model vendor or music-generation product.
