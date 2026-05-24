Store a new Substack idea into the ideas bank.

The user's raw thought is: $ARGUMENTS

## What to do

1. Read the current `ideas.md` file.
2. Get today's date and current time.
3. Look at the last entry in the file. If the last entry's date is different from today, add a day divider before the new idea:

```
&nbsp;

⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

## <month day, year>

```

If the last entry is from the same day, just continue under the existing day heading.

4. Append the new idea in this format:

```
### idea #<N> — <hh:mm am/pm>

**raw thought:** <the user's input, lightly cleaned up but not rewritten>

**seed angle:** <a single sharp angle or hook that this idea could become>

---
```

Where `<N>` is the next sequential number based on all existing entries.

5. Confirm to the user: "✅ idea #N saved. type `/thought` to see your bank, or `/post <number or topic>` to draft it."

Do NOT generate a full post. Just capture and lightly sharpen the seed.
