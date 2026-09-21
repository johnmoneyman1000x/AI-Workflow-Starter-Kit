# /ship-check

Pre-ship checklist. Run this before you merge, deploy, or demo.

## Usage

`/ship-check [scope — defaults to current changes]`

## The checklist

Go through each. Pass, fail, or N/A — with evidence, not vibes.

1. **States.** Loading, empty, error, and edge states all render. No blank screens, no infinite spinners.
2. **Responsive.** Works at 375px, 768px, and 1440px. No horizontal scroll, no overlapping text, tap targets ≥ 44px on mobile.
3. **Accessibility.** Semantic HTML, visible focus states, alt text on meaningful images, color contrast ≥ 4.5:1 for body text, keyboard-navigable flows.
4. **Copy.** No lorem ipsum, no placeholder text, no typos. Error messages tell the user what happened and what to do next.
5. **Performance.** No obvious waterfalls, images sized appropriately, no layout shift on load.
6. **Hygiene.** Typecheck and lint pass. No console.logs, no commented-out code, no dead files. Migrations/rollbacks considered if data changes.

## Output

A table: check → pass/fail/N/A → evidence or the fix needed. End with a verdict: **ship it** or **fix these N things first** (list them, hardest first).
