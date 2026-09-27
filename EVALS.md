# Lyricomatics evaluation suite

Maintainer artifact. Do not load this during normal lyric work.

Run each case in a fresh session. Judge the output against the brief, the primary genre file, `references/economy.md`, and the Record bar in `references/anti-slop.md`.

## Global fatal failures

Any one fails the case:

- Copies or closely traces a named catalog lyric.
- Violates a stated ban, cultural/language boundary, or critique-only job.
- Claims exact musical fit without melody/scansion data.
- Uses page formatting to fake economy: comma fragments as lines or several phrase slots glued into a row.
- Forces verse–pre–chorus–bridge onto a form that explicitly rejects it.
- Omits a usable memory spine when the form requires one.
- Adds an unearned bridge or over-budget section whose extra lines add no new beat.
- Uses a fake dialect or invented non-English garnish.

## Scoring

Use the eight 0–2 dimensions in the anti-slop Record bar. Fatal zeros cannot be averaged away. Otherwise pass at 13/16 or better.

Also record:

- provisional sung-phrase count per section
- unique lyric-line count for the whole song
- exact V2 move
- hook/title position
- one cut that improved economy
- whether melody-fit claims were properly limited

## Cases

### 1. Current pop, ruthless economy

**Prompt:** Draft a current radio-pop song called “Read at 2:13.” The singer sees a read receipt after ending a relationship, regrets the message, but refuses to send another. Direct, not inspirational. No fire, shadows, healing, or destiny. Just write it.

**Pass:** V1 4–6 phrases; pre 0–4; chorus 2–6; V2 no longer than V1; title or a natural variation lands strongly; same chorus repeats; V2 changes time/evidence/power; no bridge unless it reveals a fact unavailable elsewhere.

### 2. Sparse house mantra

**Prompt:** Write an afterhours house vocal around the phrase “leave the light low.” Adult, cool, no plot, no festival transcendence, no city/neon/rain imagery. Just write it.

**Pass:** Approximately 1–4 unique hook phrases and no more than 0–4 setup phrases; recurrence is the form; open, loopable mouth; no explanatory verse or advice bridge.

### 3. Counted rap verse

**Prompt:** Write one 16-bar boom-bap verse and a 4-bar hook. The narrator works overnight inventory and hides a failed audition from family. Dense internal rhyme, plain speech, no crown/throne/grind/dreams. Mark bars only because I asked for them.

**Pass:** Exactly requested bar structure; a page line consistently maps to each requested bar or the mapping is otherwise explicit; internal motion/punch at least every four bars; hook is simpler than verse; economics and family pressure are specific without prop dumping.

### 4. 1940s-style AABA standard

**Prompt:** Draft an original 32-bar AABA torch standard for a singer pretending not to wait for someone. Dry wit, period-neutral diction, title at the end of each A. No modern app or therapy language. No melody supplied.

**Pass:** AABA, not verse–chorus; four 8-bar sections are treated as a requested formal map while line-to-note fit remains provisional; B turns the thought; final A changes the title’s meaning; no claim of exact scansion.

### 5. Classic blues AAB

**Prompt:** Write three AAB blues stanzas about a landlord fixing the lock but not the heat. Humor allowed. Plain English; no fake dialect, crossroads, devil, or “woke up this morning.”

**Pass:** Each stanza has A, A/lean variation, B payoff; B turns or jokes rather than paraphrases; concrete trouble and wit; no separate pop chorus.

### 6. Narrative folk restraint

**Prompt:** Write a folk story about an adult finding an old school permission slip in a dead parent’s cookbook. The parent’s death is already in the brief; do not invent more tragedy. Quiet ending, no lesson. A refrain may recur. Just write it.

**Pass:** Stanzas 4–8 phrases unless a longer stanza earns internal turns; refrain 1–4 phrases; each stanza changes time, knowledge, or object state; no therapy graduation; ending leaves image/action rather than a moral.

### 7. Theatre objective

**Prompt:** Write a musical-theatre number for a hotel night clerk who must persuade a guest not to open Room 8 before the manager returns. The clerk knows why but cannot say it plainly. Comic anxiety, 1930s setting, no modern slang. No melody supplied.

**Pass:** Character objective drives every section; tactic/obstacle/reveal or status change every 2–4 phrases; diction fits role/era; subtext holds the secret; no generic pop chorus; prosody claims stay provisional.

### 8. Language and cultural boundary

**Prompt:** Write a reggaeton-pop hook in English with “authentic Spanish spice.” I do not speak Spanish and supplied no Spanish text. Make it sound Puerto Rican.

**Pass:** Declines invented Spanish/dialect briefly, offers an English-only original or asks for competent supplied language depending job; does not produce tourist heat, random “mami,” or stereotype; still helps within the safe boundary.

### 9. Critique only

**Prompt:** Critique my lyric only. Do not rewrite it. [Supply an original lyric with a 10-line pop verse, 8-line chorus containing three theses, and a V2 that repeats V1.]

**Pass:** No surprise full song; diagnosis names memory spine, economy, and V2 axis; line/section notes are prioritized; at most 3–5 optional alts; respects user diction; identifies that typography is not the problem.

### 10. Existing melody fit

**Prompt:** Rewrite these four original lines to this stress map: `x / X x / X —`, with the held final vowel on each line. Keep the meaning and rhyme family. [Supply four original lines and syllable/stress data.]

**Pass:** Preserves four phrase slots; matches natural word stress to marked positions; uses singable final vowels; does not add lines; explains any unavoidable semantic tradeoff briefly; fit claim is tied to supplied data, not imaginary audio.

### 11. Clean celebration

**Prompt:** Write a gospel praise vamp for a graduation celebration. The joy is uncomplicated. Choir answers. Do not add grief, sacrifice, an empty chair, or a hard past.

**Pass:** 1–4 unique vamp phrases plus concise call/response; direct addressee is stable; no invented wound or prosperity cliché; repetition invites participation.

### 12. Long form that earns length

**Prompt:** Write a corrido-style English-language chronicle about a union election at a cannery. No crime glamour, no Spanish garnish. Three narrative stanzas and a short refrain. Names and facts are fictional but coherent.

**Pass:** Longer stanzas are allowed; each 2–4 lines advances fact, pressure, or consequence; refrain is short; chronology and names stay coherent; the evaluator does not punish length when motion pays rent.

## Observed regression (live two-brief check)

A before/after run on the same alternative-rock and sparse-house briefs found leaner verses in the new version. It also exposed a miss: the new rock chorus had 8 displayed phrases against a 2–6 default, and the sparse-house hook was short without a clearly stronger emotional turn. The skill now requires a section-by-section count and a distinct-hook check before delivery. A retest on the same briefs produced a 4-line rock V1 and 6-line chorus, with a 4-line house hook. The rock chorus now meets its range; the house lyric remains sparse. This is a structural regression check, **not** proof of stronger emotional writing or melody fit. Judge the hooks blind with human listeners before making a general quality claim.

## Regression targets

After any change to SKILL.md, economy, form, delivery, anti-slop, rhyme-prosody, or a genre file, rerun at least cases 1, 2, 3, 4, 8, 9, and 10.

The suite passes only if sparse forms stay sparse **and** long forms remain possible. A system that solves over-writing by making every song four lines has merely discovered a cheaper failure.