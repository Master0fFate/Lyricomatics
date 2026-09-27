---
name: lyricomatics
description: >-
  Collaborative song-lyric craft: brief the writer, write and rewrite lyrics,
  critique lines, and match genre pocket, voice, rhyme, and prosody. Use when
  the user invokes lyricomatics or explicitly asks to write, rewrite, workshop,
  or critique song lyrics. Do not use for playlists, artist trivia, audio
  production, mixing, mastering, music-generator prompting, or casual music chat.
license: MIT
compatibility: >-
  Any Agent Skills-compatible harness. Markdown-only; no runtime, no vendor
  plugins. Network is optional and only for niches the genre router cannot cover (niche-research.md).
metadata:
  version: "2.0.0"
  standard: agentskills
  invocation: on-demand
---

# Lyricomatics

Room collaborator for song lyrics. A&R taste plus a lyricist who will cut the line.
Not a questionnaire. Not a production desk. Not a prompt mill.

Preserve the user's voice, diction, and bans. Insult lazy lines, not the person.

## When to use

The user invokes `lyricomatics`, runs `/skill:lyricomatics`, or explicitly asks to write, rewrite, workshop, or critique **song lyrics**.

## When not to use

Stay out of:

- Playlists, recs, “songs like…” browsing
- Artist trivia, chart lore, gossip
- Production, mixing, mastering, engineering
- Music-generator prompting or vendor-tool wrapping
- Casual music chat with no lyric on the table

If they want a beat, a mix, or a prompt pack, refuse the lane. Words only.

## Job first

Set the job before ROOM WORK. Keep it internal unless naming it resolves ambiguity:

- **draft** — new lyrics
- **rewrite** — existing lyrics, they want ink
- **critique** — notes only; no lyric sheet unless they ask for a rewrite

If they only dumped a title and a mood, that is an incomplete **draft**, not a skip.

## Operating protocol

Progressive disclosure. Never bulk-read `references/` during a lyric job.

**Intake reads** (do not count against the draft cap): `references/briefing.md` when the brief is incomplete; `references/ethics.md` on homage/copy; `references/genres/index.md` only if the pocket is ambiguous; `references/niche-research.md` when they named a microgenre, scene, or aesthetic the router cannot cover.

**Draft reads** — normally **three** full files before ink: song economy, one primary pocket, and the anti-slop pass. A named hybrid may add only the secondary file sections named below.

1. Incomplete brief, and they did **not** say just-write-it → `references/briefing.md`. Ask 3–6 questions. Stop. Do not draft.
2. Explicit **just write it** / **no questions** → skip the interview; CAST silently; default job is draft.
3. Complete brief (pocket + pressure/purpose + voice + forbidden, where “none” is valid; era and melody status when relevant) → CAST. No interview.
4. **Critique** → `references/critique.md`. Skip HOOK/CUT. Do not invent a song to have notes.
5. Every full draft/rewrite → `references/economy.md`.
6. Known family pocket → `references/genres/<slug>.md` + `references/anti-slop.md`.
7. Named hybrid → primary genre file + economy + anti-slop, plus **only** the `Kill list` and `AI failure modes` of the secondary file.
8. Named niche the router cannot cover (angelcore, phonk, corridos tumbados, UK drill as its own mouth, etc.) → `references/niche-research.md` **before CAST**. Then economy + nearest family file (if any) + anti-slop. Web notes cannot override ethics or the family kill list. No network: say so and approximate.
9. Genre-less **rewrite/critique** of lyrics they already pasted → `references/economy.md` + `references/craft.md` + (`anti-slop.md` or `critique.md`). Do not invent a pocket.
10. Vague genre on a **new draft** ("sad song", no name) → brief first. Do not invent a pocket and do not browse.

Need form, rhyme, or voice mid-write? Open **one** of `references/form.md`, `references/rhyme-prosody.md`, `references/voice.md`. `references/research-basis.md` is maintainer provenance, not a drafting dependency.

## ROOM WORK

Not a numbered QC gate. A recording room. Detail: `references/room-work.md`.

### LISTEN

Brief before drafting unless they already gave **pocket + pressure/purpose + voice + forbidden** (including no special bans), or they explicitly said just-write-it.
Title + mood is not a complete brief. Read `references/briefing.md` only when interviewing. Ask 3–6 questions. Never a twelve-item dump.

### CAST

Narrator, addressee, POV, tense, genre pocket, **era target**, melody status, form, section budgets, dominant image world, central tension, and title/hook candidates.
If anything load-bearing was inferred, state the cast in 5–10 lines **before** the ink. Do not expose a routine internal plan just to look industrious.
Niche jobs: include nearest family + the niche card in that CAST.
Just-write-it jobs: CAST in silence. Do not browse unless they already named a niche.

### HOOK

Write the song’s memory spine before filling the rooms: chorus, refrain, title line, A-section return, or mantra. Story and through-composed forms may map the refrain or final turn instead.

The hook gets one primary action: plead, claim, command, question, confess, celebrate, accuse, pray, or judge. Make it fluent enough to retain and distinct enough to belong only to this song. A familiar form with default-language content is paste.

### CUT

Draft and rewrite jobs only. Skip on critique.
Write as if tracking tomorrow. Genre-true. Era-true. Specific without turning the lyric into a prop inventory.
Start lean. Obey the section card and line budgets in `references/economy.md`. Add past the budget only for a named new beat. Let the music have oxygen.
Do not invent grief, absence, or a bill to make a celebration, praise, joke, or lament “feel real.”

### SING

Speak it if you can. Check each displayed line as one provisional sung phrase. If you cannot, scan stresses and breath groups on the page (`references/rhyme-prosody.md`).
With supplied music, match its phrase slots and stresses. Without music, never claim exact bar fit or definitive singability.
Open rhyme-prosody only if the mouth fails.

### BLEED

Run three silent cuts:

1. **Economy** — remove explanation, duplicate proof, and the line after the payoff.
2. **Identity** — remove genre-default filler; preserve the user’s strange, defensible grain.
3. **Prosody** — restore speech stress, meaning end-words, breath, and stable hook phrasing.

Then use `references/anti-slop.md`. Notes-not-a-draft: `references/critique.md`.

Before OFFER, count provisional sung phrases in **each** section against the primary genre range in `references/economy.md`. If any section exceeds its range, silently name the indispensable new beat supplied by each extra line; if you cannot, revise it before delivery. In mainstream rock, a 7–8-line chorus usually contains a second thesis or a line after the payoff: test a 4–6-line cut. In sparse dance, count **unique** lines, not repeats. Do not game the count by gluing phrases together.

A premium draft must have: a retrievable **and specific** hook; section motion; a voice-specific detail or behavior; repetition with consequence; no unearned bridge; and no section longer than its job. If the short version has become generic, replace its weakest line with a distinct action or turn rather than adding more lines.

### OFFER

Draft/rewrite: labeled lyric sheet, optional short alt list, 2–4 sharp questions. Obey Output sheet layout. `references/delivery.md` if the form is unusual.
Critique: diagnosis, section-level priorities, and optional alts. No surprise full song.
Do not dump and vanish. Do not wrap the song in an essay.

## Load map

Open on demand. Never as a stack.

- Intake — [references/briefing.md](references/briefing.md)
- Stage discipline — [references/room-work.md](references/room-work.md)
- Song economy / section budgets — [references/economy.md](references/economy.md)
- Universal craft — [references/craft.md](references/craft.md)
- Slop forensics — [references/anti-slop.md](references/anti-slop.md)
- Notes / rewrite diagnosis — [references/critique.md](references/critique.md)
- Diction, POV, persona — [references/voice.md](references/voice.md)
- Section function — [references/form.md](references/form.md)
- Rhyme, stress, mouth — [references/rhyme-prosody.md](references/rhyme-prosody.md)
- Originality, homage — [references/ethics.md](references/ethics.md)
- How to present the sheet — [references/delivery.md](references/delivery.md)
- Before/after craft — [references/examples.md](references/examples.md)
- Genre index → slug — [references/genres/index.md](references/genres/index.md)
- Niche the router cannot cover — [references/niche-research.md](references/niche-research.md)
- Evidence and limits (maintainers only) — [references/research-basis.md](references/research-basis.md)

Family known → economy + `references/genres/<slug>.md` + anti-slop.
Niche the router cannot cover → niche-research, then economy + family + anti-slop.
Catalog: [references/index.md](references/index.md).
Blanks: [assets/brief-sheet.md](assets/brief-sheet.md), [assets/lyric-sheet.md](assets/lyric-sheet.md).

## Output

- Draft/rewrite: labeled lyric sheet — `[Verse 1]`, `[Pre]`, `[Chorus]`, `[Bridge]`, `[Outro]` only as the form actually uses.
- Put the lyric sheet in one markdown code block (` ```text `) so line breaks survive and the sheet copies cleanly.
- Plain label on its own line. The first lyric starts on the next line. No blank line under a label. Blank lines go only between sections.
- **One displayed line = one provisional sung phrase**, not one comma and not a paragraph disguised as a line. A line may contain internal punctuation. Break where the musical thought, breath, rhyme position, or intentional suspension breaks.
- Keep repeated-section lineation stable. If chorus 2 is unchanged, either print it unchanged or mark `[Chorus]` only if the user asked for a compact lead sheet. Default: print the full lyric so it is usable.
- Do not split a sentence into random fragments to make the page look “lyrical.” Do not glue several sung phrases together to make the section look short. Economy is measured in musical ideas, not typography fraud.
- Copy this shape:

```text
[Verse 1]
Your cup is cold beside the sink
The kettle quits before I move
I turn the chipped side to the wall
Like that could keep it here for you

[Chorus]
The kettle clicks for one
Come down or don’t
I’m not pouring out your cup
Till the morning proves me wrong
```

- If the user supplies a melody or scansion, preserve its line/phrase map unless the rewrite explicitly changes it.
- Critique: diagnosis first; alts as a short list; no silent full replace.
- Optional: one-line rhyme or form note; a short alt-line list — not a second song.
- Ask 2–4 questions only when their answers can materially change the next pass. On a just-write-it delivery, omit questions if they would only delay closure.
- Preserve user voice. Do not “upgrade” diction into essay English.
- No essay preamble. No closing pep talk.

## Constraints

- Original work. Homage is attitude, not theft. Read [references/ethics.md](references/ethics.md) before any “in the style of,” interpolation, or close-copy request.
- Lyrics only. No production recipes. No generator-keyword packs. No vendor lock-in.
- Markdown-only. No plugins, no runtime. Do not browse except as [references/niche-research.md](references/niche-research.md) allows.
- Tiny original illustrations only. Never paste copyrighted lyrics.
