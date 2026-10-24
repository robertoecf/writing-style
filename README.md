# writing-style

My writing voice as an agent skill, plus the author profiles and the process behind it.

Only one skill gets installed: [`skills/writing-style`](skills/writing-style/SKILL.md). It writes in my voice, picks a register (VV, Anthropic or Housel) by format, field and goal, and has an email voice calibrated from my own sent mail. The author profiles in [`authors/`](authors/) are source material, not skills.

## Install

Copy the skill folder into your host's skills directory:

```bash
cp -R skills/writing-style ~/.claude/skills/   # Claude Code
cp -R skills/writing-style ~/.agents/skills/   # Codex and other hosts that read ~/.agents
```

Then ask for text "in my style", or ask for a post, thread, essay, copy or email.

## Layout

| Path | What it is |
|---|---|
| `skills/writing-style/SKILL.md` | The installed skill: my voice, registers (email included), sentence rules, Avoid list |
| `authors/vv.md` | Jack Butcher / Visualize Value: full profile, quantified from his tweets |
| `authors/anthropic.md` | Anthropic / Eloquent Insight: full profile |
| `authors/housel.md` | Morgan Housel: partial profile |

## How I built it

1. **Profile the writers you want to sound like.** For each one: voice, shape (numbers when you have data), named devices with real examples, tone, themes, and an Avoid list. VV is quantified from [jackbutcher.md](https://github.com/visualizevalue/jackbutcher.md): sentence length, mood, openings, perspective.
2. **Weight them.** Mine: 40% VV (brevity, the backbone), 35% Anthropic (precision), 25% Housel (story, then principle).
3. **Add what is only yours.** Identity, themes, and hard rules. My sentence rules (one idea per sentence, one term per concept, no em or en dashes) come from my global agent instructions.
4. **Calibrate against what you actually wrote.** The profiles describe who I want to sound like; my archive shows how I write. I measured eight years of my sent work email on my own machine: openings, closings, sentence length, punctuation, pronouns, recurring phrases, and how I structure a recommendation. Only aggregate counts and a few anonymized excerpts left the machine, and none of it is in this repo. That pass added the email register, the moves that hold in every format (explain each thing by its job, use the reader's numbers, disagree with a reason), and loosened three rules my real writing contradicts (exclamation marks in email greetings, flagging an opinion once, longer sentences in email).
5. **Distill into one voice.** Turn each author into a register and map context to the lead register: format, field, goal. Keep only lines that change the output; state the target first and keep the Avoid list short.
6. **Test, then review adversarially.** Run the same prompts with and without the skill, check that it triggers only when it should, and compare its emails against real ones. Two external reviewers then check rule preservation, token cost and triggering before merge.

## Make your own

1. Fork this repo.
2. Replace or add profiles in `authors/`, using `authors/vv.md` as the template.
3. Rewrite `skills/writing-style/SKILL.md`: your identity, your weights, your context table, your sentence rules, your Avoid list. Keep the frontmatter `description` quoted and naming the formats you write.
4. Calibrate: run the same counts over your own sent email or published posts, locally, and fix every rule your real writing contradicts.
5. Keep the skill around 1,200 words or less. The author files can be as long as you want: they are never loaded.

## Credits

* Jack Butcher data: [jackbutcher.md](https://github.com/visualizevalue/jackbutcher.md)
* VV MCP, for pure VV drafts: [vvriter](https://github.com/visualizevalue/vvriter) (`claude mcp add vvriter -- pnpm dlx vvriter`)
