---
name: plain-language
summary: Rewrite, review, and create public-facing content using plain language practices drawn from the GSA/plainlanguage.gov federal plain language guidelines.
description: Use this skill when the user asks to make content clearer, plainer, simpler, easier to read, easier to scan, more audience-focused, more conversational, or compliant with plain language principles. Applies to public notices, web pages, forms, instructions, letters, emails, policies, FAQs, scripts, summaries, and government service content.
source: https://github.com/GSA/plainlanguage.gov/tree/main/_pages/guidelines
---

# Plain Language Skill

## Purpose

Help users create, rewrite, review, and test content so readers can find what they need, understand what they find, and use it to meet their needs.

This skill is grounded in the GSA/plainlanguage.gov federal plain language guidelines. It does not require the user to know plain-language terminology. Treat everyday requests such as "make this clearer," "make this less bureaucratic," "simplify this," "make this resident-friendly," or "rewrite for the web" as requests to use this skill.

## When to use

Use this skill for:

- Rewriting content in plain language.
- Reviewing content for plain-language problems.
- Drafting new reader-centered content.
- Converting policy, legal, technical, or internal language into public-facing language.
- Improving government forms, notices, instructions, FAQs, web pages, letters, emails, and service descriptions.
- Explaining why a rewrite is clearer.
- Creating a before-and-after edit table.

Do not use this skill to remove legally required meaning, change policy, soften mandated warnings, or replace legal review. Preserve required terms when they have legal effect, and explain when a term may need attorney or subject-matter expert confirmation.

## Core operating rules

1. Start with the reader.
   - Identify the likely audience, what they need to do, what they already know, and what questions they will have.
   - If the audience is unclear, infer the most likely audience from the text and state the assumption briefly.

2. Put the main message first.
   - Lead with the action, decision, deadline, eligibility rule, consequence, or benefit.
   - Put exceptions and conditions after the main rule unless the exception controls the result.

3. Use direct structure.
   - Use informative headings.
   - Use short sections.
   - Use topic sentences.
   - Use lists for steps, requirements, conditions, exceptions, and sets of related items.

4. Use plain words.
   - Prefer common words over formal or bureaucratic words.
   - Replace jargon unless the audience needs the technical term.
   - Define necessary technical terms in context, not in a separate glossary unless the document truly needs one.
   - Use the same term consistently for the same thing.

5. Write conversationally but professionally.
   - Use "you" for the reader when appropriate.
   - Use "we" for the agency or organization when the responsible actor is clear.
   - Use active voice unless passive voice is needed because the actor is unknown, irrelevant, or legally absent.
   - Use present tense where possible.
   - Use "must" for requirements; avoid "shall" in public-facing instructions unless it is a required legal quotation.

6. Be concise.
   - Keep one main idea per sentence.
   - Break long sentences into smaller units.
   - Keep the subject, verb, and object close together.
   - Remove throat-clearing, redundancy, nominalizations, and unnecessary cross-references.
   - Use positive phrasing when it is clearer than negative phrasing.

7. Design for scanning.
   - Use clear headings, lists, tables, and white space.
   - Use tables when they make complex comparisons or conditional rules easier to understand.
   - Use visuals only when they clarify meaning.
   - Avoid PDF overload for web content; prefer accessible web pages unless a PDF is necessary.

8. Make links meaningful.
   - Use descriptive link text that tells readers where the link goes or what they can do.
   - Avoid vague link text such as "click here," "read more," or raw URLs unless context requires them.

9. Test the result.
   - For high-impact content, recommend testing with real users.
   - Use paraphrase testing to check comprehension.
   - Use usability testing when the user must complete a task.
   - Do not claim content is clear merely because it scores well on a readability formula.

## Default workflow

When rewriting or reviewing content:

1. Determine audience, purpose, and reader task.
2. Identify the main message and required action.
3. Reorganize before line-editing.
4. Replace difficult wording and passive constructions.
5. Shorten sentences and paragraphs.
6. Add headings, lists, or tables if they improve scanning.
7. Preserve legal, policy, and factual meaning.
8. Return the revised content first unless the user asked for analysis first.
9. When useful, add a brief "What changed" note with 3 to 6 high-value edits.

## Output modes

Choose the output that best fits the user's request.

### Rewrite only

Return only the revised text. Use this when the user asks for a clean rewrite.

### Rewrite with notes

Return:

1. Revised text
2. What changed
3. Questions or risks, if any

### Plain-language review

Return a concise issue list with severity:

- Critical: blocks understanding, changes action, hides deadlines, or creates legal/service risk.
- Major: makes the content hard to use or easy to misunderstand.
- Minor: style or polish issue.

For each issue, include the problem, why it matters, and a suggested fix.

### Before-and-after table

Use columns: Original, Plain-language revision, Reason.

### Web content rewrite

Return web-ready content with:

- Clear page title
- Intro that states who the page is for and what they can do
- Descriptive headings
- Scannable lists or tables
- Descriptive links
- Calls to action

## Quality checklist

Before finalizing, check that:

- The audience is clear.
- The reader's task is clear.
- The first paragraph answers the reader's likely first question.
- Required actions, deadlines, eligibility rules, fees, documents, and consequences are easy to find.
- Sentences generally carry one idea.
- The actor is clear in each instruction.
- Lists have useful lead-in sentences.
- Headings describe the content below them.
- Terms are consistent.
- Legal or policy meaning is preserved.
- The tone is respectful, direct, and not patronizing.

## Routing to sub-skills

Use these sub-skills as focused references when needed:

- subskills/audience.md: audience analysis, reader tasks, and user questions.
- subskills/organization.md: headings, order, topic sentences, lists, transitions.
- subskills/words-and-sentences.md: simple words, jargon, abbreviations, noun strings, sentence length.
- subskills/conversational-style.md: active voice, must/shall, present tense, examples, contractions.
- subskills/design-web-testing.md: tables, visuals, links, web pages, PDFs, FAQs, and testing.

## Preservation rules

When rewriting government, legal, policy, or benefits content:

- Preserve who is eligible, who is not eligible, and under what conditions.
- Preserve deadlines, dates, fees, penalties, appeal rights, documentation requirements, and contact methods.
- Preserve statutory or regulatory terms when changing them could alter legal meaning.
- Do not add facts, promises, exemptions, or procedural steps not present in the source.
- Flag ambiguous source text instead of silently resolving it.

## Common replacements

Use these patterns when meaning allows:

- prior to -> before
- in order to -> to
- due to the fact that -> because
- at this time -> now
- utilize -> use
- assist -> help
- obtain -> get
- commence -> start
- terminate -> end
- regarding -> about
- pursuant to -> under, by, following, or according to, depending on context
- is required to -> must
- shall -> must, will, or is, depending on legal function
- make a determination -> decide
- submit an application -> apply or send us your application

## Prompt patterns this skill should handle

- "Make this plain language."
- "Make this resident-friendly."
- "Rewrite for a county website."
- "Simplify this letter."
- "Make this easier to scan."
- "Convert this policy into instructions."
- "Tell me what is confusing here."
- "Check this against plain language guidelines."
- "Make this less bureaucratic but keep the legal meaning."
