# Contributing

Commit messages should follow the [Conventional Commits](https://conventionalcommits.org) specification and will otherwise be squashed and renamed during PRs.

Prettier is used for code formatting and ES Lint for code linting. Run `npx prettier --write .` to format all files and `eslint .` to lint.

Each feature should be self-contained on its own branch, requiring at least one person to review and approve it before it is merged into `main`. Commits should be squashed so that each commit represents a meaningful change. Merging should be done with the "Rebase and Merge" method.
