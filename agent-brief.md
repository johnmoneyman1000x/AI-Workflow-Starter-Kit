# /agent-brief

Write a tight brief before delegating to an agent. A 5-minute brief saves a 2-hour misfire.

## Usage

`/agent-brief <what you want the agent to do>`

## The brief format

Write all six. If you can't fill one in, that's the thing to figure out before delegating.

1. **Goal.** One sentence. What does "done" look like, concretely?
2. **Context.** The minimum background the agent needs: repo layout, relevant files, decisions already made. Link, don't paste walls of text.
3. **Constraints.** What's off-limits: files not to touch, approaches to avoid, time/complexity budget.
4. **Done criteria.** How you'll verify: tests passing, screenshot attached, specific files changed, a written summary.
5. **Output format.** What you want back: a diff, a doc, a table, a demo. Specify it.
6. **Failure mode.** What should the agent do if stuck: ask, make a reasonable assumption and flag it, or stop?

## Rules

- The brief is the contract. Vague brief → vague result; that's on you, not the agent.
- Keep it under 300 words. If the brief is longer than the task, do the task yourself.
- Review the agent's output against the done criteria before accepting.
