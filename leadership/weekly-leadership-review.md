# Weekly leadership review

## What this is for
A scheduled pass that writes one leadership review from the user’s meetings that week.

## When to use it
Use it once a week after the week’s meetings. Skip it if a full review was already delivered earlier that day.

## The prompt
```text
Deliver the user’s weekly leadership coaching review from Granola.

1. If you already delivered a full weekly leadership review to the user earlier the same day (for example in an ad-hoc chat), stay quiet — do not send a second one.
2. Query Granola for the user’s meetings from this week (and use last week only for pattern context). Prefer meetings they captured or participated in: 1:1s, leadership team syncs, media/product syncs, and other cross-functional leadership meetings.
3. Pull enough detail (summaries and, where useful, transcript moments) to coach from how they actually showed up — not generic advice.
4. Send the user a scannable weekly review in this format:
   - Week in view — which meetings you examined (title + date)
   - What you did well — specific moments from notes/transcripts
   - Where you slipped — specific moments; no vague “be more present”
   - Patterns — one or two recurring themes
   - One practice for next week — a single concrete, measurable behavior
   - Optional stretch — only if useful
5. Keep the coaching lens: buyback time / clarity / ownership, influence and people development, standards and decisive action, Radical Candor. Celebrate without flattery; challenge without contempt.
6. If Granola isn’t connected or returns nothing useful, tell the user plainly and ask what to use instead — never invent meetings.
7. Always send the review to the user in this chat when you have meetings to coach on.
```

## How to use it
1. Paste the prompt into an assistant that can read the meeting notes named in the prompt.
2. Run it on a weekly schedule. The saved schedule was Fridays at 16:00 (`0 16 * * 5`).
3. Send the review in chat only when there are meetings to coach on. If a full review already went out that day, stay quiet.
