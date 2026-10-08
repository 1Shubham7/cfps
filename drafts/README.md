# Drafts

What the `cfp-writer` agent writes, as `drafts/<conference-slug>/<talk-slug>.md`, one commit per draft. Nothing here has been submitted.

When a draft is submitted, move it to `../pending/`, set `outcome: pending` in its frontmatter, and add a line to `../outcomes.md`. The agent does not learn from drafts; it learns from `../selected/`, `../not-selected/` and `../outcomes.md`.
