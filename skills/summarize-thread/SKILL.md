---
name: summarize-thread
description: Turn a long message thread into decisions, open questions and next steps. Use when someone asks what a thread came to.
version: 1
---

# Summarize thread

## When to use

- "What did we decide in this thread?"
- "Catch me up on this conversation."

## Inputs

- The full thread, oldest message first, with authors and times.

## Steps

1. Read the whole thread before writing anything.
2. List decisions that were agreed, with who agreed.
3. List questions still open, with who owns each one.
4. List next steps, with owner and due date when the thread gives one.
5. Drop greetings, thanks and anything already superseded.

## Output

```
Decisions
- <decision> (<who>)

Open questions
- <question> (owner: <who>)

Next steps
- <step> (owner: <who>, due: <date or none>)
```

Leave a section out if it's empty. One line per item.

## Don't

- Don't invent owners or dates the thread doesn't state.
- Don't quote private details that aren't needed for the summary.
