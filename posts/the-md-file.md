# the .md file

i've been using claude code for a few days. before that it was google ai studio, then lovable, then figma make. through all of those, the question is the same: what do i need to give the tool so the output is actually good.

the answer keeps being the .md file.

there's something happening at a bigger scale that feels related. google gemini's redesign leans on native ui, the base design language of iOS and android, instead of building a visual system from scratch. you take what the OS gives you and define only what's distinctly yours on top. you're not reinventing every element. you're deciding what belongs to your product.

the .md file works the same way at the level of a single project. layer 1 is tokens: colors, typography, spacing, radius, shadows. brad frost calls these atoms. layer 2 is components: how those tokens combine into actual ui pieces. a button, a mic button, a nav bar, a bottom sheet. molecules and organisms. layer 3 is patterns: where components live and how they behave. a session screen always has a nav bar and a mic button. toast always enters from the top. destructive actions always ask for confirmation. templates. once those three layers are in the file, the tool stays consistent. what's left for me is thinking.

i spent a while getting layer 3 wrong. "use orange for CTAs" is not a rule. "use orange-500 for primary monetizable actions only, never more than one per viewport, disabled opacity 40%, minimum mobile height 48px" is. that version has business logic in it, and accessibility, and hierarchy.

i've been thinking about why this changes how building feels, and i keep coming back to an analogy. what svg is to icons is what a .md file is to design systems. svg stores a visual asset in portable, machine-readable, human-readable form. you pass it anywhere and it renders. a .md file does the same for a design system. you pass it to claude code, to figma, to antigravity, and each one reads from the same source. it doesn't document the system. it carries it.

layer 4 is everything after that. workflow, cognitive load, emotional pacing, edge cases, user trust. none of that lives in a file. it's what you bring. i'm still working out how much of that is learnable versus how much is just always yours.

---

some things that shaped my thinking:

https://youtu.be/W1gWIQp9k1Y

https://github.com/google-labs-code/design.md

https://designmd.app

https://medium.com/design-bootcamp/design-md-as-a-standard-1fd1af0fcc33

https://medium.com/design-bootcamp/google-makes-design-md-open-source-on-its-way-to-become-a-industry-standard-16119f2368dd

https://github.com/pbakaus/impeccable

https://github.com/Dammyjay93/interface-design
