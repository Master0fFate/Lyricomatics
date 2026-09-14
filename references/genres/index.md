# Genre pockets

One file is a contract for the mouth, not a tour of music history.
If the lane is known, load **one** slug plus `references/anti-slop.md`. Do not stack pockets. Do not invent a lane to avoid asking.

Unknown genre → brief first. Guessing a pocket and dumping a song is malpractice.

## Router

User signal → file. Match the lyric job, not the Spotify shelf.

| If they say, mean, or imply | Load |
| --- | --- |
| rap, bars, 16s, boom-bap, trap, drill, punchlines, story rap, conscious rap, abstract rap | `hip-hop.md` |
| radio pop, dance-pop, pre-chorus lift, post-chorus earworm, top-line hook | `pop.md` |
| R&B, soul, neo-soul, quiet-storm, bedroom confession, runs around a spare hook | `rnb.md` |
| country, americana, honky-tonk, bar-top proverb, small-town ledger | `country.md` |
| rock, classic rock, arena, indie rock, art-rock, guitar-band lyric (not pit/shout) | `rock.md` |
| metal, metalcore clean/harsh split, black/death posture, concept-doom | `metal.md` |
| folk, singer-songwriter, acoustic diary, coffeehouse monologue, strophic story | `folk.md` |
| blues, AAB, 12-bar complaint, juke confession, devil-at-the-crossroads talk | `blues.md` |
| jazz vocal, standard, AABA, torch, swing wit, vocalese-to-a-tune | `jazz.md` |
| musical theatre, want-song, charm song, reprise, character objective in a room | `theatre.md` |
| gospel, testimony, praise, choir vamp, altar call | `gospel.md` |
| reggae, lover’s rock, dancehall, deejay toast, riddim chant | `caribbean.md` |
| Afrobeats, amapiano, softlife, log-drum space, dance-cue English | `afro.md` |
| reggaeton, urbano, regional Mexican, corrido, salsa, bachata, banda, norteño | `latin.md` |
| K-pop, J-pop, idol concept, English hook for a bilingual track | `east-asia.md` |
| house, EDM peak vocal, club mantra, trip-hop, downtempo fragment | `electronic.md` |
| punk, hardcore, d-beat shout, slogan chorus, indictment in one breath | `punk.md` |

If two rows fire, do not merge files. Pick a **primary** by which section must survive a drunk sing-along or a cold read.

## Ambiguous signals

- “Soulful pop” → `rnb.md` if the hook wants caress/accusation and air for runs; `pop.md` if the chorus must land on first listen as a text you send.
- “Indie” alone is not a pocket. Bedroom confession with ugly stresses → `folk.md`. Band throat, shirt-print chorus, elliptical image → `rock.md`. Shoutable indictment → `punk.md`.
- “Alternative” is a marketing fog. Ask throat and enemy, then route.
- “Christian” is not gospel. Testimony/choir/vamp → `gospel.md`. Radio love-song with holy nouns swapped in is still `pop.md` and usually a bad idea.
- “Rap-sung R&B” → primary `rnb.md` unless bars are the product; then `hip-hop.md` and steal R&B kill-list items (Pinterest chorus, advice-nouns).
- “Country-rap / trap-soul / hyperpop” → hybrid protocol below. Do not hunt a missing slug.
- “Musical” meaning theatrical plot → `theatre.md`. “Musical” meaning they want it to sound pretty → still ask form.
- Spanish or bilingual club heat is not automatically `latin.md`. Confirm lane. English pop with decorative “mami” is `pop.md` failing ethics.
- Jamaican or pan-Caribbean “vibe” without register source → `caribbean.md` and refuse costume dialect.
- “K-pop English” is `east-asia.md` even if the hook sounds like dance-pop. The sectional and phonology rules differ.

## How to pick primary

Ask, silently if they said just-write-it:

1. What is the chorus *for*? Claim, chant, caress, complaint, want, testimony, mantra, slogan.
2. How much air does the mouth need? Packed bars, radio line, spare groove, shout chunk, loop phrase.
3. Whose diction? Street week, idol concept, character in a room, congregation, dance floor, kitchen table.

The file that answers those three without translation is primary.

## Hybrids

Primary pocket owns form, rhyme pressure, pocket/mouth, POV, and hook.
Secondary pocket donates its **kill list** and its **AI failure modes** only.

Examples of the split:

- Country-trap: `country.md` form and proper-noun ethics; `hip-hop.md` kill list (throne, empty city drops, therapy-rap). Do not fake both dialects at once.
- Pop-punk: `punk.md` if the chorus must be yelled; `pop.md` if it must be belted cute. Secondary kill list either way.
- Gospel-R&B: `gospel.md` if God is addressee or the vamp is the song; else `rnb.md` and run gospel’s kill list (baby→Jesus swap).
- Folktronica: `folk.md` diary rules + `electronic.md` kill list (do not novelize a loop; do not tidy the ending into a sermon).
- Reggaeton-pop: `latin.md` primary if dembow mouth and coro matter; `pop.md` kill list so it does not become an empowerment bullet list.
- Drill-electronic: `hip-hop.md` primary; `electronic.md` kill list so you do not write six unique dense sections over a mantra job.

Never average the two rhyme pressures. Never write a “both” voice. If the brief cannot name a primary, ask one question and stop.

## Load discipline

- One **primary** genre file. Not a sampler platter.
- Named hybrid: you may also read **only** the secondary file’s `## Kill list` and `## AI failure modes`. Do not load the rest of the secondary pocket.
- Do not open this index after the slug is known unless the lane changed mid-session.
- Sub-lane inside a file is a dial, not a second read.
- Production words (tempo as law, mix, sound-design nouns) are out of pocket. Ignore them as lyric instructions.

## If nothing matches

Do not invent `references/genres/other.md`.

They named a **niche, scene, or aesthetic** (angelcore, phonk, corridos tumbados, UK drill as its own mouth): leave this index. Read [../niche-research.md](../niche-research.md). Map a nearest slug if you can. Browse only as that file allows. Family kill list still wins.

They said a mood with no name ("sad song", "something dark"): brief first. Do not browse.

Closest-slug heuristics when you must approximate without a niche name:

- Story with a zip code and a job → `country.md` or `folk.md` (job/economy vs diary shame).
- Slogan and an enemy → `punk.md`.
- Loop sentence for a floor → `electronic.md`.
- Character wants something *in this room* → `theatre.md`.
- Bars that have to survive a cipher → `hip-hop.md`.

## What these files refuse

Discography as proof. BPM-as-morality. Generator keywords. Copyrighted lines as models. Fake fluency in a language or dialect the brief did not supply. Sacred or narrative traditions treated as costume.

Read the slug. Obey its never-do. Then write as if someone has to sing it tomorrow without shame.
