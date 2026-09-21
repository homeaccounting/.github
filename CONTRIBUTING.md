# Contributing to HomeAccounting

This is the organization-wide default. Each code repository ships its own
`CONTRIBUTING.md` with setup instructions and the rules that actually block a
merge there — read that one if you are working in
[backend](https://github.com/homeaccounting/backend/blob/master/CONTRIBUTING.md),
[web](https://github.com/homeaccounting/web/blob/master/CONTRIBUTING.md), or
[site](https://github.com/homeaccounting/site/blob/master/CONTRIBUTING.md).

## Where to file things

**Issues belong to the repository you are using.**

| What | Where |
| --- | --- |
| API behaviour, bank providers, data problems | [backend](https://github.com/homeaccounting/backend/issues) |
| Web interface bugs and UX | [web](https://github.com/homeaccounting/web/issues) |
| Website and marketing content | [site](https://github.com/homeaccounting/site/issues) |
| Questions, ideas, bank-provider requests | [Discussions](https://github.com/orgs/homeaccounting/discussions) |
| Anything conversational | [Community](https://www.homeaccounting.com/community) |
| **Security vulnerabilities** | **Never in public** — [SECURITY.md](SECURITY.md) |

## What applies everywhere

- **[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)** for
  commit messages, `<type>/<kebab-case-description>` for branches, both named
  after the goal of the work rather than individual changes.
- **Branch off `master`**, keep a pull request to one goal, and make sure CI
  passes locally before pushing.
- **A Contributor Licence Agreement** is required before your first pull
  request merges. A bot asks on the PR; you keep your copyright.
- **Never commit real financial data** — not in code, fixtures, tests,
  screenshots, or issue attachments. Use synthetic data and scrub screenshots.
- **The [Code of Conduct](CODE_OF_CONDUCT.md)** applies in every repository,
  discussion, and chat. Reports go to `conduct@homeaccounting.com`.

## Good first contributions

Look for
[`good first issue`](https://github.com/search?q=org%3Ahomeaccounting+label%3A%22good+first+issue%22+state%3Aopen&type=issues)
across the organization. Adding a **bank provider** is the highest-value
contribution — each one opens a market that is not otherwise on the roadmap.
