# slashscript
slash's TF2 scripts

*Not* stable or ready for general use, as yet.

That said, if you're truly stupid enough to try this ...

1) Back up your TF2 configuration files.  If you don't already know where they are, you *really* shouldn't be using this.  Make sure to get your config.cfg, with autoexec and class CFGs where relevant.

2) This is meant to be a framework.  If you just want to change bindings or options, those are best placed in the appropriate file in the settings directory within the slashscript hierarchy.  The script invocation order will make sure they override the defaults appropriately.  Changes to the actual script files themselves are best limited to work on patches you want to submit, which would be appreciated, assuming they work and make sense.

3) Understand that this, in its default configuration, will produce some interesting interface changes.  For example, medic's weapon switching will be quite different, thanks to an idea from Catfunt.  (The way I built this is not his fault - this is meant as credit, not blame. :) ) Q, mousewheel, etc... will cycle between the medigun and melee, whereas holding shift will bring up the primary - with releasing it reverting to the last weapon prior.  This is intended to be used with a conventional competitive medic loadout such that the primary is crossbow, and the melee is ubersaw.  As a result, you can maximize the usefulness of the passive reload on crossbow, while having it always handy for arrowing teammates.  Also, when you're alone, you can have fast switching between crossbow and ubersaw as any threat nears.  I am working on making this kind of thing a good bit more configurable - tying it to loadout switching mechanics, etc... so different loadouts will be able to bring in the appropriate weapon logic.
