# Plain Language Skill

A reusable AI Skill for plain-language writing, rewriting, review, and web-content improvement.

Source: GSA/plainlanguage.gov guidelines at https://github.com/GSA/plainlanguage.gov/tree/main/_pages/guidelines

## Files

- `SKILL.md` - Core skill and routing instructions
- `subskills/audience.md` - Audience and reader-task analysis
- `subskills/organization.md` - Headings, ordering, lists, and task structure
- `subskills/words-and-sentences.md` - Word choice, jargon, hidden verbs, sentence clarity
- `subskills/conversational-style.md` - Active voice, must/shall, direct tone, examples
- `subskills/design-web-testing.md` - Web writing, links, PDFs, tables, testing

## Suggested install pattern

Place the `plain-language-skill` folder where your AI runtime expects skills. Keep the folder intact so the core `SKILL.md` can route to the sub-skills.

## Notes

This skill preserves legal and policy meaning. It should flag unclear legal or policy text rather than inventing interpretations.
