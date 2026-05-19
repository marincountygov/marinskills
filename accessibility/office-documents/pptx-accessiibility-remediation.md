---
name: pptx-accessibility-remediation
description: Review and safely remediate PowerPoint slide decks against County of Marin presentation template, brand, accessibility, and plain-language expectations.
extends:
  - accessibility/core
  - brand-standards
  - plain-language
default_standard: WCAG 2.2 Level AA
content_types:
  - pptx
  - potx
  - slide decks
status: proof-of-concept
---

# PPTX Accessibility and Brand Remediation Skill

Use this skill when a user uploads a PowerPoint deck and asks for review, remediation, publication readiness, accessibility improvement, or County template alignment.

## Primary output

Return:
1. a remediated copy of the deck when safe automatic changes are possible;
2. a remediation report;
3. a manual testing checklist.

## Safe automatic corrections

Apply only low-risk corrections that preserve meaning:
- set missing document metadata when derivable from existing content;
- repair title placeholders when visible title text already exists;
- apply approved County theme/layout defaults when content is compatible;
- normalize editable body text to approved font family;
- flag or adjust text below minimum size only when layout remains safe;
- mark clearly decorative template artifacts as decorative where supported;
- repair reading order for standard placeholder-based slides;
- convert raw URLs to existing nearby descriptive text when unambiguous.

## Do not silently change

Do not silently:
- invent alt text for meaningful images;
- rewrite legal, policy, budget, emergency, or public-meeting content;
- recreate, redraw, crop, recolor, or improvise logos;
- claim full accessibility compliance;
- validate exported PDF accessibility;
- delete slides unless the user requested deletion.

## Required report language

State reviewed scope, unreviewed scope, target standard, automatic corrections, recommended remediations, required manual testing, and any County brand or governance escalation.
