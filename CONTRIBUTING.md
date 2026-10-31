# Contributing to Crustates

Thanks for helping build Crustates. This guide applies to every repository in
the org. The monorepo's
[CONTRIBUTING.md](https://github.com/crustates/crustates/blob/development/CONTRIBUTING.md)
adds the branch model, the release flow and how to propose bigger changes.

## Before you start

- For anything bigger than a small fix, open an issue or discussion first so we
  can agree on the approach.
- Be kind. Everyone here follows our [Code of Conduct](CODE_OF_CONDUCT.md).
- Found a security issue? Don't open an issue; follow [SECURITY.md](SECURITY.md).

## How we work

- **Setting up:** each repository's README explains how to set it up.
- **Commits:** use [Conventional Commits](https://www.conventionalcommits.org)
  (`feat(tide): add VM snapshots`, `fix(reef): ...`). The changelog is
  generated from them.
- **Sign-off:** we use the [Developer Certificate of Origin](https://developercertificate.org).
  Sign every commit with `git commit -s`.
- **Pull requests:** keep them small and focused. They are squash-merged, so
  write the title as a Conventional Commit.
- **Dependencies:** mention new dependencies and why you need them in your pull
  request.

## Pull request checklist

- [ ] Linked to an issue, or explains the problem it solves
- [ ] Tests added or updated
- [ ] Docs updated for user-facing changes
- [ ] The repository's checks pass locally
- [ ] Commits signed off

## Licence

By contributing, you agree that your contributions are licensed under the
same licence as the repository you're contributing to. See that repository's
`LICENSE` file.
