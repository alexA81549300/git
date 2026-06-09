# Hermes worker next: git

## next_worker_rule
Use existing local Hermes evidence first.

## allowed_work
- Summarize existing receipt labels.
- Open issues with metadata-only tasks.
- Review repo structure against local truth labels.
- Request sanitized local proof from Hermes Private AI.

## forbidden_work
- No raw .mesh.
- No secrets.
- No dumps.
- No prompts.
- No archive contents.
- No runtime truth claims from GitHub alone.
- No rename/delete/prune/reset/rebase/force.
