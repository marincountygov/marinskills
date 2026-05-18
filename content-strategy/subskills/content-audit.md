# Subskill: Content Audit

## Purpose

Use this subskill to evaluate existing content and recommend whether to keep, revise, merge, split, move, redirect, archive, or delete it.

## Core rule

Audit content against user need, strategic purpose, accuracy, findability, ownership, performance, and maintenance burden. Do not audit only for style.

## Audit dimensions

### User value

Evaluate whether the content serves a real user task or question.

Questions:

- Who needs this?
- What task does it support?
- What would users lose if it were removed?

### Accuracy and currency

Evaluate whether the content is correct and up to date.

Questions:

- Is the information current?
- Is the owner known?
- Is there a source of truth?
- Are dates, fees, contacts, links, and requirements current?

### Duplication and overlap

Evaluate whether the content duplicates or conflicts with other content.

Questions:

- Does another page answer the same need better?
- Are there conflicting versions?
- Should items be merged or redirected?

### Findability

Evaluate whether users can locate and recognize the content.

Questions:

- Is the title clear?
- Does the content appear in the right place?
- Are search terms, metadata, and taxonomy appropriate?
- Are related pages linked appropriately?

### Purpose and fit

Evaluate whether the content type and placement match the purpose.

Questions:

- Is this a service page, guide, news item, policy, alert, event, directory, or document?
- Is the content in the right channel?
- Is it public, internal, archival, or campaign-specific?

### Performance

Evaluate how users interact with the content.

Possible signals:

- Page views.
- Search queries.
- Click-throughs.
- Form starts and completions.
- Downloads.
- Support contacts.
- Feedback.
- Bounce or exit patterns.
- Broken links.

### Risk and maintenance burden

Evaluate the consequence of keeping inaccurate or unmanaged content.

Questions:

- Could stale content cause service failure, legal risk, safety risk, or public confusion?
- Is maintenance effort justified by user value?
- Is the content owner still available?

## Recommendation labels

### Keep

Use when the content is useful, accurate, findable, owned, and aligned.

### Revise

Use when the content is still needed but needs updates, restructuring, plain-language editing, metadata, or ownership fixes.

### Merge

Use when multiple items serve the same or overlapping intent.

### Split

Use when one item serves unrelated audiences, tasks, or purposes.

### Move

Use when the content is valid but belongs in a different section, channel, or content type.

### Redirect

Use when an old URL or item should point users to a better current source.

### Archive

Use when content is no longer active but should remain available for reference, records, transparency, or historical context.

### Delete

Use when content has no user value, no current purpose, no retention need identified by the responsible authority, and no meaningful traffic or dependency.

## Audit inventory fields

Use these fields when building an audit table:

| Field | Description |
|---|---|
| URL or item ID | Where the content lives |
| Title | Current title |
| Content type | Current or recommended type |
| Owner | Responsible person or unit |
| Audience | Primary audience |
| Purpose | Primary content purpose |
| Lifecycle state | Proposed, published, stale, archived, etc. |
| Last reviewed | Known review date |
| Accuracy | Current, partly current, inaccurate, unknown |
| Duplicate or overlap | Related content conflicts |
| Performance signal | Analytics or qualitative signal |
| Risk | Low, medium, high |
| Recommendation | Keep, revise, merge, split, move, redirect, archive, delete |
| Priority | Low, medium, high |
| Next action | Specific action needed |

## Scoring model

Use a simple 1 to 3 score when useful.

| Dimension | 1 | 2 | 3 |
|---|---|---|---|
| User value | Low or unclear | Moderate | High |
| Accuracy | Unknown or inaccurate | Partly current | Current |
| Findability | Hard to find | Somewhat findable | Easy to find |
| Ownership | Unknown | Shared or unclear | Clear owner |
| Strategic fit | Weak | Partial | Strong |
| Maintenance risk | High | Moderate | Low |

Interpretation:

- High value + low accuracy: prioritize revision.
- Low value + high maintenance burden: consider archive or delete.
- Duplicate high-value content: merge and redirect.
- Unknown owner + high-risk content: escalate before publication or continued reliance.

## Audit summary output

Use this format:

| Recommendation | Count | Rationale | Next step |
|---|---:|---|---|
| Keep |  |  |  |
| Revise |  |  |  |
| Merge |  |  |  |
| Split |  |  |  |
| Move |  |  |  |
| Redirect |  |  |  |
| Archive |  |  |  |
| Delete |  |  |  |

## Decision rules

- Do not delete content solely because it has low traffic; first determine whether it serves a critical low-volume need.
- Do not keep content solely because it has high traffic; high traffic may indicate confusion or dependency.
- Do not archive content that users still need for active tasks.
- Do not merge content with different primary audiences unless the combined page can still serve each audience clearly.
- Flag legal, records, privacy, or policy retention questions for the responsible authority.
