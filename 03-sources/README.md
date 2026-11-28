# Exercise 03-sources

Companion exercise to part 3 of "Claude from Zero to Hero": "Can you trust Claude's answer? Web search, sources and mistakes". Runs in any Claude plan, Free included.

## Task

`claims.md` lists five short claims about spreadsheets, data and AI. Some are true, some are false, and one can't be verified at all.

1. Start a new chat. For each claim, send: `Search the web: is this true? Name the source and quote the sentence that supports or contradicts it.` followed by the claim.
2. Open at least one of the source links Claude gives you for each claim. Search the page for the number (Ctrl+F, or Cmd+F on a Mac) and find the sentence yourself.
3. Mark each claim as **true**, **false** or **not verifiable**, and write down the sentence and the page that settles it.

If Claude can't find a source, or the linked page doesn't contain the sentence, don't guess: mark the claim as not verifiable, or ask Claude where exactly the page says that.

## What a good result looks like

- Two claims true, two false, one not verifiable.
- For each true or false claim: one sentence from a page you opened yourself, not only Claude's summary.
- For the false ones: the number the source actually gives.

## Check yourself

`solution/SOLUTION.md`.
