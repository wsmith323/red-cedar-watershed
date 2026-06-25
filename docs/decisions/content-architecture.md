# Content Architecture Decision

## Current decision

Use a template-first approach.

Page-specific narrative content will live directly in Django templates during
the prototype phase. Shared layout belongs in base templates. Repeated
presentation elements belong in reusable includes.

No external content schema will be introduced until actual repetition or
editing pain demonstrates a need for one.

## Rationale

The content model is not yet known. Designing YAML files, database models, or a
CMS now would likely encode assumptions that have not been validated.
