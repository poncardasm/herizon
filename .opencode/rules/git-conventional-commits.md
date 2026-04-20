# Conventional Commits Rule

All git commits MUST follow the [Conventional Commits](https://www.conventionalcommits.org/) specification.

## Format

```
<type>(<scope>): <description>

[optional body]

[optional footer(s)]
```

## Commit Types

| Type | Description |
|------|-------------|
| `feat` | A new feature |
| `fix` | A bug fix |
| `docs` | Documentation only changes |
| `style` | Changes that do not affect the meaning (whitespace, formatting, etc) |
| `refactor` | A code change that neither fixes a bug nor adds a feature |
| `perf` | A code change that improves performance |
| `test` | Adding missing tests or correcting existing tests |
| `build` | Changes that affect the build system or external dependencies |
| `ci` | Changes to CI configuration files and scripts |
| `chore` | Other changes that don't modify src or test files |
| `revert` | Reverts a previous commit |

## Rules

- Use imperative mood in the subject line ("add" not "added")
- Do not end the subject line with a period
- Limit the subject line to 72 characters
- Separate subject from body with a blank line
- Use the body to explain what and why vs. how
- Reference issues and pull requests in the footer

## Examples

```
feat(auth): add user login functionality
fix(api): resolve null pointer exception in user service
docs(readme): update installation instructions
refactor(core): simplify validation logic
test(unit): add tests for date formatting
```
