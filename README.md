# CFPs

Every talk proposal I have submitted, sorted by what happened to it. The `cfp-writer` agent in [1Shubham7/agents](https://github.com/1Shubham7/agents) reads this repo before it writes a new proposal, so the sort is its training data: `selected/` shows the shape that works, `not-selected/` shows what did not, and `outcomes.md` says why I think so.

## Layout

- `selected/`: accepted somewhere. One file per proposal, text exactly as submitted.
- `not-selected/`: submitted and rejected everywhere it went.
- `pending/`: submitted, no result recorded yet. Also holds older proposals whose result I have not written down.
- `drafts/<conference-slug>/<talk-slug>.md`: what the agent writes. Not submitted yet.
- `outcomes.md`: one line per submission with the result and my view of why. The agent reads all of it.

## Lifecycle

1. The agent writes `drafts/<conference-slug>/<talk-slug>.md` and commits it.
2. I edit it, submit it, move the file to `pending/`, and add a line to `outcomes.md`.
3. When the result comes, I move the file to `selected/` or `not-selected/`, set `outcome:` in its frontmatter, and write the why line in `outcomes.md`.

A proposal sent to several conferences lives in one file; `outcomes.md` carries the per-conference results. It belongs in `selected/` as soon as it is accepted anywhere.

## Frontmatter

```yaml
---
title: "Exact title as submitted"
outcome: accepted | rejected | waitlisted | pending | unknown | draft
conferences: [Conference Name Year, ...]
format: Lightning talk (10 min)
field: engineering | compliance | open source | platform | community
speaker: I | we
---
```

Then the submission text under the headings the form used. Keep the text as submitted; this is the record of what reviewers saw.
