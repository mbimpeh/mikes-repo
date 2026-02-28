# Quality checklist

Before merge/release:

- [ ] CI passes (HTML validation, accessibility, link check).
- [ ] No open critical/high bugs for this scope.
- [ ] README/docs updated if needed.
- [ ] CHANGELOG updated for user-facing changes.

Code/content:
- [ ] HTML valid; required attributes present.
- [ ] Links work; no broken or placeholder URLs in commit.
- [ ] No secrets or sensitive data committed.

New features:
- [ ] Acceptance criteria in issue or PR.
- [ ] Happy path verified; edge cases or follow-up tests captured.
