# /blueprint

Turn messy notes into a spec you can actually build from.

## Usage

`/blueprint <paste your rough notes>`

Example: `/blueprint voice memos should auto-summarize into tasks, people keep asking, not sure realtime vs async`

## How it works

1. **Find the real ask.** Strip the notes down to what gets built, who it's for, and why it matters now. Park everything else.
2. **Ask up to 3 questions.** Only questions whose answers would change the build. If it wouldn't change anything, don't ask.
3. **Draft the spec.** The problem in one paragraph, who's affected, what's explicitly in and out, the core flows, the data involved, edge cases worth handling, and what's still unknown.
4. **Sequence the build.** First slice, what gets faked, what gets dropped if time runs out.

## Rules

- A spec earns its length. If reading it takes longer than building v1, cut it.
- Every "should we?" lands somewhere: in scope, out of scope, or an open question with a named owner and a date.
- No orphaned unknowns — each one gets a person and a deadline.
