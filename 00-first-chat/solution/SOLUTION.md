# Solution 00-first-chat

| Question | Kind | Run 1 and run 2 | Why |
|---|---|---|---|
| 1 Rows in one Excel worksheet | Fact | Same number both times: 1,048,576 rows. The extra details (columns, version) may be worded differently or missing. | A fact with one right answer: the most likely continuation is the same each time. |
| 2 Message to the team | Wording | Two different messages, for example "Quick heads-up: this week's status report will be due Monday ..." and "... is moving from Friday to Monday ...". | Many good wordings exist, so each run picks a different one. That is how the model works, not a mistake. |
| 3 Hotel limit in your travel policy | Your company | "I don't have access to your company's documents ..." plus suggestions to connect an app (Google Drive, Microsoft 365, Notion, ...) or to paste the policy. | Claude knows only what is in the chat, a project or a connected app. Your policy is in none of them. |

Observed on 11.11.2026 with Opus 5.5. Other models, and later versions, word things differently; the pattern stays the same: same fact, different wording, "can't see that".

Next step: part 1, "How to prompt Claude: give it the job, not just the question".
