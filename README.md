This Rimworld mod adds some extra item categories, so that you can set up stockpiles more easily:
- things which need to be indoors
- things which need refrigeration

When you're setting up stockpiles, they'll appear as top-level categories, near the bottom.
They don't have any sub-categories, so you'll have to scroll through everything if you want to get specific.
(Or use the normal categories - when you checkmark one of the new categories, it affects the normal categories too!)

Problems:
- that this doesn't work on meats or corpses
    - []this is because those are hard-coded, rather than being defined in XML](https://ludeon.com/forums/index.php?topic=46153.msg438893#msg438893)
- this also breaks the UI for creating/editing clothing assignments
    - the allow-tainted checkmark is gone, and everything else is in a root-level checkmark
    - possibly because there's a bunch of 'duplicate tag' errors (debug console) when the game / mod first load?  
