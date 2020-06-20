# Evolution/MV
(Putting the ghost in the {Pick/Multivalue} machine since 1994)
What you'll find here is some of my personal Pick Basic source code (and maybe some necessary data, too).
I call this particular project AnyKey.
AnyKey's purpose is to enable Pick programs to respond to any key (or combination of keys) on the keyboard, no matter what terminal emulation or terminal emulator is being used.
It also allows existing programs to be retrofitted without breaking existing functionality (because of hard-coded keyboard-strings).
I've written it as flavor (and host OS) agnostic as possible, but, of course, given the many flavors of Pick, each with its own ablity to emulate most other flavors, this is a herculean task, which is one of the reasons it's here: Not just to share it with others (and show off my own talents), but also to invite others to contribute to it in order to make it even more valuable to the community (which badly needs it) than it already is.
To that end, you will find, in the code, wherever flavor-agnostic coding was impossible, I've marked flavor-specific sections.  Wherever installed, irrelevant flavors' code sections must first be removed/commented-out.  I have a pre-compiler which automates this process, but that's a separate project.
