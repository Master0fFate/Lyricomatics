# Flow parity

Open when a repeated section does not sing the same twice, when the user supplied music or asked for strict counts, or when a genre file sets a dial you need to apply.

The rule itself is short enough to live in SKILL.md. This file is how to count, how to fix, and where each pocket turns the rule down.

## The problem this solves

A melody is a grid of slots. Verse 2 sings the tune verse 1 taught. Every chorus return sings the chorus tune. Every A in an AABA sings the A tune.

If line 3 of verse 2 carries two more syllables than line 3 of verse 1, the singer has one move: cram them in as faster notes, or swallow a word. If it carries two fewer, they hold a note nobody wrote or add a filler *oh*. Either way the vocal rhythm lurches. The listener hears the singer fighting the song. Across a whole verse, those lurches read as the singer changing tempo.

That is not a performance problem. It is a lyric problem. Fix it on the page.

## The default rule

Applies unless the primary genre file says otherwise.

**Pair** every line with its partner: V1 line n with V2 line n, chorus return with first chorus, pre with pre, A with A, stanza with stanza, hook anchor with hook anchor.

For each pair:

1. **Syllables match.** Same count of sung syllables. Verse pairs may differ by one syllable only at the pickup (before the first stress) or the tail (after the last stress). Hook and chorus returns match exactly.
2. **Stresses match.** Same number of stressed syllables, in the same positions. This outranks the raw syllable count. Six syllables with stress on 2 and 5 are not a pair for six syllables with stress on 1 and 4.
3. **Endings match.** A line ending on a stressed syllable pairs with a line ending on a stressed syllable. A line ending on an unstressed tail pairs with a tail. *Stay* and *leaving* do not share a slot.
4. **Pickups match.** If the template line opens on an unstressed word before the first beat, its partner does too.
5. **Breath matches.** Paired lines break for breath in the same place, or nowhere.
6. **Held vowels match** where the dial says so. On a sung hook, the vowel on the longest or highest note keeps the same colour every return. Open stays open. Close stays close.

Counting vowels is counting syllables. One vowel sound per sung syllable. Vowel letters do not matter; *queue* is one, *idea* is three.

## The four dials

Genre files set one dial for verse pairs and one for hook returns. A file that sets nothing inherits the default.

| Dial | Syllables | Stress | Endings and pickups | Held vowels |
|---|---|---|---|---|
| **strict** | exact | exact positions | exact | match on every held or hit slot |
| **tight** | exact, or one extra only at pickup or tail | exact positions | match | match on the longest note |
| **loose** | stress count exact; unstressed syllables may float by up to two | same count, positions may shift inside a beat | match at the end of the line | match where a note is clearly held |
| **off** | no paired melody to protect | speech stress still rules | — | — |

**Default:** verse pairs **tight**, hook and chorus returns **strict**. A pocket that never says its dial gets this.

**Off** is a formal fact, not a mood. It applies where the music does not repeat: through-composed theatre, a rap verse where the flow is the design, a trip-hop fragment that never returns, a mawwal or improvised intro. Even then the song's hook keeps its own dial. A rap verse with the dial off still owes bar parity (below).

Loosening the dial is a genre decision made in the genre file, or an explicit user decision. Never loosen it mid-draft because the line you liked did not fit. Change the line.

Linguists who study how words sit on reused tunes call this positional parallelism: the same tune keeps the same per-line syllable count. French and Spanish song almost never break it. English song breaks it often, because English lets unstressed syllables crowd or thin between beats. That is why the **loose** dial exists for English talk-sung verses, and why it does not exist for a chorus.

## When two rules fight

Priority, top wins:

1. Stressed syllables sit on strong beats. Never mis-stress a meaning word to save a count.
2. No gap where the tune has a note. Do not leave a slot the singer must fill with air or a filler.
3. No cramming. Do not make the singer subdivide a note to fit extra syllables.
4. Line ends where the phrase ends. A clause that spills past the melodic phrase forces a false breath.

If honouring 1 breaks 3, rewrite the line until both hold. The list ranks damage. It is not permission to keep the lower one broken.

## Count sung syllables, not dictionary syllables

Count the way the singer will say it, then write it so the singer knows.

- Contractions count as written. *I'm* is one, *I am* is two. Use them to buy or spend a syllable.
- Elision is legal and must be marked: *ev'ry*, *'bout*, *'round*, *prob'ly*. Spell the elision on the sheet. Do not write *every* and hope.
- Diphthongs are one: *day*, *go*, *time*, *now*.
- *Fire*, *hour*, *our*, *real*, *poem* are one or two depending on the mouth. Decide once per song and keep it.
- *-ed* is a syllable only after *t* or *d*: *waited* two, *walked* one.
- *-ion*, *-ious*, *-ial* are one: *motion* two, *serious* three.
- Numbers and initials count as spoken: *3 a.m.* is four.
- Non-English: count in that language's sung convention. Spanish and Portuguese verse count to the last stressed syllable and merge adjacent vowels across words. French counts a final mute *e* before a consonant and drops it before a vowel or at the line end. Do not apply English rules to a language you are not writing.

Stress: content words carry it, function words do not unless the sense contrasts them. Two-syllable nouns usually stress the first syllable, two-syllable verbs the second. Compounds hit the first half: *HALL light*, *BACK door*. Words ending in *-ly* and *-ity* are where writers misplace stress most. If a word has to be mis-stressed to fit, the slot is wrong, not the word.

A three-syllable word never goes in a two-syllable slot. No speed bumps: if the singer would trip reading it once at tempo, the line is not finished.

Breath falls where speech breathes. Never mid-word, never between a noun and the word that modifies it.

## The parity grid

Build it for every section that returns. Do it silently unless the user asked for counts or supplied music.

Write each line as a stress skeleton. Capital for a stressed syllable, lowercase for unstressed, a bar for a breath.

```text
V1 L1  your CUP is COLD be SIDE the SINK        8   xXxXxXxX
V2 L1  the KET tle's STILL on YOUR side NOW     8   xXxXxXxX
```

Pass. Same count, same stress positions, both end stressed.

```text
V1 L2  the KET tle QUITS be FORE i MOVE         8   xXxXxXxX
V2 L2  i TOLD my SIS ter YOU were ON ly TRAV el LING   12
```

Fail. Four extra syllables, two extra stresses, unstressed tail against a stressed end. The singer will rush the middle and split the last note. Rewrite the line, not the melody.

The first full statement of a section is the **template**. Partners match the template. If the template is clumsy, fix the template first, then re-pair everything. Do not patch partners to a bad template.

If V2 keeps coming out longer, draft V2 first. It usually carries more facts. Then write V1 to its skeleton.

Topline rooms call the same discipline melodic math: each line mirrors the syllable count of the line it answers, and the melody is written before the words. Honour the mirror even when no melody exists yet.

Repeat for hook returns. A chorus printed three times should produce three identical skeletons. A final-chorus variation changes words inside the same skeleton.

## Bar parity for rap and toasting

Where the dial is **off** for syllables, the grid still exists. It is the bar.

- Within one flow pattern, syllables per bar stay in a narrow band. A bar that doubles its load mid-pattern is a flow switch, and a switch is a decision, not an accident.
- Rhyme lands on the same beat position bar after bar until the pattern changes. End-hits that wander off the four read as a stumble, not swagger.
- Switches happen at seams: every four bars, at the hook, at a new camera. Announce a switch in CAST. Keep the new pattern as consistently as the old one.
- The hook is **strict**. A chant that gains a syllable on its second return is not a chant.
- Drill and grime end-hits: same clipped consonant family on the fence, same beat.

A dense verse is legal. A verse where no two bars share a shape is not dense. It is unwritten.

## Held vowels

Vowel families for parity purposes:

- **Open:** ah, aw, oh, ay, eye, ow — *stay, go, mine, call, now, saw*
- **Close:** ee, oo — *me, you, free, true*
- **Short:** ih, eh, uh, a as in *cat* — *sit, left, love, back*

On a sung hook the longest note wants an open vowel, and that slot wants the same family on every return. Swapping *stay* for *leave* on the hold changes the colour the singer has learned and the harmony stacked on it. Swap inside the family, or keep the word.

Short vowels and consonant clusters belong on fast slots. Shouted pockets flip this: match the hit, not the hold. A punk chant wants the same hard end on the same beat; a drill hook wants the same clipped consonant on the fence.

**Full vowel parity** means every stressed slot keeps its family across the pair, not only the hold. Children's song, chant, dream pop, worship, and any brief that asked for it use this. Everyone else matches the hold and leaves the rest to sense.

## Fixing a line without losing it

Gain or lose a syllable without changing what the line means. In rough order of preference:

1. Contract or expand: *I'm / I am*, *don't / do not*, *'cause / because*, *till / until*, *'round / around*.
2. Drop or add a function word the ear does not need: *that*, *the*, *just*, *so*, *then*.
3. Swap a synonym by count: *leave / go*, *kitchen / room*, *telephone / phone*.
4. Change the verb form: *walked / was walking*, *keep / am keeping*.
5. Swap a name for a pronoun or back.
6. Move the adverb or cut the adjective.
7. Rewrite the line in speech order with the same meaning word at the fence.

Never:

- Pad with *oh*, *yeah*, *baby*, *girl* unless the pocket uses them as architecture and every partner line has one in the same slot.
- Invert syntax to hit the count. Yoda is still a kill.
- Glue a clause on to reach the number.
- Mis-stress a word and call it syncopation.
- Change the template to fit the one partner you could not fix.

## With and without music

**Music supplied:** the demo, scansion, or phrase map is law. Notes per phrase is the syllable budget. Melisma exists only where the demo has it. Pickups and holds are where the demo puts them. Report the grid in one line if the user asked for fit.

**No music:** parity still applies, because whatever melody arrives will be repeated. Build the grid from the template line. State in OFFER that fit is provisional. Do not claim bar counts you did not test.

**Melody-first briefs:** topline camps write syllables to a tune before words exist. Honour the given syllable and stress map exactly. Sense bends to the slot there, not the reverse.

## Deliberate breaks

A break is legal when it is a decision with a job:

- Final chorus adds a tag line after the last return. The returns themselves still match.
- V2 switches to a double-time or half-time flow at a seam, and the brief or CAST names it.
- A list song extends one item for the joke, once, on the last item.
- A spoken aside sits outside the grid and is labelled as such.

A break is a stumble when nobody can say what it is for.

## Reporting

Default: silent. The grid is your work, not the user's reading.

Print a one-line note after the sheet only when the user supplied music, asked for counts, or asked for strictness:

```text
Parity: V1/V2 8-8-7-8, stress aligned, tails matched; hook returns identical.
```

If a slot could not be matched without wrecking the sense, say which slot and why in one clause. Do not hide it.

## Tiny tests

- Read V1 and V2 aloud to the same made-up tune. Did you stumble, rush, or hold anywhere?
- Do all chorus returns produce one skeleton?
- Does every held note keep its vowel family?
- Did you fix a partner by breaking the template?
- Did you loosen the dial because the line was pretty?

Mouth, rhyme type, and end-words: [rhyme-prosody.md](rhyme-prosody.md). Section budgets: [economy.md](economy.md). Pocket dials: `genres/<slug>.md`.
