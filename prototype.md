# /prototype

Go from a rough idea to a working prototype in one session.

## Usage

`/prototype <what to build>`

Example: `/prototype a waitlist landing page for an AI meeting-notes app with email capture`

## Steps

1. **Clarify the stack (one question max).** If the project already has a stack, use it. Otherwise default to the simplest thing that runs (single HTML file, or the repo's existing setup). Don't bikeshed.
2. **State the plan.** 3–5 bullets: what you'll build, the key screens/states, what you're explicitly skipping. Wait for a nod on anything ambiguous.
3. **Build it.** Working code over scaffolding. Real copy, real data shapes, real interactions. Follow the taste standards in CLAUDE.md — no AI-slop UI.
4. **Run it.** Start the dev server / open the file, verify it renders, click through the main flow yourself.
5. **Report.** One screenshot-worthy summary: what works, the 2–3 decisions you made, and what's stubbed.

## Rules

- A prototype is for learning, not for production. Optimize for speed of iteration.
- Fake the backend with realistic mock data; make the seams obvious (a `mock/` folder, not hidden hacks).
- If the idea needs more than ~30 minutes of build, slice it: prototype the riskiest interaction first.
