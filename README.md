# Skills

My custom agent skills.

## Available skills

| Skill | Purpose |
| --- | --- |
| [babysit](skills/babysit/SKILL.md) | Keep an Azure DevOps pull request moving until it is ready to merge, addressing conflicts, CI failures, and existing review comments. |

## Installation

Clone this repository and copy `skills/babysit` into your agent's skills directory. For agents that use `~/.agents/skills`, the installed file should be `~/.agents/skills/babysit/SKILL.md`.

The babysit skill requires authenticated Azure DevOps access through tools, the CLI, or the REST API.
