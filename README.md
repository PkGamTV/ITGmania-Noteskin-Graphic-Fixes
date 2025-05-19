# ITGmania-Noteskin-Graphic-Fixes
Fix those oddball graphics!

So I have been working on the noteskins in my ITGMania (https://www.itgmania.com/) to get them as graphically polished as possible. Sort of like a personal challenge that also scratches the itch of wanting to clean up the imperfections. This gave me the idea to plop them on github for everyone's use if they would like to do so as well. I set these up with default names so you can just drag and drop them in the Noteskins>Dance folder and it'll automatically replace the necessary files (Edit: With the exception of ddr-rainbow now that Peter redid it. So in that case, remove that one in ITGmania first before putting them all in so there aren't any file conflicts.). But you can also pick and choose which ones you would prefer. None of the things here are essential tweaks as they are all perfectly playable as-is without these. But you can read about them below.

-----Cel-----

-Redrew the hold bottomcaps so they aren't jagged and better match the bodies.

-Fixed the hold's slight gradient mismatches at the top loop point.

-Fixed the coloration of the active roll bottomcaps as there were very strong mismatches.

-----Cyber-----

-Made all hold graphics tile more invisibly. They're not perfect as the gradients are exceptionally hard to match and make them have the feel of the originals, but it's way less noticeable.

-The same active roll bottomcap fix as Cel as they use the same roll graphics. (Note that this does not fix the bug that causes them to not glow properly. I'm at a loss why it occurs because it uses the exact same active bottomcap code as Cel and Metal, Robot and Vivid which all work fine.)

-----DDR Rainbow-----

-I do not know how Peter made this, lol! So I just put the whole fallback noteskin in with the correct updated fallback code to match what ITGmania names the DDR ones. But basically it will show the colors accurately by position, not quantification like Cel. You can see his stuff (and the history of his DDR-Rainbow) here: https://github.com/Pete-Lawrence/Peters-Noteskins

-----Enchantment-----

-Fixed the mines so they aren't invading each other's space so you no longer see pieces of others flop in and cleaned up the graphical cutoff where bits were rotated outside the boundary of the image. There was also some odd buggy misalignment on a few frames that I cleaned up.

-Better matched the colors of the active roll bottomcap.

-----Flat-----

-Maybe add Flat to complete the ITG noteskin lineup? It's needed for official course functionality and all. Though it is a very unused noteskin. Skyblader07's "Alpha" noteskin pack was a big help here as I didn't know how a flat fallback noteskin was created. But his Flat was set up for it using some commonly used code for noteskins. So I just tweaked it's fallback to point towards Metal and it worked. Why reinvent the wheel right?

-----Metal-----

-Better matched the colors of the hold bottomcaps.

-Mirrored the hold bottomcaps horizontally so the lighting doesn't look off.

-The same active roll bottomcap fix as Cel as they use the same roll graphics.

-Fixed the hold's slight gradient mismatches at the top loop point like Cel too.

-----Robot-----

-The same active roll bottomcap fix as Cel as they use the same roll graphics.

-Added SugoiFactory's white fantastic graphic and fallback explosion files from Metal for consistency: https://github.com/itgmania/itgmania/commit/18179d95cb66b2061c81b467535c6dcdfb8a55a6

-Added the same lift code that Peter added to Metal also for consistency: https://github.com/itgmania/itgmania/commit/18179d95cb66b2061c81b467535c6dcdfb8a55a6

----Vivid-----

-The same active roll bottomcap fix as Cel as they use the same roll graphics.

-Added the white fantastic graphic and fallback explosion file from metal.

-Copied over the arrow model as a lift model and tweaked it's code to point to the new lift stuff.

-Added the same lift code that Peter added to Metal. But then needed to edit-create lift graphics from the main arrow graphics to match.

====================

Enjoy!

<3 PkGam
