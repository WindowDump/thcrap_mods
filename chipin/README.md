# Imperishable Night Chipmusic Mod

A music mod for Touhou Eiyashou ~ Imperishable Night (aka Touhou 8), using [thcrap](https://www.thpatch.net/wiki/Touhou_Patch_Center:Download). Features 21 *different* songs, updated in-game text, and a new script for Reimu & Yukari's (AKA Barrier Team, Barrier Gang) scenario which is hopefully entertaining.

MP3's have been processed with [mp3gain](http://mp3gain.sourceforge.net/), so the absolute volume level should be mostly consistent between files. The menu tune is one of the louder ones, so set your volume there and it should be fine throughout the mod. All of the songs have different amounts of compression applied to them, however, so apparent loudness is not going to be consistent.

This patch contains curse words. They're mostly in the Extra Stage. Consider yourself warned.

Slapped together *with love* using pcutmp3, mp3gain, and GIMP.

## Concept

Why *Imperishable Night*? Why chipmusic?

Quite simply, because I've developed an unhealthy obsession with Touhou and IN is my favorite so far, because I like rooting through my collection of chipmusic, and because thcrap made doing all of this far easier than it should have been. Don't hate the mod tools, hate the modder.

Also my current working knowledge of Touhou lore suggests that not only is Yukari likely to collect weird music from the outside world, she's also the most likely to find reasons to force people to listen to it for her own amusement. That's the starting point for the script, and things flowed from there.

I also wanted to do a proof of concept mod to show that thcrap can be the jumping off point for your own bizarre Touhou mods. Your only limitations are the number of lines of dialog because otherwise the demos desync.

## Copyright Notice

I've done my best to choose freely available music for this mod - it's possible to download the original music files in most cases and edit the mod together yourself, the hard part has already been done. These files are included as a convenience because it's very annoying to do it yourself.

Wherever applicable, the licesnses of the original release should overwrite any other licenses and copyrights applied to the contents of this mod. This is to say: I do not own the music or the derivative edits of it for this mod. Please do not sell this mod or attempt to claim any musical works as your own.

Just keep it doujin.

## Installation Instructions

0. Get thcrap set up to work with IN. [Here's the link again.](https://www.thpatch.net/wiki/Touhou_Patch_Center:Download)

1. Make sure your 

2. Use the thcrap configurator to add the patches to the new or existing configuration of your choice! Look for "Window Dump's Mods" towards the bottom of the list. Be sure to select the patch last (after the language of your choice, though this mod is in English) so you get the new script and song titles.

3. Alternatively, add these patches to an existing configuration:

```
{
  "archive": "WindowDump/chipin_base/"
},
{
  "archive": "WindowDump/chipin/"
}
```

Typos? Bugs? Questions? Complaints? Bug Window Dump on the Touhou Patch Center Discord server! https://discord.thpatch.net/

# Music Credits & Timecode Crop Information

If you want to be surprised by the music choices don't read these.

Using pcutmp3 is a little annoying due to its command-line interface for modifying media files. If you can get your hands on lossless audio sources, I'd *strongly* recommend playing with those and then encoding to OGG/MP3 afterwards.

It was pretty hard to get pcutmp3 to do what I wanted, so I'm including the crop information. Please don't try to use mp3DirectCut, it doesn't cut sample-accurately and the files it generates will not play and loop properly in thcrap despite what XMPlay and foobar2000 tell you.

Also remember that you can use timecodes instead of sample numbers.

## Main Menu

Phlogiston - Cyber-Axe Café, from Mode 3 (2007), 8BP074

http://www.8bitpeoples.com/products/520256-phlogiston-mode-3

Crops:

1:0.50s-49.58s
2:49.58s-1m48.49s

## Stage 1

Trash80 - Icarus, from Icarus (2008), 8BP086

http://www.8bitpeoples.com/products/520270-trash80-icarus

Crops:

1:44.18s-1m14.42s
2:1m14.42s-2m28.84s

Mr. Spastic - Sloppy, from Claps and Leads (2009), 8BP096

http://www.8bitpeoples.com/products/520390-mr-spastic-claps-and-leads

Crops:

1:28.47s-49.27s
2:49.27s-2m07.37s

## Stage 2

knife city - precious jewel, from precious jewel (2014), 8BP133

http://www.8bitpeoples.com/products/534586-knife-city-precious-jewel

Crops:

1:1m09.12s-1m16.80s
2:1m16.80s-3m35.04s

A.M.U - Speech Machine Failure, from Diamond (2010), 8BP112

http://www.8bitpeoples.com/products/520413-a-m-u-diamond

Crops:

1:3m59.12s-4m58.21s
2:4m58.21s-5m56.38s

## Stage 3

Psilodump - Låtsades Krama, from Memory Loss (2004), 8BP040

http://www.8bitpeoples.com/products/520173-psilodump-memory-loss

Remaster: https://psilodump.store/album/memory-loss-ep-redump

Crops:

1:0s-7.92s
2:38.63s-2m33.84s

Din Stalker - Ohne Zuschlag, from Filesystems (2005), 8BP048

http://www.8bitpeoples.com/products/520231-the-x-dump-filesystems

Crops:

1:6.71s-1m0.79s
2:1m0.79s-1m54.86s

## Stage 4

Nullsleep - Dirty ROM Dance Mix, from Electric Heart Strike (2007), 8BP077

http://www.8bitpeoples.com/products/520259-nullsleep-electric-heart-strike

Crops:

1:42.00s-1m29.23s
2:1m29.23s-2m21.74s

Bomb Boy - Back Alley Clash, from SOUNDSHOCK 2: FM FUNK TERROR!! (2012), UBI044

http://ubiktune.com/releases/ubi044-various-artists-soundshock-2-fm-funk-terrror

Crops:

1:1m57.13s-2m28.09s
2:2m28.09s-4m35.80s

http://ubiktune.com/releases/ubi044-various-artists-soundshock-2-fm-funk-terrror

Radlib - Zoomin' Nature (CTRIX SEES TRICKS SB16 MIXXX 2013), from 2 Le Chip 2 Quit (2013), 8BP127

http://www.8bitpeoples.com/products/520441-radlib-2-le-chip-2-quit

Crops:

1:30.78s-1m50.52s
2:1m50.52s-3m17.51s

## Stage 5

Doomcloud - Welcome to Dudley Town, from The Masquerade (2013), 8BP131

http://www.8bitpeoples.com/products/521174-doomcloud-the-masquerade

Crops:

1:49.03s-1m01.00s
2:1m01.00s-3m26.99s

Sulumi - Jurchen (Covox Remix), from Music Offers the Third Eye (2013), 8BP128

http://www.8bitpeoples.com/products/520443-sulumi-music-offers-the-third-eye

Crops:

1:2m15.97s-2m28.01s
2:2m58.00s-5m24.02s

## Final A & B

IAYD - Redshift, from Supergalactic (2009), 8BP098

http://www.8bitpeoples.com/products/520392-iayd-supergalactic

Crops:

1:25.73s-1m4.08s
2:1m4.08s-2m33.70s

Anamanaguchi - Mess, single released in summer 2010

http://www.anamanaguchi.com/singles/

Crops:

1:0.29s-30.01s
2:30.01s-2m38.04s

Bonus Meme: https://www.youtube.com/watch?v=e60JlM6ZXHc

Starscream - Gravity in Terms of Space-Time, from Future, and It Doesn't Work (2009), 8BP099

http://www.8bitpeoples.com/products/520393-starscream-future-and-it-doesnt-work

Crops:

1:57.18s-1m25.65s
2:1m25.65s-3m43.94s

Goto80 - Llamawarning, from Contech (2005), 8BP044

http://www.8bitpeoples.com/products/520177-goto80-contech

Crops:

1:30.35s-50.63s
2:1m12.36s-2m13.67s

## Extra Stage

videogame orchestra - mk ultra, from RIOT (2009), II26

http://iimusic.net/
http://iimusic.net/dl.php?d=26_RIOT.zip

Crops:

1:0s-13.61s
2:13.61s-2m42.38s

Rainbowdragoneyes - The Primordial Booze, from The Primordial Booze (2011), 8BP117

http://www.8bitpeoples.com/products/520425-rainbowdragoneyes-the-primordial-booze

Lyrics and other info: https://rainbowdragoneyes.bandcamp.com/track/the-primordial-booze

Crops:

1:0s-25.00s
2:25.00s-2m39.35s

## Ending

Starscream - Kepler's Star Catalog, from Future, and It Doesn't Work (2009), 8BP099

http://www.8bitpeoples.com/products/520393-starscream-future-and-it-doesnt-work

Crops:

1:26.93s-1m22.65s
2:1m22.65s-2m18.34s

## Staff Roll

Nullsleep - Galaxy Tonite [DMG Version], from Unconditional Acceleration (2008), 8BP088

http://www.8bitpeoples.com/products/520272-nullsleep-unconditional-acceleration

Crops:

1:0s-13.14s
2:13.14s-2m24.40s

## Last Word

Sabrepulse - We Are Hi-Speed [Saskrotch's Nurrrbody in This Bitch Get Chipsy Remix], from I'll Have You Naked by the End of This ROM (2009), 8BP102

http://www.8bitpeoples.com/products/520399-saskrotch-ill-have-you-naked-by-the-end-of-this-rom

Bonus Tracks: https://saskrotch.bandcamp.com/album/ill-have-you-naked-by-the-end-of-this-rom

Crops:

1:32.03s-1m04.03s
2:1m04.03s-2m47.99s

# Greetz

Everyone whose music appears in this mod - you've given me years of enjoyment! I hope I can do the same thing for whoever bothers to use this.

ChipMusic.org

[Touhou Patch Center](https://www.thpatch.net/wiki/Touhou_Patch_Center:Main_page)

Mandalore's Anime Containment

GST大好き

Anyone else who actually bothered to download this meme. Bug me on Discord and I'll put your name here for the screencap.