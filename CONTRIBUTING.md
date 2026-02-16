# Contributing

Thanks for contributing to `agent-skills`.

## Add a new skill

1. Create a new folder under `skills/<skill-name>/`.
2. Add `SKILL.md` with YAML frontmatter including:
   - `name`
   - `description`
3. Add optional `scripts/` and `references/` folders as needed.
4. Keep examples generic and reusable across users.

## Validation checklist

- `SKILL.md` has valid frontmatter and clear trigger-oriented description.
- Script examples run from repository root.
- No personal credentials or account-specific defaults are committed.
