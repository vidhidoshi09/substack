# the .md file

i've been switching tools constantly. google ai studio first, then lovable, then figma make, now claude code for the past few days. every time i switch, the first few sessions i'm re-explaining everything: colors, components, how things are supposed to behave.

that kept happening until i started keeping a .md file and passing it to whatever tool i moved to.

the file has three layers. layer 1 is tokens: colors, typography, spacing, shadows. brad frost calls these atoms. layer 2 is components: how tokens combine into actual ui pieces. a button, a nav bar, a mic button, a bottom sheet. molecules and organisms. layer 3 is patterns: how components behave. a session screen always has two speech areas and a mic button at the center. toast always enters from the top. destructive actions always ask for confirmation. templates. once those three layers are solid, the tool has what it needs to stay consistent. what's left for me is thinking.

i spent a while getting layer 3 wrong. i kept writing "use orange for CTAs" and being confused when things were still inconsistent. the problem was that wasn't a rule, it was a preference. a real rule is "use orange-500 for primary monetizable actions only, never more than one per viewport, disabled opacity 40%, minimum mobile height 48px." that version tells the tool what the color means, when to use it, what the constraints are. once i started writing like that, things clicked.

i kept trying to explain to myself why the file changes so much about how sessions go. the analogy i landed on: what svg is to icons is what a .md file is to design systems. svg stores a visual asset in portable, machine-readable, human-readable form. pass it anywhere and it renders. a .md file does the same for a design system. pass it to claude code, to figma, to antigravity, and each one reads from the same source. it doesn't document the system. it carries it.

google gemini's recent redesign felt like the same principle. instead of building a new visual language from scratch, they leaned on native ui, the base design language of iOS and android, and put only what's distinctly gemini on top. when i read about that i thought: same thing, different scale.

layer 4 is everything else. workflow, cognitive load, emotional pacing, edge cases, user trust. none of that lives in a file. it's what you bring. i'm still working out how much of that is learnable.

---

some things that shaped my thinking:

https://youtu.be/W1gWIQp9k1Y

https://github.com/google-labs-code/design.md

https://designmd.app

https://medium.com/design-bootcamp/design-md-as-a-standard-1fd1af0fcc33

https://medium.com/design-bootcamp/google-makes-design-md-open-source-on-its-way-to-become-a-industry-standard-16119f2368dd

https://github.com/pbakaus/impeccable

https://github.com/Dammyjay93/interface-design
