# Contributing to Crustates

Thanks for helping build an open, European cloud. This guide covers how we work
and what we expect in a pull request.

## Before you start

- For anything bigger than a small fix, open an issue or discussion first so we
  can agree on the approach.
- Be kind. Everyone here follows our [Code of Conduct](CODE_OF_CONDUCT.md).
- Found a security issue? Don't open an issue; follow [SECURITY.md](SECURITY.md).

## Setting up

Each repository's README explains how to set it up.

## How we work

- **Branches:** `development` is the integration branch and the default; branch
  from it (`feat/<topic>`, `fix/<topic>`, `chore/<topic>`, `docs/<topic>`,
  `refactor/<topic>`) and open a pull request back into it. `main` holds
  released code only; only `development` and `hotfix/*` may merge into it.
  Keep pull requests small and focused.
- **Commits:** use [Conventional Commits](https://www.conventionalcommits.org)
  (`feat(tide): add rollback`, `fix(reef): ...`). The changelog is generated from them.
- **Sign-off:** we use the [Developer Certificate of Origin](https://developercertificate.org).
  Sign every commit with `git commit -s`.
- **Checks:** run the repository's checks before pushing. CI runs the same
  steps: in the monorepo that is `cargo xtask check` (format, clippy, tests,
  licence checks, and the dashboard with Bun).

## Tooling

- **Rust:** `cargo xtask <command>` is the task runner in the monorepo; there
  is no `just` and no `make`.
- **JavaScript:** [Bun](https://bun.sh) for installs, scripts and tests
  (`bun install`, `bun run`, `bun.lock`). No pnpm and no npm lockfiles.
- **Releases:** release-plz on `main` (version, `CHANGELOG.md`, tag, GitHub
  release); see the monorepo's `CONTRIBUTING.md` for the full flow.

## Adding dependencies

Every dependency must pass the Crustates component policy:

1. An OSI-approved licence, or a managed service run by a European company
   that speaks an open standard
2. No phone-home; operable by us and replaceable behind a port
3. Forkable if the maintainer relicenses
4. Nothing that sends customer data outside European-operated infrastructure

Mention new dependencies and why you need them in your pull request; a new
service or data store needs an ADR first.

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
