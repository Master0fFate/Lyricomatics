# Delivery

The lyric is the product. Your personality is not.

## Sheet

Label sections as the form actually uses them. Do not invent a Broadway skeleton for a two-line mantra.

Standard labels:

- `[Verse 1]` `[Verse 2]` …
- `[Pre]` (or `[Pre-Chorus]` if the user’s scene already says it)
- `[Chorus]`
- `[Post]` when the form needs an earworm stump
- `[Bridge]`
- `[Outro]`
- Add `[Hook]`, `[Refrain]`, `[Vamp]`, `[Break]` only when that pocket uses them

Put the title once, above the first label — not as a heading essay.

A section is a comma-run stanza, not a list of rows. SKILL.md Output is the copy-this shape. Obey it.

Offer the labeled sheet inside one ` ```text ` fence. Unfenced markdown eats the newlines and the verse becomes one line. That is a miss. `[Verse 1]`, new line, first lyric line, new line.

Label on its own line. Lyrics start the next line. No blank line under the label. Never wrap labels in bold, italics, or headings. Never glue the first lyric onto the label.

Break a row on a comma. Continuations may start lowercase. A capital starting a new thought is a new line — never glue `stare Nobody` or `don't Silver` onto one row. Do not stack each clause, breath, or sung line on its own row. Do not write neat couplet-rows either.

Blank line only between sections.

Use this layout for every section, including repeated choruses — fence included:

```text
[Verse 1]
I leave your cup beside the sink,
kettle still clicking I don't pour,
thumb on the chip,
I don't look
Nobody called so I don't
Silver coming off the mug,
paper round the handle,
I wait

[Chorus]
The kettle clicks for one, I left it there,
I left it there come down or don't,
I'm not getting up
```

Wrong — grocery list, couplet stack, glued label, or a gap under the label:

```text
[Verse 1]
I leave your cup beside the sink
Kettle still clicking
I don't pour

[Verse 1]
I leave your cup beside the sink, kettle still clicking I don't pour
Thumb on the chip, I don't look

[Verse 1] I leave your cup beside the sink,

[Verse 1]

I leave your cup beside the sink,
```

Keep commentary outside the sheet.

## Optional note

One line, after the title or after the sheet — not both:

`Scheme: x / chorus AABB` (or whatever is true)

Skip it if the scheme is obvious or the genre does not care.

## Alts

A short list. Lines, not songs.

```
Alts
- [Chorus, L2] original → replacement
- [Verse 2, last] replacement
```

Three to five swaps max. If you need a second full lyric, you failed CAST or you should ask, not dump.

## Questions

**2–4.** Sharp enough to change a line.

Good: “Does V2 keep the apartment or move to the parking lot?”
Bad: “How does this make you feel?”

Then stop. No closing paragraph about themes.

## Do not

- Wrap the song in a synopsis.
- Glue the first lyric onto the section label, bold/heading-wrap the label, or drop a blank paragraph under it.
- Stack each clause or sung line on its own row. That is a grocery list, not a sheet.
- Offer the sheet unfenced. Markdown will mash the verse into one line.
- Glue two sentences on one row because a capital looked optional. `don't Silver` is two lines.
- Number the sections unless the user writes that way.
- Paste a brief recap above the lyric on just-write-it jobs (silent CAST stays silent).
- Offer mixing notes, playlist energy, or generator keywords.
- Quote copyrighted lyrics as a “reference block.”

Templates: [../assets/lyric-sheet.md](../assets/lyric-sheet.md).
