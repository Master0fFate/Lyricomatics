# Delivery

The lyric is the product. Your personality is not.

## Sheet

Label sections as the form actually uses them. Do not invent a modern pop skeleton for a two-line mantra, AABA standard, blues stanza, theatre scene, or strophic ballad.

Common labels:

- `[Verse 1]` `[Verse 2]` …
- `[Pre]` or `[Pre-Chorus]`
- `[Chorus]`
- `[Post]`
- `[Bridge]`
- `[Outro]`
- `[Hook]`, `[Refrain]`, `[Vamp]`, `[Break]`, or `[Reprise]` only when the pocket uses them

Put the title once above the first label when a title has been chosen.

Offer the labeled sheet inside one markdown code block (` ```text `). The fence preserves line breaks and gives the user a clean copy target.

### Lineation

One displayed lyric line is one **provisional sung phrase**.

Break a line where at least one of these breaks:

- melodic phrase or supplied phrase slot
- breath group
- rhyme position
- complete thought
- intentional suspension that the next line resolves

Do not break on every comma. Do not make each short clause a decorative row. Do not glue several phrase slots together to make the section look lean. Typography cannot solve over-writing; [economy.md](economy.md) can.

A line can contain internal punctuation. A sentence can cross a line when the suspension is singable and intentional.

Without music, lineation is provisional. With music, the user’s melody, scansion, demo, or bar map wins.

### Spacing

- Label on its own line.
- First lyric on the next line.
- No blank line under a label.
- One blank line between sections.
- Keep repeated-section lineation stable.

Use this shape:

```text
Title

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

Wrong — punctuation confetti pretending to be phrases:

```text
Your cup is cold,
beside the sink,
I wait,
I breathe
```

Wrong — several musical ideas glued into one row:

```text
Your cup is cold beside the sink, the kettle quits before I move, I turn it to the wall
```

Wrong — label glued or separated from its lyric:

```text
[Verse 1] Your cup is cold beside the sink

[Verse 1]

Your cup is cold beside the sink
```

## Repeated sections

Default: print the full repeated chorus so the sheet can be performed without reconstruction.

A compact lead-sheet request may use `[Chorus]` as a return marker after the first full chorus. Do not silently switch formats.

Final-chorus variation should be visible and minimal. If most lines change, it is a new section, not a variation.

## Optional note

One short line after the sheet when useful:

`Form: AABA / title at the end of each A`

or

`Rhyme: verse loose slant / chorus ABAB`

or, only when the user supplied music, asked for counts, or asked for strictness:

`Parity: V1/V2 8-8-7-8, stress aligned, tails matched; hook returns identical`

Skip the note if it adds no practical value. Never print the full grid unasked.

## Alts

A short list. Lines, not songs.

```text
Alts
- [Chorus, L2] original → replacement
- [Verse 2, L4] replacement
```

Three to five swaps maximum. If you need a second full lyric, CAST failed or the user asked for another version.

## Questions

Ask **2–4** only when the answers can change the next pass.

Good: “Does V2 keep the apartment or move to the parking lot?”
Bad: “How does this make you feel?”

For an explicit just-write-it request, omit questions that only reopen the brief.

## Do not

- Wrap the song in a synopsis.
- Offer the sheet unfenced.
- Fake a low line count by gluing phrase slots.
- Fake lyricism by breaking every clause.
- Put a blank line between a label and its lyric.
- Offer production, mix, or generator instructions.
- Quote copyrighted lyrics as a reference block.
- End with a pep talk.

Template: [../assets/lyric-sheet.md](../assets/lyric-sheet.md).