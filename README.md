# cicd-sample-python

A small Python project used as the **course-provided sample repository** for the **CI/CD Pipeline Concepts** course (Operations Support Specialist curriculum).

This repo's purpose is to give learners a working Python codebase to clone and extend across lessons L1 through L8: branch protection, GitHub Actions workflows, multi-stage pipelines, environments and secrets, deployment strategies, and tag-based releases.

## What's in this repo

- A small Python module (`src/sample/calculator.py`) with `add`, `subtract`, and `multiply` functions
- A `tests/` directory with passing `pytest` tests
- A `pyproject.toml` configured for `python -m build --wheel`
- A baseline `.github/workflows/hello.yml` (minimal `test` job) — used in **Lesson 1** to populate the branch-protection status-check picker
- A tag-triggered `.github/workflows/deploy.yml` — used in **Lesson 8** for the tag-deploy-rollback exercise
- An initial `v0.1.0` tag

## Lessons that use this repo

| Lesson | What you do |
|---|---|
| L1 | Configure branch protection on a fork of this repo |
| L2 | Author your first `.github/workflows/build.yml` |
| L3 | Extend `build.yml` with a `test` job and dependency caching |
| L4 | Refactor `build.yml` into multiple jobs with `needs:` |
| L5 | Configure a `staging` environment with a secret and reviewer |
| L6 | Add a status badge and required status checks |
| L8 | Tag a release, deploy via `deploy.yml`, and roll back |

L9 (Capstone) uses a separate fresh sample repo: `apprenti-org/cicd-capstone-python`.

## Quick start

```bash
git clone https://github.com/<your-username>/cicd-sample-python.git
cd cicd-sample-python
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
pytest
```

All tests should pass.

## License

MIT.
