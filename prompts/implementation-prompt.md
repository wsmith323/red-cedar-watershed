# Implementation Prompt

Read `AGENTS.md`, all documents under `docs/`, and the approved
`docs/content-plan.md`.

Implement the approved content plan as a Django template-based discussion
prototype.

Constraints:

- Use Django templates with shallow inheritance.
- Keep page-specific narrative content directly in templates for now.
- Use reusable includes only where genuine repetition exists.
- Do not introduce YAML, a CMS, database-backed page content, a REST API, React,
  or a generalized page builder.
- Use minimal JavaScript.
- HTMX may be used only where progressive disclosure materially helps visitors.
- Include visible citations for substantive claims.
- Clearly distinguish documented findings, modeled estimates, reported
  accomplishments, interpretations, and open questions.
- Include a prominent discussion-prototype disclaimer.
- Credit the organizations whose work is represented.
- Use no more than four simple, sourced visualizations.
- Optimize for accessibility, responsive layout, and ordinary readers.
- Do not make the site look endorsed by any organization.

Before coding, create `docs/implementation-plan.md`. Then implement the site and
run all available tests and checks.
