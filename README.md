# thcrap_mods

Modifications for use with the [Touhou Community Reliant Auto Patcher](https://www.thpatch.net/wiki/Touhou_Patch_Center:Download), because I keep making them.

## Complaints

I think GitHub emails me if you make an issue, so you can do that if you really want. I also lurk on the [Touhou Patch Center Discord](https://discord.thpatch.net/), which may be quicker or less formal depending on your needs.

# chipin

Chipmusic Mod for Touhou Eiyashou ~ Imperishable Night, featuring 21 *different* tunes and a new script for the Barrier Team which is hopefully funny and enjoyable. Intended as a showcase for the capabilities of the BGM modification module of thcrap and the process needed to use it optimally.

Music included is all freely available online - I did my best to avoid choosing tracks which are only available on paid releases. If you want to adjust the loop points, I have also included the loop points I used with pcutmp3 to create the actual files.

# chipin_base

Base files for chipin, including the new script and images. Best practice is to separate these from audio files in the event that lossless files are available for redistribution. Also allows you to get the new dialogue without changing the music!

# EoSD_Retexture

Graphical files from the [EoSD Rexture Patch](https://en.touhouwiki.net/wiki/Game_Tools_and_Modifications#Retexture_Patch) by [Emarrel](http://www.shrinemaiden.org/forum/index.php?action=profile;u=160), dumped with [thtk](https://github.com/thpatch/thtk). Replaces most of the graphical assets, including in-game sprites, level backgrounds, and HUD elements. I have made a few minor changes to make this compatible with thcrap - specifically, I have added alpha channels to eff04, eff05, eff06, eff07, and stg6bg; and I had to scale down eff01 because Rumia can't handle a 1024 x 1024 texture.

This patch should be considered a historical curiosity and is not recommended for general use. I do not take any responsibility for font choice or graphical changes made. Also note that this patch significantly increase load times, which may result in instability on some systems.

# EoSD_Retexture_Hitbox

The files from the visible hitbox option from the above retexture mod.

# Static_English

Replaces translations and scripts with those from the old static patches, developed by Simon Elén and the Touhou Wiki. These date back to about 2006 and feature very old translations and decisions. The most significant changes are the font used (Arial, MS UI Gothic), and the choice to subtitle most text in the game rather than outright replacing it as the current thpatch translation does. This was mostly done to try to get Tom to switch to thcrap, but maybe it can be fun to root through and see how much things have changed, for historical purposes.

Note that because all of this content was posted on the Touhou Wiki, it should be within the license to redistribute it in this way. Other old static translations appear to not be under this kind of permissive license, so I doubt I'll do this in the future unless someone actually wants this.