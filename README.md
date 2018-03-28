# NEATEvolve [<img src="https://camo.githubusercontent.com/326dd5cd5aa07adca69ff20e033fe21f663fb920/68747470733a2f2f696d6167652e666c617469636f6e2e636f6d2f69636f6e732f706e672f3132382f3130392f3130393631322e706e67" alt="image" title="Download" data-canonical-src="https://image.flaticon.com/icons/png/128/109/109612.png" width="35" height="35">](https://goo.gl/znNdj9)

MarI/O by SethBling - With working, more effective, save and load functions

The original MarI/O by SethBling over at https://pastebin.com/ZZmSNaHX crashes everytime you try to load your bot state.
So I decided to lear some lua and make a more efficient save and load function.
It now saves the whole pool.species table in a file called species.lua,
but still uses the original save file for some other small but important values.

Setup:
Download "neatevolve.lua" and "saveTable.lua", and put them into the root folder of BizHawk (where EmuHawk.exe is located)
Then drag neatevolve.lua into the emulator window after the game has been launched.
Other than that, follow this tutorial for more setup info http://glenn-roberts.com/posts/tech/2015/07/08/neuroevolution-with-mario.html

In order to save multiple bot states you'll have to manually make a subfolder and copy
neatevolve.lua, SMB1-1.state/DP1.state, and saveTable.lua into the folder.
Then normally drag neatevolve into the emulator and you'll have a second bot state separate from the first one.

I may update the code where saving multiple bot states will be automated.

Anyway, enjoy. And please do report any problems you might have to me.

[Amount of Downloads](https://goo.gl/#analytics/goo.gl/znNdj9/all_time)
