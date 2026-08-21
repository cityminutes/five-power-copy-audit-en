# Five-Power Copy Audit

An English Codex Skill for evaluating commercial copy to advertising-agency pitch standards. It turns subjective feedback into calibrated scores, a concise creative-director critique, and a concrete next revision.

Its central question is simple:

> Can this copy help the client win business in a competitive market?

## What it evaluates

| Dimension | Core question |
| --- | --- |
| Business Power | Can the strategy, value proposition, proof, and CTA drive a commercial result? |
| Reasoning Power | Do the structure, logic, and information design complete the persuasion? |
| Empathy Power | Does the copy understand the audience and create an appropriate emotional connection? |
| Innovation Power | Does the idea have a distinctive angle and memorable creative assets? |
| Word Power | Are the vocabulary, syntax, rhythm, and voice precise and persuasive? |

Each dimension receives a 1–10 score calibrated against professional agency standards:

- **9–10 — Exceptional:** distinctly competitive work; 10 is reserved for extremely rare, mature execution.
- **7–8 — Professional:** meets agency review standards and needs only focused refinement.
- **5–6 — Competent draft:** the core idea works but still requires senior revision.
- **1–4 — Needs development:** material strategy or execution flaws limit commercial effectiveness.

## What it produces

```text
Five-Power Copy Audit
Business Power: 7 / 10
Reasoning Power: 6 / 10
Empathy Power: 8 / 10
Innovation Power: 6 / 10
Word Power: 7 / 10

Creative Director's Note
[Strongest quality, biggest gap, and one actionable revision]
```

After five samples in one round, the Skill reports average scores and identifies the best-supported writer profile: Writer, Seller, Scholar, Veteran, Beginner, or Hybrid.

## Good use cases

- Reviewing ads, social posts, landing pages, and brand content
- Running a quality check before a client presentation
- Comparing headlines, variants, or creative routes
- Identifying a writer's recurring strengths and blind spots
- Turning “something feels off” into clear, actionable criteria

## Installation

Download or clone this repository into your Codex skills directory:

```bash
git clone https://github.com/cityminutes/five-power-copy-audit-en.git ~/.codex/skills/five-power-copy-audit-en
```

Then invoke it in Codex:

```text
Use $five-power-copy-audit-en to audit the copy below.

Audience: first-time small-business founders
Channel: Instagram ad
Business objective: book a free consultation

[Paste copy]
```

Supplying the audience, channel, and business objective produces a more context-aware audit. When context is missing, the Skill states its assumptions instead of inventing product evidence.

## Design principles

- Adjust criterion weight to the format; do not judge a headline as if it were a complete sales page.
- Do not reward length, information volume, or decorative language by default.
- Calibrate scores with observable evidence from the copy.
- Provide concise conclusions and actionable guidance without exposing private chain-of-thought.

## Repository structure

```text
five-power-copy-audit-en/
├── SKILL.md              # Triggers, workflow, and output contract
├── agents/openai.yaml    # Codex interface metadata and default prompt
└── references/rubric.md  # Five-dimension rubric and scoring anchors
```

## Traditional Chinese edition

For Traditional Chinese commercial copy, use [5力文案健檢](https://github.com/cityminutes/five-power-copy-audit-zh).
