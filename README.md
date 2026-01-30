# Agent Best Practices

> Drop-in rules file to make AI agents follow tasks more clearly and avoid common mistakes.

## What This Is

A battle-tested `AGENTS.md` file containing 15 core rules + supporting guidelines for AI coding agents (Claude, GPT, Cursor, Copilot, etc.).

Born from real failures. Fixes real problems.

## Quick Start

```bash
# Download and drop into your project
curl -O https://raw.githubusercontent.com/NextFrontierBuilds/agent-best-practices/main/AGENTS.md
```

Or just copy `AGENTS.md` into your project root.

## The 15 Rules

1. **Confirm before executing** — Repeat back the task
2. **Never publish without approval** — Show draft → get OK → then post
3. **Spawn agents only when truly needed** — Simple tasks = do yourself
4. **When user says STOP, you stop** — Full stop, re-read chat
5. **Simpler path first** — Don't fight broken tools for 20 min
6. **One task at a time** — Finish, confirm, then move on
7. **Fail fast, ask fast** — 2 failures = escalate
8. **Less narration during failures** — Fix quietly or ask for help
9. **Match user's energy** — Short frustrated messages = short responses
10. **Ask clarifying questions upfront** — Don't assume
11. **Read reply context** — Focus on what they replied to
12. **Time-box failures** — 3 tries or 5 min max
13. **Verify before moving on** — Confirm actions worked
14. **Don't over-automate** — Manual sometimes better
15. **Process queued messages in order** — Read ALL before acting

## Also Includes

- **Communication rules** — Never go silent during builds
- **Memory rules** — Write it down, don't make "mental notes"
- **Safety rules** — Ask before external actions
- **Group chat etiquette** — When to speak, when to stay silent
- **Publishing rules** — Always show draft first
- **Quick reference table** — Situation → action mapping
- **Anti-patterns** — What NOT to do

## Why This Exists

These rules came from a real session where an AI agent:
- Deleted a post by accident
- Spawned unnecessary background agents
- Fought browser automation for 30 minutes
- Ignored multiple "STOP" messages
- Published without showing a draft
- Went silent during a 10-minute build

Don't let your agent make the same mistakes.

## Works With

- Claude (Anthropic)
- GPT-4 / ChatGPT
- Cursor
- GitHub Copilot
- Windsurf
- Any agent that reads project files

## Installation Options

### Option 1: Direct download
```bash
curl -O https://raw.githubusercontent.com/NextFrontierBuilds/agent-best-practices/main/AGENTS.md
```

### Option 2: Git submodule
```bash
git submodule add https://github.com/NextFrontierBuilds/agent-best-practices.git .agent-rules
cp .agent-rules/AGENTS.md .
```

### Option 3: Copy-paste
Just copy the contents of `AGENTS.md` into your project.

## Customization

The file is meant to be customized. Add your own:
- Project-specific rules
- Tool configurations
- Team conventions
- Lessons learned

## Contributing

Found a rule that helps? Open a PR.

## License

MIT — Use it, modify it, share it.

---

Built by [@NextXFrontier](https://x.com/NextXFrontier)
