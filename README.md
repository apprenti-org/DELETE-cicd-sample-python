# DELETE-cicd-sample-python

> ⚠️ **DO NOT USE.** This repo was created in error on 2026-04-27 and should be deleted by a user with `delete_repo` scope.

## Why this exists

This repo was provisioned as starter code for the `cicd-pipeline-concepts` course but **violated the canonical `[slug]-student` naming convention** documented in `apprenti-org/design-documentation:curricula-design/design-process-documentation/deployment-process.md` (line 344). Per that spec, student-side starter code lives at `apprenti-org/[slug]-student` — for cicd that's `apprenti-org/cicd-pipeline-concepts-student`.

The contents of this repo were re-pushed to the canonical location. This `DELETE-` prefixed copy is an artifact pending manual deletion.

## What to do instead

Use the canonical repo: **https://github.com/apprenti-org/cicd-pipeline-concepts-student**

## Deletion plan

Any apprenti-org admin can delete this repo via:
- GitHub UI: Settings → General → Danger Zone → Delete this repository
- `gh repo delete apprenti-org/DELETE-cicd-sample-python` (requires `delete_repo` scope: `gh auth refresh -h github.com -s delete_repo`)

## References

- Audit META: `apprenti-org/design-documentation#256`
- Spec: `apprenti-org/design-documentation:curricula-design/design-process-documentation/deployment-process.md` line 344
