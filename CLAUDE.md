# CLAUDE.md — AI Artifact Starter Kit

Copy this to the root of any project. Adapt the bracketed parts.

## How we work

- **Plan before building.** For anything non-trivial, state your plan (files to touch, approach, risks) and wait for a nod before writing code. Small fixes: just do them.
- **Small diffs.** Prefer the smallest change that solves the problem. Don't refactor adjacent code unless asked.
- **Show, don't describe.** After changes, show the diff or the result — not a paragraph about what you did.
- **Ask before destructive actions.** Deleting files, dropping data, force-pushing, changing infra: always confirm first.
- **Verify your work.** Run the typechecker, linter, and relevant tests before declaring done. If you can't run them, say so explicitly.

## Taste standards (this is the important part)

AI-generated UI has a recognizable slop signature. Never ship it:

- **Banned:** purple/blue gradients, generic hero sections ("Welcome to..."), lorem ipsum or placeholder copy, identical rounded cards in a grid, emoji as decoration, "delve", "leverage", "unlock", "game-changer" in copy.
- **Required:** real, specific copy (write like a human with an opinion); typography-first hierarchy; generous whitespace; one clear primary action per screen; mobile-first responsive.
- **Design like you have taste.** Reference: Linear, Vercel, Arc, Teenage Engineering. Restrained color, confident type, motion with purpose.

## Product thinking

- Every feature answers: who is it for, what job does it do, what does success look like? If that's unclear, ask before building.
- **States matter more than the happy path.** Every UI needs: loading, empty, error, and edge states. Ship-check these with `/ship-check`.
- Prefer boring technology and proven patterns. Novelty is a cost.

## Code standards

- TypeScript strict; no `any` without a comment explaining why.
- Components: small, named for what they render, co-located styles.
- No dead code, no commented-out blocks, no TODOs without an owner.
- Commits: conventional format (`feat:`, `fix:`, `chore:`), present tense, scope when useful.

## Communication

- Be concise. Lead with the conclusion, then the reasoning.
- When there are real tradeoffs, name them and recommend one — don't hedge.
- Never say "as an AI". Never apologize for asking a clarifying question.

## MCP & tools

- If MCP servers are configured (browser, design tools, databases), prefer using them over asking me to paste things in.
- Use web search for library docs and API references when unsure — don't guess APIs from memory.

---

*Part of the [AI Workflow Starter Kit](https://johnmaartifacts.substack.com) — free.*
