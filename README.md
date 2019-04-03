# thcrap_mods

Modifications for use with the [Touhou Community Reliant Auto Patcher](https://www.thpatch.net/wiki/Touhou_Patch_Center:Download), because I keep making them.

## Complaints

I think GitHub emails me if you make an issue, so you can do that if you really want. I also lurk on the [Touhou Patch Center Discord](https://discord.thpatch.net/), which may be quicker or less formal depending on your needs.

# chipin

Chipmusic Mod for Touhou Eiyashou ~ Imperishable Night, featuring 21 *different* tunes and a new script for the Barrier Team which is hopefully funny and enjoyable. Intended as a showcase for the capabilities of the BGM modification module of thcrap and the process needed to use it optimally.

Music included is all freely available online - I did my best to avoid choosing tracks which are only available on paid releases. If you want to adjust the loop points, I have also included the loop points I used with pcutmp3 to create the actual files.

# chipin_base

Base files for chipin, including the new script and images. Best practice is to separate these from audio files in the event that lossless files are available for redistribution.

# EoSD_Retexture

Graphical files from the [EoSD Rexture Patch](https://en.touhouwiki.net/wiki/Game_Tools_and_Modifications#Retexture_Patch) by [Emarrel](http://www.shrinemaiden.org/forum/index.php?action=profile;u=160), dumped with [thtk]
(https://github.com/thpatch/thtk). Replaces most of the graphical assets, including in-game sprites, level backgrounds, and HUD elements. I have made a few minor changes to make this compatible with thcrap - specifically, I have added alpha channels to eff04, eff05, eff06, eff07, and stg6bg; and I had to scale down eff01 because Rumia can't handle a 1024 x 1024 texture.

This patch should be considered a historical curiosity and is not recommended for general use. I do not take any responsibility for font choice or graphical changes made. Also note that this patch significantly increase load times, which may result in instability on some systems.

# EoSD_Retexture_Hitbox

The files from the visible hitbox option from the above retexture mod.