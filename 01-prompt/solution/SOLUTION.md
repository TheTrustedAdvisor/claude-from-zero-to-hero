# Solution 01-prompt

```text
Decision: Move the portal launch to Monday 14 December | Owner: Elena Costa | Due: 18 Nov 2026
Decision: Approve the extra CHF 4,500 for external testers from the contingency | Owner: Peter Steiner | Due: 20 Nov 2026
Decision: Run two portal training sessions for the help desk | Owner: Jonas Weber | Due: 10 Dec 2026
```

Accept other wordings, as long as each line has the same decision, owner and date. Other models word things differently; the pattern stays the same: three decisions, one owner and one date each.

## Not decisions (should not be in your list)

| Item in the notes | Why it is not a decision |
|---|---|
| Dark mode | An idea, explicitly "not for this release". No owner, no date: nothing to track. |
| Chat widget | Open: Mia asks the support lead, "Not decided". |
| Updated cost sheet | A task, not a decision. |

## If your answer differs

- **A fourth line "Leave dark mode out of this release | Owner: none | Due: none":** this is what Claude produced when we tried the exercise on 11.11.2026 (Opus 5.5). Fair reading, but not a tracker item. Sharpen once more: "Only decisions that someone has to act on."
- **Five or more lines:** the prompt didn't say "only what was decided". Add the reader and the goal.
- **Right content, mixed shapes** (owner in brackets, date missing on one line): add the example line. It fixes the format more reliably than "keep it short".
- **Owner for the launch is Mia:** defensible, but the notes give the follow-up to Elena (she tells the agency by 18 November). Ask Claude: "Owner means the person with the next action."
