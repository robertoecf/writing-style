# writing-style

A Claude Code skill for writing in specific author styles.

## Supported Styles

| Style | Trigger | Status |
|-------|---------|--------|
| **Jack Butcher / VV** | "vv style", "jack style" | Full profile + vvriter MCP |
| **Anthropic / Eloquent Insight** | "anthropic style", "eloquent insight style" | Full profile |
| **Morgan Housel** | "housel style", "morgan housel style" | Partial profile |
| **Roberto's Mix** | "my style", "roberto style" | Full profile (40% VV + 35% Anthropic + 25% Housel) |

## Usage

Say things like:
- "write a tweet in vv style about leverage"
- "write a blog post in anthropic style about AI safety"
- "rewrite this in my style"

## Installation

Copy `SKILL.md` to your Claude Code skills directory:

```bash
mkdir -p ~/.claude/skills/writing-style
cp SKILL.md ~/.claude/skills/writing-style/
```

### Optional: VV MCP integration

```bash
claude mcp add vvriter -- npx vvriter
```

## Adding Authors

See the "How to Add a New Author" section at the bottom of `SKILL.md`.

## Credits

- Jack Butcher style data from [jackbutcher.md](https://github.com/visualizevalue/jackbutcher.md)
- VV MCP tool: [vvriter](https://github.com/visualizevalue/vvriter)
