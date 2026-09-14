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

Give each section label its own line, followed by a blank line, then the lyrics. The blank line keeps the label and first lyric separate when Markdown renders; a single source newline can collapse into a space. Never wrap labels in bold, italics, or headings. Use this layout for every section, including repeated choruses:

```text
[Verse 1]

I leave your cup beside the sink.

[Chorus]

The kettle clicks for one.
```

Wrong — these render as one mashed line:

```text
[Verse 1] Same slow circle, same assigned height

**[Verse 1]**
Same slow circle, same assigned height
```

Keep a blank line between sections, too. Keep commentary outside the sheet.

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
- Glue the first lyric onto the section label, or bold/heading-wrap the label.
- Number the sections unless the user writes that way.
- Paste a brief recap above the lyric on just-write-it jobs (silent CAST stays silent).
- Offer mixing notes, playlist energy, or generator keywords.
- Quote copyrighted lyrics as a “reference block.”

Templates: [../assets/lyric-sheet.md](../assets/lyric-sheet.md).
