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
how components are used and where. not abstract "thinking" but specific decisions: a session screen always has a nav bar, two speech areas, a mic button. the designer defines this. the tool can't invent it.
atomic design equivalent: *templates*.

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

## references

added with `/note`. pulled into posts when relevant.

<!-- notes appended below this line -->
