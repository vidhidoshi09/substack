Search the ideas bank and return only matching entries.

The search query is: $ARGUMENTS

## What to do

1. Read `ideas.md`.
2. Parse the query — it could be:
   - a **keyword or phrase** (e.g. "design system", "figma")
   - a **date** (e.g. "may 24", "yesterday", "today")
   - a **topic** (e.g. "AI", "product", "handoff")
   - a **combination** (e.g. "design may 24")

3. Search across all fields of each idea entry:
   - idea heading (number + time)
   - day heading (date)
   - raw thought
   - seed angle

4. Return only the matching entries, preserving their original format. Group results under their original day headings if multiple days match.

5. If no matches found, say:
   > "no ideas matched '[query]'. try a different keyword or date, or type `/thought` to see everything."

6. After results, show:
   > "found [N] idea(s). type `/post <number>` to draft any of these."

Keep output clean and scannable. Do not rewrite or summarize the entries — show them as-is.
