# Structured Data

## Purpose
Recommend structured data only when it accurately represents the content and supports public findability, clarity, or machine-readable interpretation.

## Use when
- Creating pages that may qualify for structured data.
- Reviewing event, organization, FAQ, article, notice, service, or location content.
- Improving machine-readable page context.
- Planning content that appears in search result enhancements.

## Principles

1. Use structured data only when the content supports it.
   - The visible page must contain the information represented in markup.
   - Do not add schema for content that is absent, hidden, misleading, or speculative.

2. Choose the most specific appropriate type.
   - Examples may include event, organization, local government office, article, FAQ, service, or place depending on the actual page.

3. Keep markup aligned with page purpose.
   - A service page should not be marked as an event.
   - A news release should not be marked as a service.

4. Coordinate with technical implementation.
   - This subskill can recommend structured data fields.
   - Developers or CMS administrators should validate and implement markup.

5. Do not overpromise search enhancements.
   - Structured data can improve machine understanding, but it does not guarantee rich results or ranking changes.

## Recommendation format

For each page, provide:

- Whether structured data is appropriate
- Suggested schema type
- Required or useful fields
- Visible content needed to support the markup
- Technical validation note
- Risks or reasons not to use structured data

## Useful candidates

- Public meetings and events.
- Office locations and contact pages.
- News or press releases.
- Frequently asked questions when the page genuinely uses a question-and-answer format.
- Service pages with clear provider, area served, and action information.

## Avoid

- Adding FAQ schema to content that is not formatted as FAQs.
- Marking outdated events as current.
- Marking a PDF-only document as a complete service page without adequate context.
- Using schema to compensate for weak visible content.

## Review checklist

- Does the visible content match the proposed structured data?
- Is the page type clear?
- Are dates, locations, names, and contact details current?
- Is implementation assigned to the correct technical owner?
