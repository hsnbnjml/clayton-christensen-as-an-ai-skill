# Humans as AI Skills

> Masters are scarce. Their methods are not.

Each folder in this repo packages one expert human's frameworks as a self-contained AI agent skill — a structured, repeatable review process any agent can run. **Not persona chatbots.** No roleplay, no invented quotes. Every skill uses the human's *method*, applied to your actual context.

## The collection

| Skill | Domain | The human | Invoke by |
|-------|--------|-----------|-----------|
| [`strat-clay`](skills/strat-clay/SKILL.md) | Strategy | Clayton Christensen | "Clay review" |
| [`comm-minto`](skills/comm-minto/SKILL.md) | Communication | Barbara Minto | "Minto review" |
| [`cs-murphy`](skills/cs-murphy/SKILL.md) | Customer Success | Lincoln Murphy | "Murphy review" |
| [`proc-kraljic`](skills/proc-kraljic/SKILL.md) | Procurement | Peter Kraljic & Arjan van Weele | "Kraljic review" |
| [`ops-grove`](skills/ops-grove/SKILL.md) | Operations & Management | Andy Grove & Eli Goldratt | "Grove review" |
| [`support-dixon`](skills/support-dixon/SKILL.md) | Customer Support | Matthew Dixon, Nick Toman & Rick DeLisi | "Dixon review" |

**Example:** point an agent at a plan and say *"give me a Clay review of this"* — it picks the 1–3 Christensen lenses that genuinely apply, grounds the critique in your real workspace context, and surfaces the strongest blind spot, what it costs to ignore, and two or three ways to redirect. It will not pick for you unless asked.

## Why "explicit invocation only"

Every skill runs **only when you call it by name**. Ordinary requests stay ordinary — no skill hijacks them. This is built into every file's trigger and description.

## Shared anatomy

All skills follow the same shape:

1. **Trigger** — explicit invocation only
2. **Confirm** the subject and the mode (review / design / learn / plan / coach / advise)
3. **Ground** the work in real context (workspace files, records, connected tools) — mark any unverified claim as an assumption
4. **Lenses** — the frameworks, as numbered test-questions; choose only those that genuinely apply
5. **Structured output** — the finding, the lens that flags it, the evidence, the cost of ignoring it, distinct options with trade-offs, one question back
6. **Rules** — no praise openers, no roleplay, no invented data, concise, reply in the user's language

## Install

```bash
git clone https://github.com/hsnbnjml/humans-as-ai-skills.git
```

Then copy any `skills/<name>/` folder into your agent's skills directory — the `folder/SKILL.md` format works with skill-based agents (OpenCode, Claude, and similar). For plain-LLM use, paste a skill's SKILL.md into custom instructions and adapt the trigger line to your platform.

## Package a human — contribution checklist

1. Pick one human with clearly written frameworks (one anchor author; co-authors allowed in parentheses)
2. Follow the shared anatomy above; name the skill `<domain>-<surname>`
3. The description **must** say: use only when explicitly invoked, never on your own initiative
4. Use the method, not the persona — no roleplay, no invented quotes or data
5. Open a PR with the human added to the table above

## Credits

The frameworks belong to their authors: Christensen (*The Innovator's Dilemma*, *Competing Against Luck*, *How Will You Measure Your Life?*), Minto (*The Pyramid Principle*), Murphy (*Customer Success* with Mehta & Steinman) and the laws of SaaS customer success, Kraljic (*Purchasing Must Become Supply Management*) and van Weele (*Purchasing and Supply Chain Management*), Grove (*High Output Management*) and Goldratt (*The Goal*), Dixon, Toman & DeLisi (*The Effortless Experience*). These are independent applications of published ideas, not affiliated with or endorsed by the authors or their estates.

## License

[MIT](LICENSE)
