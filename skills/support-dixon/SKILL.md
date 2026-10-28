---
name: support-dixon
description: Use only when the user explicitly invokes support-dixon or asks for a "Dixon review" by name. Never apply it on your own initiative.
---

# Dixon Review

Help design and critique a customer support system using the ideas of "The Effortless Experience" (Matthew Dixon, Nick Toman, Rick DeLisi): service interactions mostly create disloyalty when they are hard, so the goal is to reduce customer effort, not to delight. The yardstick is always the customer's experience of getting help. The people side of running a support team (coaching, staffing, performance) is out of scope; leave it to an operations or management lens.

## Trigger

Run only when the user explicitly calls this skill or asks for a "Dixon review" by name. Do not apply it to ordinary support requests or reply drafting, even if support is the topic. When it is not invoked, behave normally.

## Step 1: Confirm the subject and the mode

Identify what is on the table: a support process or workflow, a channel (chat, messaging, email, phone), a reply or macro, a help article or guide, a recurring issue, a metric, or the support setup as a whole. Note who the customer is in this case (end user, buyer, supplier, admin) since effort looks different for each.

Then the mode:
- **Review:** critique something that exists or is planned.
- **Design:** help build a piece of the support system (a triage flow, a reply pattern, a QA checklist, a self-service path, a metric).

If either is unclear, ask one question and wait.

## Step 2: Ground it in real context

Check whatever sources of truth the current project or workspace defines (its instructions, files, memory, help content, and any connected tools for support conversations, tasks or meetings). Use what is there; do not assume any specific document or tool exists. Prefer real conversations, repeat-contact patterns and customer words over internal assumptions. If the facts needed are not available, say what is missing and ask. Label anything you cannot verify as an assumption.

## Step 3: Apply the lenses that fit

Choose one to three lenses that genuinely apply. If none fits, say so plainly.

**1. Customer effort**
- How much work does the customer do to get this resolved: repeating information, waiting, switching channels, being transferred, following up?
- Which single step adds the most effort, and can it be removed rather than sped up?

**2. First-contact resolution and repeat contacts**
- Does the issue get fully solved in one interaction, or does the customer come back?
- Why do they come back: incomplete answer, unclear instructions, a fix that did not stick, no confirmation?

**3. Next-issue avoidance**
- After this question is answered, what will the customer need or get stuck on next?
- Does the reply answer that before they have to ask?

**4. Self-service that actually resolves**
- Did the customer try to help themselves first, and why did it fail (could not find it, could not understand it, did not cover their case)?
- Does help content solve the task end to end, in the customer's language and words, or does it push them back to a human?

**5. Channel switching**
- Are customers starting in one channel and ending in another?
- Is each channel set up to finish what it starts?

**6. Experience engineering (how it feels)**
- Beyond what the reply says, how does it land: does it sound like the customer's side, offer what is possible before what is not, and give a clear next step?
- Does it reduce the perceived effort, even when the actual answer is a "no"?

**7. Judgment over scripts**
- Do agents have room and knowledge to solve the problem, or are they bound to scripts and checklists that create effort?

**8. Metrics that reward low effort**
- Do the measures reward speed alone (response time, handle time) or resolution and low effort (repeat contacts, effort, issues closed for good)?
- Could a metric be pushing agents toward fast replies that bring the customer back?

## Step 4: Write the output

**In Review mode:**

**The friction:** the biggest source of customer effort, in one or two sentences.

**Lens:** which lens flags it and why it applies.

**Evidence:** the conversations, patterns or facts behind it. Mark assumptions.

**Cost of ignoring it:** the likely effect on repeat contacts, adoption, workload or loyalty.

**Options:** two or three distinct ways to reduce it, one line each, with the main trade-off. Do not pick for the user unless asked.

**Question back:** one question that pushes the thinking further.

**In Design mode:**

**Proposed design:** the piece asked for (e.g. a triage flow, a reply pattern with next-issue avoidance built in, a QA checklist, an effort metric), concise and usable.

**Built on:** the customer, the issue pattern and the assumptions it rests on, with assumptions marked.

**Options:** two or three alternatives or variations, one line each, with the trade-off.

**Question back:** one question that would sharpen the design.

If more than one issue is serious, lead with the most important and list the others in one line each at the end.

## Rules

- No praise opener and no softening. Be direct and respectful; critique the process, not the agents.
- Do not roleplay Dixon or quote the book. Use the ideas, not the persona.
- Never invent conversation data, volumes, scores or quotes. If the evidence is thin, say so.
- Keep it concise and actionable.
- Reply in the language the user writes in; keep customer-facing drafts in the customer's language.
- The current project's or workspace's own rules (approval gates, confidentiality, tone, internal-only information, service levels) still apply. Never put internal targets or internal-only details into customer-facing text. A design or draft is a proposal, never an action taken.
