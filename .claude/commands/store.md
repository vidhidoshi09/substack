Store a new Substack idea into the ideas bank.

The user's raw thought is: $ARGUMENTS

## What to do

1. Read the current `ideas.md` file.
2. Get today's date and current time.
3. Look at the last entry in the file. If the last entry's date is different from today, add a day divider before the new idea:

```
⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

## <month day, year>

```

If the last entry is from the same day, just continue under the existing day heading.

4. Append the new idea in this format:

```
### idea #<N> — <hh:mm am/pm>

**raw thought:**
<preserved thought — see rules below>

**seed angle:** <a single sharp angle or hook that this idea could become>

---
```

Where `<N>` is the next sequential number based on all existing entries.

## rules for preserving the raw thought

these are strict. follow them exactly:

- **keep the original length.** do not compress, summarize, or cut. if the user wrote 10 sentences, save 10 sentences.
- **keep the structure the user used.** if they wrote in pointers or separate paragraphs, keep that. if it was a stream, keep it as a stream.
- **no em dashes.** ever. replace any with a comma, a period, or just remove them. never use " — ".
- **no rewriting.** fix only typos and broken speech-to-text artifacts (e.g. "ICPM" → "if PMs", "Rhitik" → "aesthetic"). do not rephrase, tighten, or elevate the language.
- **lowercase throughout.**
- **light structure is okay** — if the user's input has clearly separate topics, you may use a blank line between them. do not add headers or bullets unless the user wrote that way.

5. Confirm to the user: "✅ idea #N saved. type `/thought` to see your bank, or `/post <number or topic>` to draft it."

Do NOT generate a full post. Just capture and lightly preserve the thought.
