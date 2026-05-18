# Subskill: Metadata and Taxonomy

## Purpose

Use this subskill to define how content is described, grouped, found, related, governed, and maintained through metadata and taxonomy.

## Core rule

Metadata and taxonomy should help users find the right content and help owners manage it over time.

## Metadata vs. taxonomy

### Metadata

Structured information about a content item.

Examples:

- Title.
- Summary.
- Content type.
- Audience.
- Owner.
- Department or service area.
- Topic.
- Location.
- Publish date.
- Review date.
- Expiration date.
- Status.
- Language.
- Related service.

### Taxonomy

Controlled categories and relationships used to organize and retrieve content.

Examples:

- Topic categories.
- Service categories.
- Audience groups.
- Locations.
- Departments.
- Content types.
- Lifecycle states.
- Campaign tags.

## Required metadata fields

For strategic governance, most content should have:

| Field | Purpose |
|---|---|
| Title | Identifies the item clearly |
| Description or summary | Helps users and search understand the item |
| Content type | Determines structure and lifecycle |
| Primary audience | Clarifies who the content serves |
| User intent | Clarifies task or question |
| Owner | Assigns responsibility |
| Source of truth | Identifies authoritative information source |
| Topic or service category | Supports browsing and related content |
| Lifecycle state | Supports governance |
| Publish date | Establishes timeline |
| Last reviewed date | Shows maintenance history |
| Next review date | Supports ongoing maintenance |
| Expiration or sunset date | Supports time-limited content |

## Optional metadata fields

Use when relevant:

- Geographic location.
- Eligibility group.
- Related department.
- Related form.
- Related fee.
- Related deadline.
- Event date.
- Campaign name.
- Program name.
- Policy authority.
- Document version.
- Language.
- Redirect target.
- Archive reason.

## Taxonomy design principles

### Use user-centered labels

Prefer labels users recognize over internal jargon.

### Keep categories mutually useful

Categories do not need to be perfectly mutually exclusive, but they should help users make meaningful distinctions.

### Avoid over-tagging

Too many tags reduce usefulness. Apply the smallest useful set.

### Separate departments from topics

Department ownership is not the same as user topic. Capture both only when both are useful.

### Support lifecycle management

Taxonomy should help find content that is stale, ownerless, campaign-specific, or due for review.

## Information architecture placement

When recommending placement, evaluate:

- Primary user task.
- Content type.
- Topic or service area.
- Audience.
- Source of truth.
- Related pages.
- Navigation path.
- Search behavior.
- Ownership.

## Common taxonomy facets

Use these as candidates, not defaults:

| Facet | Use when |
|---|---|
| Topic | Users browse by subject |
| Service | Users need to complete a transaction |
| Audience | Requirements differ by user group |
| Location | Content varies by place or facility |
| Department | Ownership or accountability matters |
| Content type | Users filter by format or function |
| Date | Timeliness matters |
| Lifecycle status | Governance or maintenance matters |
| Campaign | Content belongs to a temporary initiative |

## Metadata quality checks

Good metadata is:

- Accurate.
- Specific.
- Consistent.
- Controlled where needed.
- Useful for both users and maintainers.
- Maintained with the content.

Weak metadata includes:

- Vague titles.
- Duplicative categories.
- Internal acronyms.
- Empty owner fields.
- Missing review dates.
- Tags that do not change findability or governance.

## Output format

Use this table for metadata recommendations:

| Field | Recommendation | Notes |
|---|---|---|
| Title |  |  |
| Summary |  |  |
| Content type |  |  |
| Primary audience |  |  |
| User intent |  |  |
| Topic/category |  |  |
| Service relationship |  |  |
| Owner |  |  |
| Source of truth |  |  |
| Lifecycle state |  |  |
| Review date |  |  |
| Expiration date |  |  |
| Related content |  |  |
| Redirect target |  |  |

## Decision rules

- If users search by task, tag by service or action rather than department only.
- If content is time-limited, require expiration or review metadata.
- If content is authoritative, require owner, source, effective date, and version where applicable.
- If content is duplicated, metadata alone is not enough; recommend merge, redirect, or clarify purpose.
- If a taxonomy term is used only once and has no governance value, question whether it is needed.
