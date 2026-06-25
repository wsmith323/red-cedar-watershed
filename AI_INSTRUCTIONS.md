# AGENTS.md

## Project purpose

This repository contains a discussion prototype for a public educational
website about Lake Menomin, Tainter Lake, and the Red Cedar River watershed.

The site should help ordinary residents understand:

- why the lakes experience harmful algae blooms;
- where phosphorus comes from;
- what organizations are already doing;
- what solutions are technically available;
- what progress has been documented;
- what remains unknown or unresolved.

## Editorial requirements

- Prefer primary, official, and peer-reviewed sources.
- Cite every substantive quantitative or causal claim.
- Preserve the distinction between measured data, modeled estimates,
  organization-reported accomplishments, interpretation, and open questions.
- Include dates with figures where practical.
- Attribute work and accomplishments to the organizations that performed or
  reported them.
- Use plain language without distorting the science.
- Avoid anti-farmer framing and avoid assigning personal blame.
- Do not imply organizational endorsement without explicit approval.
- Do not silently reconcile conflicting sources.
- Do not invent missing values, quotations, timelines, or conclusions.
- Mark uncertainty explicitly.

## Technical requirements

- Use Django templates with shallow inheritance.
- Keep page-specific narrative content in templates initially.
- Use reusable includes only where genuine repetition exists.
- Do not introduce YAML content files, a CMS, database-backed page content,
  a REST API, React, or a generalized page builder unless explicitly requested.
- Use minimal JavaScript.
- HTMX may be used only for progressive disclosure or similarly focused
  interactions.
- Favor accessible, semantic HTML.
- Keep visualizations simple, sourced, and clearly labeled.
- Treat the site as a discussion prototype rather than a finished publication.

## Python style

- Use single quotes for literal strings where practical.
- Format Python as Black would, except preserve single quotes.
- Use a line length of 120.
- Sort imports as isort would using the Black profile and a line length of 120.
