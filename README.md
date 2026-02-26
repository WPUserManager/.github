# WP User Manager Default GitHub Files

Default issue and PR templates for all repos in the WPUserManager org.

## How It Works

The `.github` directory here applies to any repo in `WPUserManager` that doesn't have its own `.github` directory. See [GitHub docs](https://docs.github.com/en/github/building-a-strong-community/creating-a-default-community-health-file#creating-a-repository-for-default-files).

## Issue Templates

| Template | Description |
|----------|-------------|
| Bug Report | Something is broken — includes environment info and severity |
| Feature Request | New functionality — user story format |
| Enhancement | Improve existing functionality |
| Chore | Internal tasks — refactoring, deps, CI, tooling |

Issues are automatically added to the [project board](https://github.com/orgs/WPUserManager/projects/2) and shaped by the ops agent (RICE scoring, acceptance criteria, technical notes).

## Pull Request Template

Guides developers through: what changed, testing instructions, test coverage, and a pre-merge checklist. PRs should use `Resolves #` to link issues for automatic board status updates.
