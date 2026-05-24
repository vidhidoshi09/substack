Generate a full Substack post draft.

The user's input (idea number, topic, or raw thoughts) is: $ARGUMENTS

## What to do

### Step 1 — Load context
1. Read `substack-instructions.md` — this defines voice, structure, audience, tone.
2. Read `ideas.md` — if the user referenced an idea number or topic, find it there.
3. If `substack-instructions.md` has mostly empty fields, note which sections are blank and proceed with what's available — do NOT refuse to generate.

### Step 2 — Clarify (only if needed)
If the input is extremely sparse (fewer than 5 words and not referencing a stored idea), ask ONE question:
> "Quick clarification — what's the core tension or insight you want this post to land on?"

Otherwise, proceed directly to drafting.

### Step 3 — Generate the post

Write a complete Substack post draft following the structure and voice from `substack-instructions.md`.

Output format:

---

## 📝 Draft: [Proposed Title]

**Suggested subtitle:** [one line]

---

[Full post body here — ready to copy-paste into Substack]

---

**Word count:** ~[N] words

**Suggested tags:** [2-4 tags]

---

### ✏️ Editorial notes
- [1-2 sentences on choices made — why this angle, what's punchy, what might need personalizing]
- [Flag any section that needs the user's real anecdote or specific data]

---

### Step 4 — Offer next steps
After the draft, say:
> "Want me to adjust the tone, make it shorter/longer, punch up the opening, or try a different angle? Just say the word."
