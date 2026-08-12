# Furkan Anter

Software developer building practical web, mobile, and AI-assisted products.

## `overengineer`

An Agent Skill that stops AI agents from turning a small task into an architecture project.

It pushes agents to:

- choose the smallest correct solution,
- preserve existing behavior and project patterns,
- reject speculative abstractions, dependencies, tools, and agents,
- test the behavior they actually changed,
- stop when the requirement is satisfied.

> Enough. The current solution already meets the requirement.

### Install

```bash
npx skills add furkananter/furkananter --skill overengineer
```

Global install without prompts:

```bash
npx skills add furkananter/furkananter --skill overengineer -g -y
```

Source: [`skills/overengineer/SKILL.md`](./skills/overengineer/SKILL.md)

Compatible with the open Agent Skills format and the Vercel Skills CLI.
