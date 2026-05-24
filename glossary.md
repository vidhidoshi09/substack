# glossary

this file works as a zettelkasten. two things live here:
1. **terms and frameworks** vidhi uses across her work
2. **references**: things she's read, seen, heard, or noticed that she wants to keep

references are added via `/note`. they get pulled into posts when relevant.

---

## terms and frameworks

### design system layers

the way vidhi structures a design system when building with ai tools. maps directly to atomic design (brad frost's framework).

**layer 1 — tokens**
colors, typography, spacing, radius, shadows, effects. the raw material. lives in DESIGN.md. claude code reads this as source of truth.
atomic design equivalent: *atoms*.

**layer 2 — components**
how tokens combine into actual ui pieces. button, mic button, nav bar, input, chips, bottom sheet. built on demand as screens need them.
atomic design equivalent: *molecules and organisms*.

**layer 3 — patterns**
how components are used and where. not abstract "thinking" but specific decisions: a session screen always has a nav bar, two speech areas, a mic button. toast enters from top. destructive actions need confirmation. mobile CTAs stay thumb-accessible. the designer defines this. the tool can't invent it.
atomic design equivalent: *templates*.

**layer 4 — product thinking**
the actual hard part. workflow sequencing, hierarchy, cognitive load, edge cases, business logic, emotional pacing, user trust. this layer doesn't live in any .md file. it's what you bring.

---

### atomic design (brad frost)
a framework for building design systems from smallest to largest: atoms → molecules → organisms → templates → pages. widely known. vidhi's layer 1/2/3 maps onto this directly and can be used as a bridge when explaining her layers to a reader.

---

### tools (as of may 2026)

**claude code** — ai coding tool. key differentiator: can access figma directly. using since may 2026 (a few days).
**antigravity** — design-to-code tool. doesn't improvise. follows what's given. preferred when designs are ready and just need building.
**google ai studio** — used before claude code for design-to-code work.
**lovable** — used before claude code.
**figma make** — used before claude code.
**stitch** — can generate .md files (antigravity cannot, as of now).

---

### system ui
the native design language of a phone's operating system (iOS, android). using system ui means building on apple or material design's base components rather than designing from scratch. a growing number of apps are choosing this as the foundation and adding only their distinct layer (typography, color, illustration) on top.

---

### design.md (google labs)
an open-source structured design system format shipped by google labs in april 2026. a single markdown file with yaml frontmatter (tokens: colors, typography, spacing) plus prose explaining the reasoning behind decisions. the idea: a portable, machine-readable, human-readable contract for a design system that ai agents, figma, react, and documentation tools can all consume from the same source of truth. becoming an industry standard for ai-readable design systems.
- spec: https://github.com/google-labs-code/design.md
- tool: https://designmd.app
- video walkthrough: https://youtu.be/W1gWIQp9k1Y

---

### impeccable (paul bakaus)
a design vocabulary skill for ai coding assistants. sits between intent and execution. gives ai tools the concepts designers use daily but developers haven't encountered. uses slash commands: /audit, /arrange, /typeset, /polish. the idea: stop ai-generated ui from looking like ai made it.
- site: https://impeccable.style
- github: https://github.com/pbakaus/impeccable

---

### interface-design skill (dammyjay93)
a design skill for ai coding assistants, similar in spirit to impeccable. focuses on interface design principles for ai tools.
- github: https://github.com/Dammyjay93/interface-design

---

### svg analogy
"what svg is to icons is what a .md file is to design systems."
svg stores a visual asset in portable, machine-readable, human-readable form — you pass it anywhere and it renders. a .md design system file does the same for a design system. it doesn't document the system. it IS the system.

---

### good rule vs bad rule (from vidhi's notes)
a .md file is only as useful as the quality of rules inside it.

bad rule: "use orange for CTAs."
good rule: "use orange-500 only for primary monetizable actions. never more than one primary CTA per viewport. disabled opacity = 40%. min mobile height = 48px. destructive actions cannot share orange styling."

the second encodes business logic, ux intent, accessibility, and hierarchy — not just a visual choice. this is the work that moves into the .md file.

---

## references

added with `/note`. pulled into posts when relevant.

### note #1 — may 24, 2026, 12:45pm IST

**source:** design.md ecosystem (google open source + community)
**noted:** design.md is google's open-source structured design system format. becoming an industry standard for ai-readable design systems. related tools and writing:
- https://designmd.app
- https://github.com/google-labs-code/design.md
- https://medium.com/design-bootcamp/google-makes-design-md-open-source-on-its-way-to-become-a-industry-standard-16119f2368dd
- https://medium.com/design-bootcamp/design-md-as-a-standard-1fd1af0fcc33
- https://youtu.be/ETylJa-iXJ8?si=P9IZ1df2DgKReGjz
- impeccable.md (vidhi to confirm exact url)
**might connect to:** the .md file post (idea #1 and #2), any future post about design systems and ai tools

---

<!-- notes appended below this line -->
