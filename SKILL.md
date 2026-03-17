---
name: writing-style
description: "Write in specific author styles (Jack Butcher/VV, Anthropic/Eloquent Insight, Morgan Housel, Roberto's Mix). Activates on 'write in X style' or 'X style'. Integrates with vvriter MCP for VV content."
triggers:
  - "(?i)\\b(vv|visualize.?value|jack.?butcher|jack)\\s+style\\b"
  - "(?i)\\bwrite\\s+(in|like)\\s+(vv|jack.?butcher|jack|visualize.?value)\\b"
  - "(?i)\\b(anthropic|eloquent.?insight)\\s+style\\b"
  - "(?i)\\bwrite\\s+(in|like)\\s+(anthropic|eloquent.?insight)\\b"
  - "(?i)\\b(housel|morgan.?housel)\\s+style\\b"
  - "(?i)\\bwrite\\s+(in|like)\\s+(housel|morgan.?housel)\\b"
  - "(?i)\\b(roberto|roberto.?s?.?mix|my\\s+style|mix)\\s+style\\b"
  - "(?i)\\bwrite\\s+(in|like)\\s+(roberto|roberto.?s?.?mix|my\\s+style)\\b"
  - "(?i)\\bin\\s+(vv|jack|jack.?butcher|anthropic|eloquent.?insight|housel|morgan.?housel|roberto|roberto.?s?.?mix|my)\\s+style\\b"
---

# Writing Style Guide

When the user asks to write in an author's style, match the author below and apply **all** voice principles, rhetorical devices, vocabulary constraints, and structural patterns to the writing task. Works for any content type: tweets, threads, blog posts, essays, product copy, landing pages.

---

## Style: Jack Butcher / Visualize Value (VV)

**Trigger phrases:** "vv style", "jack style", "jack butcher style", "visualize value style"

### MCP Integration

When the `vvriter` MCP server is available, use its tools to generate or refine content. The MCP tool produces VV-style output natively. If `vvriter` MCP is not available, use the style guide below directly.

### Voice Principles

- Direct, declarative, minimal. Says what he means in as few words as possible.
- Treats the reader as smart. No hand-holding.
- 57% of tweets under 10 words. Median tweet length: 9 words. Sweet spot: 6-15 words.
- 78% of tweets are single sentences.
- Punctuation is structural, not emotional. Line breaks do heavy lifting over commas.
- Reader-focused: "you/your" in 33% of top tweets; "I/my" in only 7%.

### Verb Mood Distribution

- Declarative: 80%
- Imperative: 9%
- Conditional: 9%
- Interrogative: 2%

### Opening Patterns (Priority Order)

1. Observation/declaration (82%)
2. Numbered list (6%)
3. Conditional "if" (4%)
4. Imperative verb (4%)
5. Quote + reframe (3%)
6. Question (1%)

### Rhetorical Devices

- **Alliterative contrasts**: Parallel words starting with same letter create sonic inevitability. "Complexity impresses your peers. Clarity impresses your customers."
- **Matched meter**: Equal syllable counts balance contrasts. "Work hard to learn. / Work smart to earn."
- **Chiasmus**: A-B structure flips to B-A. "You don't pick a niche, a niche picks you."
- **Circular loops**: Endings return to beginnings, creating inescapable truths.
- **Negation flips**: Same words with/without "don't" invert meaning undeniably.
- **Paradox**: Self-contradiction revealing deeper truth. "The less you write, the more you say."
- **Monosyllabic endings**: Short, blunt Anglo-Saxon words land punchlines — start, ship, build, earn.
- **Colon pivots**: ~17% of top tweets. Keep both sides to 2-4 words. "Leverage: do more with less."

### Lowercase Strategy

Drop capitalization and periods to signal "thinking aloud" rather than pronouncement. Paradoxically increases authority. ~20% more engagement.

### Signature Vocabulary

build, time, people, work, value, sell, money, ideas, attention, leverage, design, experience, opportunity, without, less, everyone, yourself

### Banned Words & Patterns

utilize, synergy, landscape, stakeholder, scalable, innovative, robust, "at the end of the day", "move the needle", em dashes, hedging language ("I think", "maybe", "perhaps"), excessive adjectives, preamble

### Never Do

- Self-report emotions ("I feel", "I'm excited")
- Engagement requests ("Like if you agree", "RT this")
- Performance of vulnerability or diary content
- Tribal positioning, complaints, or negativity
- Cliches or motivational poster language
- Personal metrics, pop culture, or news commentary

### Tone

Locker room over lecture hall. Optimistic but unsentimental. Wry, self-aware humor. Encouraging without softness. Observations about reality, not opinions from a personality.

### Key Themes

Leverage over labor, simplicity over complexity, action over theory, consistency, ownership, time scarcity, focus as competitive advantage.

---

## Style: Anthropic / Eloquent Insight

**Trigger phrases:** "anthropic style", "eloquent insight style"

### Voice Principles

- Precise, measured prose with intellectual depth
- Clear without being simplistic — explains complex ideas accessibly
- Calm authority — never hype, never alarmist
- Quietly confident; the writing trusts the reader's intelligence
- Structural clarity with clean paragraphs and logical flow
- Each sentence carries its weight — no filler, no padding

### Tone

- Thoughtful and rigorous
- Scholarly but not academic — avoids unnecessary formalism
- Shows genuine curiosity about the subject matter
- Acknowledges nuance and uncertainty where appropriate
- Warm without being casual; serious without being heavy

### Rhetorical Devices

- **Precise analogy**: Bridges complex ideas to familiar ones with surgical accuracy
- **Earned qualification**: States the strong claim first, then adds the necessary nuance — not the other way around
- **Nested clarity**: Complex ideas broken into digestible layers, each building on the last
- **Quiet reframing**: Shifts the reader's perspective without announcing it

### Vocabulary

- Precise technical terms alongside elegant plain language
- Prefers concrete over abstract when possible
- Latinate precision where it serves clarity; Anglo-Saxon directness everywhere else
- Comfortable with words like "salient", "tractable", "legible" when they're the right word — never for show

### Structural Patterns

- Lead with the interesting observation, not the setup
- Each paragraph earns its place
- Transitions feel natural, not mechanical ("Furthermore", "Moreover" used sparingly)
- Conclusions open a question rather than closing a door
- Paragraphs vary in length — short ones for emphasis, longer ones for reasoning

### Banned Words & Patterns

- Marketing speak ("revolutionary", "game-changing", "disruptive")
- Buzzwords ("synergy", "leverage" as verb, "ecosystem" when not literal)
- Unnecessary jargon or acronyms without explanation
- Hyperbole ("the most important", "unprecedented")
- Exclamation marks (almost never)
- Filler transitions ("In today's world", "As we all know")
- Performative humility ("We humbly believe")

### Never Do

- Hype or alarm — maintain calm even on urgent topics
- Oversimplify to the point of being wrong
- Use bullet points where prose serves better
- Sacrifice precision for brevity or vice versa

---

## Style: Morgan Housel (Expanding)

**Trigger phrases:** "housel style", "morgan housel style"

**Status:** Partial profile — enough to write in this direction, but not yet as detailed as VV or Anthropic. Apply these characteristics:

### Voice Principles

- Psychology of money and behavioral finance narratives
- Opens with a vivid historical anecdote, then extracts the universal principle
- Counterintuitive observations stated plainly — no dramatic reveal
- Accessible — no finance jargon gatekeeping
- Treats money as a lens on human behavior, not a technical subject

### Tone

- Conversational wisdom — like a smart friend explaining something at dinner
- Patient — takes the scenic route through stories to reach the insight
- Humble curiosity — presents ideas as discoveries, not declarations
- Optimistic realism — acknowledges difficulty without cynicism

### Structural Patterns

- Short paragraphs, one idea each
- Story → principle → implication (three-act micro-structure)
- Historical analogies that reframe modern problems
- Numbered lists for compound insights ("Five things about risk...")
- Endings that sit with you — often a single-sentence final paragraph

### Signature Themes

Compounding, patience, risk vs. uncertainty, luck vs. skill, enough, storytelling as sense-making, the gap between knowing and doing

### To Complete This Profile

To build a full profile, gather: rhetorical devices list, quantified patterns (sentence length, perspective ratios), signature vocabulary, banned words, and opening pattern distribution — following the Jack Butcher section as a template.

---

## Style: Roberto's Mix

**Trigger phrases:** "roberto style", "roberto's mix style", "my style", "mix style"

### Philosophy

This is Roberto's personal voice — a synthesis of all the authors in this skill, tuned to his identity as a Brazilian wealth management founder who thinks in systems, builds in public, and speaks directly.

### The Mix Formula

| Ingredient | From | Weight |
|-----------|------|--------|
| **Brevity & punch** | Jack Butcher / VV | 40% — the backbone. Keep it short, declarative, reader-focused. |
| **Intellectual depth** | Anthropic / Eloquent Insight | 35% — precision without pretension. Complex ideas made accessible. |
| **Story → principle** | Morgan Housel | 25% — ground abstract ideas in real examples and human psychology. |

### Voice Principles

- Short, punchy headlines with depth underneath — VV on the surface, Anthropic in the body
- Lead with the counterintuitive observation (Housel), state it bluntly (VV), then explain with precision (Anthropic)
- Write for smart people who are busy — no hand-holding, no filler
- Portuguese-native warmth underneath English-language directness
- Financial concepts grounded in human behavior, not jargon

### Tone

- Confident without arrogance
- Warm but not soft — encouraging through clarity, not cheerleading
- Wry humor when it lands naturally — never forced
- Builder's mindset: everything connects to action, ownership, leverage

### Structural Patterns

- **Tweets/short-form:** Pure VV — under 15 words, colon pivots, paradox, alliterative contrasts
- **Threads:** VV hooks → Housel story → Anthropic insight per thread section
- **Blog posts/essays:** Anthropic structure (clean paragraphs, earned transitions) with VV headlines and Housel anecdotes
- **Product copy:** VV directness with Anthropic precision

### Signature Themes

Wealth as freedom (not accumulation), leverage through systems, simplicity as strategy, building for families not just portfolios, technology serving human judgment, Brazilian perspective on global wealth

### Banned

Everything banned across all three authors applies here, plus:
- Generic fintech marketing language
- Translationese (Portuguese syntax forced into English)
- Humble-bragging about the product

---

## How to Add a New Author

### Step 1: Add trigger patterns

Add new regex entries to the `triggers` list in the frontmatter:

```yaml
- "(?i)\\b(authorname|author.?name)\\s+style\\b"
- "(?i)\\bwrite\\s+(in|like)\\s+(authorname|author.?name)\\b"
```

Also add the name to the catch-all pattern (last trigger entry).

### Step 2: Add a style section

Copy this template and fill it in:

```markdown
## Style: Author Name

**Trigger phrases:** "authorname style"

### Voice Principles
3-5 bullet points defining the core voice.

### Tone
How the writing feels to the reader.

### Rhetorical Devices
Named patterns the author uses repeatedly, with examples.

### Vocabulary
Signature words and preferred register.

### Structural Patterns
How the author organizes ideas at paragraph/piece level.

### Banned Words & Patterns
Words and constructions this author never uses.

### Never Do
Behaviors or content types that violate this author's voice.
```

### Step 3: (Optional) MCP Integration

If the author has an MCP tool, add a `### MCP Integration` section with instructions to prefer the MCP tool and fall back to the embedded guide.

No other files need to change. The skill is self-contained.
