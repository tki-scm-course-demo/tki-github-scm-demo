# TKI SCM Course Demo

> Educational GitHub collaboration demonstration inspired by the *Trusted Knowledge Ingestion Layer for Enterprise RAG* project.
>
> This is a standalone, illustrative teaching sample. It is **not** the original TKI source code, does not connect to a real backend, and must not be represented as a verified production feature.

## Purpose

Demonstrate software configuration management with Git and GitHub: repository creation, commits, branch isolation, pull requests, review, merge, and commit history.

## Contents

- `index.html` — static presentation of a sample document-ingestion lifecycle.
- `style.css` — styling for the static demonstration page.
- `demo-data/sample-documents.json` — invented demonstration data.
- `docs/team-guide.md` — shared rules for a three-member GitHub workflow.

## Start locally

Double-click `index.html` to open it in a browser, or open this folder in VS Code and preview locally.

## Video roles

- **Thai (`NQThai-7803`)**: coordinator and reviewer.
- **T.Thinh (`thinh26194`)**: organization/repository setup, initial commit, permissions.
- **P.Thinh (`ThinhNguyennnnnn`)**: create a feature branch, edit the page, push, open a pull request.

## GitHub demonstration plan

1. T.Thinh creates an organization and a new public repository (after safety check).
2. T.Thinh adds this sample and makes the first commit to `main`.
3. T.Thinh grants permissions and shares the repository URL.
4. P.Thinh clones the repository and creates `feature/update-ingestion-ui`.
5. P.Thinh changes the heading `<h1>` in `index.html` from `TKI - Demo Workflow` to `TKI - GitHub Collaboration Demo` and updates the sample workflow card description.
6. P.Thinh commits and pushes his branch; opens a pull request into `main`.
7. Thai or T.Thinh actually reviews it; after successful review, merge the PR into `main`.
8. Verify the updated page and GitHub commit/PR history.

Only the public demo repository is changed. Never use the real subproject's Git remote, history, tokens or database.
