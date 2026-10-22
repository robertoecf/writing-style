# writing-style

An agent skill for writing in specific voices. Works in Claude Code, Codex, and any host that reads `SKILL.md`.

| Style | Say | Profile |
|---|---|---|
| Jack Butcher / Visualize Value | "vv style", "jack style" | Full, plus optional vvriter MCP |
| Anthropic / Eloquent Insight | "anthropic style" | Full |
| Morgan Housel | "housel style" | Partial |
| Roberto's Mix | "my style", "roberto style" | Full: 40% VV, 35% Anthropic, 25% Housel |

Examples: "write a tweet in vv style about leverage", "rewrite this in my style".

## Layout

`SKILL.md` is a short router: it loads, then reads only the file for the requested style from `styles/`. A request pays for one style, not four.

## Install

```bash
mkdir -p ~/.claude/skills/writing-style
cp -R SKILL.md styles ~/.claude/skills/writing-style/
```

Optional VV MCP: `claude mcp add vvriter -- npx vvriter`

## Add an author

1. Create `styles/<author>.md`. Use the sections that apply: voice paragraph, Shape or Structure, Devices (with examples), Tone and themes, Avoid.
2. Add one row to the table in `SKILL.md` and name the author in its `description`.

To finish the Housel profile, collect what VV has: quantified patterns (sentence length, perspective ratio, opening distribution), devices with examples, signature words, and an Avoid list.

## Credits

* Jack Butcher data: [jackbutcher.md](https://github.com/visualizevalue/jackbutcher.md)
* VV MCP: [vvriter](https://github.com/visualizevalue/vvriter)
