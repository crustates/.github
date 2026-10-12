## What and why

<!-- What does this change, and why is it needed? Link the issue: Closes #123 -->

## Target branch

- [ ] This pull request targets `development` (the integration branch)
- [ ] …or it targets `main` and the head branch is `development` or `hotfix/*`

## Area

- [ ] Tide
- [ ] Reef
- [ ] Control plane / API
- [ ] Dashboard / CLI / TUI / MCP
- [ ] Infra / deploy
- [ ] Docs

## Checklist

- [ ] The repo's checks pass locally (`cargo xtask check` in the monorepo)
- [ ] Tests added or updated
- [ ] Docs updated (if user-facing)
- [ ] New dependencies pass the component policy (OSI licence or a European
      managed service behind a port; `cargo deny check` in the monorepo)
- [ ] No new `just`, pnpm or Node tooling: `cargo xtask` and Bun
- [ ] Commits are signed off (`git commit -s`)
