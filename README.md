# Red Cedar Awareness Site

A discussion prototype for a public educational website about Lake Menomin,
Tainter Lake, and the Red Cedar River watershed.

The initial goal is to translate and organize publicly available research,
plans, progress reports, and organizational work into a form that ordinary
residents can understand.

## Current status

This repository is intentionally a skeleton. It contains:

- project vision and editorial constraints;
- a proposed site outline;
- placeholders for research outputs;
- a Django-oriented template structure;
- an initial Codex prompt for planning the site.

The first substantive step should be to populate `docs/research/` with the
results of a Deep Research project and then run the prompt in
`prompts/initial-codex-prompt.md`.

## Intended technical direction

- Django
- Django templates
- shallow template inheritance
- page-specific content in templates initially
- reusable includes only where repetition is demonstrated
- minimal JavaScript
- optional HTMX for progressive disclosure
- no CMS, REST API, React, or generalized page builder in the first version
