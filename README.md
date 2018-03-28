NEATEvolve
MarI/O by SethBling - With working, more effective, save and load functions

The original MarI/O by SethBling over at https://pastebin.com/ZZmSNaHX crashes everytime you try to load your bot state.
So I decided to lear some lua and make a more efficient save and load function.
It now saves the whole pool.species table in a file called species.lua,
but still uses the original save file for some other small but important values.

In order to save multiple bot states you'll have to manually make a subfolder and copy
neatevolve.lua, SMB1-1.state/DP1.state, and saveTable.lua into the folder.
Then normally drag neatevolve into the emulator and you'll have a second bot state separate from the first one.

I may update the code where saving multiple bot states will be automated.

Anyway, enjoy. And please do report any problems you might have to me.
