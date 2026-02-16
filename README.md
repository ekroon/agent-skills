# agent-skills

Reusable agent skills that can be shared across projects and users.

## Repository layout

- `skills/<skill-name>/SKILL.md` (required)
- `skills/<skill-name>/scripts/` (optional executable helpers)
- `skills/<skill-name>/references/` (optional supporting docs)

This repository follows the Agent Skills format: https://agentskills.io/

## Available skills

### codespaces-secret-sync

Sync user Codespaces secret repository access so multiple secrets match one base secret.

Path: `skills/codespaces-secret-sync`

## Quick start

```bash
git clone https://github.com/ekroon/agent-skills.git
cd agent-skills
```

Run the Codespaces sync skill script:

```bash
python3 skills/codespaces-secret-sync/scripts/sync_codespaces_secret_repos.py
python3 skills/codespaces-secret-sync/scripts/sync_codespaces_secret_repos.py --apply
```
