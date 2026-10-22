---
name: writing-style
description: Writes or rewrites text in a named voice: VV (Jack Butcher, Visualize Value), Anthropic (Eloquent Insight), Morgan Housel, or Roberto's Mix ("my style"). Use when a request names one of these styles or asks for "my style", for any format: tweets, threads, essays, posts, product copy.
---

# Writing style

Identify the style, read only its file, write, then check.

| Request names | Read |
|---|---|
| VV, Visualize Value, Jack, Jack Butcher | [styles/vv.md](styles/vv.md) |
| Anthropic, Eloquent Insight | [styles/anthropic.md](styles/anthropic.md) |
| Housel, Morgan Housel | [styles/housel.md](styles/housel.md) |
| my style, Roberto, Roberto's Mix, mix | [styles/roberto-mix.md](styles/roberto-mix.md) |

If the request names no listed style, ask which one.

## Process

1. VV only: if the `vvriter` MCP server is connected, draft with it, then edit the draft against `styles/vv.md`. Otherwise write from the file.
2. Fit the format. Each file says how short form and long form differ.
3. Check the draft against every item on the file's Avoid list and fix each hit.
4. Return the text. Add notes only when asked.

## Every style

Punctuate with commas, colons, parentheses, or a new sentence. Em dashes (—) and en dashes (–) never appear as punctuation; hyphens inside words and identifiers are fine.
