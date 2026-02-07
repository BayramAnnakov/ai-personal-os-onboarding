# AI Personal OS — Onboarding Skill

A Claude Code skill that creates your personalized AI workspace through a conversational interview.

## What It Does

Instead of manually editing configuration files, this skill runs a 10-15 minute conversational onboarding that creates 4 files:

| File | Purpose |
|------|---------|
| `CLAUDE.md` | Personal AI instruction set — Claude reads this on every session start |
| `user-profile.md` | Your context: role, tools, work rhythm, preferences |
| `course-goals.md` | Your goals for the AI Personal OS course (5 weeks) |
| `SOUL.md` | Your AI mentor's personality — caring, productivity-focused |

## Install

The easiest way — ask Claude Code to do it:

```
Install the onboarding skill from https://github.com/BayramAnnakov/ai-personal-os-onboarding
```

Or download manually (no git required):

```bash
mkdir -p ~/.claude/skills/ai-personal-os-onboarding
curl -o ~/.claude/skills/ai-personal-os-onboarding/SKILL.md \
  https://raw.githubusercontent.com/BayramAnnakov/ai-personal-os-onboarding/main/SKILL.md
```

## Usage

In Claude Code:

```
/ai-personal-os-onboarding
```

Claude will walk you through:
1. **Discovery** — Who you are, what tools you use, how you communicate
2. **Goal Setting** — What you want from the course, what success looks like
3. **Personality** — How your AI mentor should behave (push hard vs. support gently)
4. **File Creation** — All 4 files generated and saved
5. **Validation** — Review and adjust what was created

## Part of AI Personal OS Course

This skill is designed for the [AI Personal OS](https://empatika.com/learn) course (Season 2), but works standalone for anyone who wants a personalized Claude Code setup.

- **Course:** 5 weeks, online workshops
- **Instructor:** Bayram Annakov
- **Topics:** Claude Code, MCP, Zettelkasten, N8N, Multi-Agent Systems

## Inspired By

- [OpenClaw](https://github.com/openclaw) — "Symbolic birth" pattern where the AI creates its own identity
- [2026-coach skill](https://github.com/BayramAnnakov/2026-coach) — Research-backed goal setting with process goals

## License

MIT
