# Hermes worker contract: git

## worker_class
`AUDIT_ONLY_REFERENCE_MIRROR`

## current_job
Maintain correct Hermes metadata for the owned fork without changing upstream Git source as part of organ closure.

## allowed_work
- Verify fork parent/source identity.
- Compare sanitized repository metadata and exact Git object identities.
- Report divergence from `git/git` as reference evidence.
- Search Hermes history for repo-specific donor/vendor/consumer lineage.
- Request sanitized local receipts/DNA for any stronger relation claim.

## execution_contract
- active_runtime_worker: `NOT_APPLICABLE_BY_CLASS`
- return_contract: `METADATA_REPORT_ONLY`
- runtime_authority: `NO`
- canon_authority: `NO`

## forbidden_work
- No source-code mutation merely to satisfy Hermes role closure.
- No raw .mesh, secrets, dumps, prompts, payloads, or archive bodies.
- No runtime truth claims from GitHub.
- No inference that public == donor or fork == vendor organ.
- No rename/delete/prune/reset/rebase/force as organ-fill work.
