# Exercise 01-prompt

Companion exercise to part 1 of "Claude from Zero to Hero": "How to prompt Claude: give it the job, not just the question". Runs in any Claude plan, Free included.

## Task

`project-notes.txt` are the notes of a project meeting. Your manager wasn't there and wants the decisions, nothing else, in the format of her decision tracker:

```text
Decision: <what> | Owner: <name> | Due: <date>
```

1. Upload `project-notes.txt` (+ > Upload or add files, or drag it into the chat) and send only: `Summarize this meeting.` Look at the answer.
2. Stay in the same chat and sharpen it, one element per message: who reads it and why, the format, then one example line. Don't start over.
   In the tracker, **Due** is the date of the owner's next action: the day by which the owner has to do their part. Say that in your prompt, so Claude doesn't have to guess which date you mean.
3. Stop when the answer has exactly the lines your manager can paste into her tracker.

## What a good result looks like

Exactly three lines, each with a decision, one owner and one date, in the tracker format. Nothing about dark mode, the chat widget or the cost sheet: those weren't decisions.

## Check yourself

Compare with `solution/SOLUTION.md`. Count your lines first: three, not four or five.
