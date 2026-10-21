# Workflow rules for the TKI GitHub SCM demo

This is a **course sample**, not the production TKI repository.

## Accounts

| Person | GitHub login | Responsibility |
|---|---|---|
| Thai | NQThai-7803 | Coordinate and review |
| T.Thinh | thinh26194 | Set up the organization/repository and initial commit |
| P.Thinh | ThinhNguyennnnnn | Feature branch and pull request |

## Proposed names

- Organization username (check availability): `tki-scm-course-demo`
- Organization display name: `Trusted Knowledge Ingestion Layer for Enterprise RAG`
- Repository: `tki-github-scm-demo` (Public)
- Default branch: `main`
- Feature branch: `feature/update-ingestion-ui`

## Handoff A: T.Thinh -> P.Thinh

- Organization and repository exist and are accessible.
- Initial commit is on `main`.
- The repository URL is shared with everyone.
- P.Thinh has repository Write access and has accepted the invitation.
- No uncommitted changes are expected on `main`.

## Handoff B: P.Thinh -> reviewer

- A feature branch is pushed to GitHub.
- A PR targets `main` and displays the expected changes.
- Thai or T.Thinh reviews the PR from their own account.
- On approval, merge and check the updated page and commit history.

## Sample commands

```powershell
git clone https://github.com/tki-scm-course-demo/tki-github-scm-demo.git
cd tki-github-scm-demo
git switch -c feature/update-ingestion-ui
# Edit index.html in VS Code
git add index.html
git commit -m "docs: refine TKI demo workflow page"
git push -u origin feature/update-ingestion-ui
```

Do not run clone before the remote repository has been created.
Do not invent a successful review or merge; verify it in the GitHub UI.
