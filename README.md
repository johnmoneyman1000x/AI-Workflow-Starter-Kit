# The AI Workflow Starter Kit
*Free companion to the AI Artifact newsletter — practical AI workflows for designers, founders, and PMs.*

This is the exact setup I use daily: a `CLAUDE.md` that makes Claude Code actually good at product work, 5 slash commands for the workflows I run on repeat, and 3 agent definitions for delegating real chunks of work.

## What's inside

| File | What it does |
|---|---|
| `CLAUDE.md` | Project instructions: taste standards, workflow rules, and how I want Claude to work with me |
| `commands/prototype.md` | `/prototype` — go from idea to working prototype in one session |
| `commands/review-design.md` | `/review-design` — adversarial design critique of any UI |
| `commands/ship-check.md` | `/ship-check` — pre-ship checklist (a11y, responsive, states, perf) |
| `commands/research-synth.md` | `/research-synth` — turn raw research notes into insights |
| `commands/agent-brief.md` | `/agent-brief` — write a tight brief before delegating to an agent |
| `agents/builder.md` | A `builder` agent that implements from a spec |
| `agents/design-critic.md` | A `design-critic` agent that reviews like a principal designer |
| `agents/researcher.md` | A `researcher` agent that maps unfamiliar codebases |

## Install (5 minutes)

1. **CLAUDE.md** → copy to the root of any project. Claude Code picks it up automatically.
2. **Slash commands** → copy the `commands/` folder contents to `~/.claude/commands/` (global) or `<project>/.claude/commands/` (per-project). Restart Claude Code.
3. **Agents** → copy the `agents/` folder contents to `~/.claude/agents/` (global) or `<project>/.claude/agents/` (per-project).

Verify: type `/` in Claude Code — you should see `prototype`, `review-design`, `ship-check`, `research-synth`, and `agent-brief`.

## The philosophy

Most AI output is mediocre because the instructions are vague. This kit fixes the three things that matter:

1. **Taste is specified, not hoped for.** The CLAUDE.md bans generic AI-slop patterns (purple gradients, cookie-cutter heroes, lorem ipsum) and states what good looks like.
2. **Workflows are commands, not vibes.** Anything you do twice becomes a slash command with steps, so quality is repeatable.
3. **Delegation has a contract.** Agents get a brief with a goal, constraints, and done-criteria — then work unsupervised.

Steal it, fork it, make it yours. That's the point.

— John · [AI Artifact](https://johnmaartifacts.substack.com)
