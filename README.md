# sm64-pc-hq-sounds
This is a project aiming to bring high quality sounds to Super Mario 64 for PC

Currently, this mod only works on EX branch of the port, but can be built with other forks.

NOTICE: If you're coming from the channel Unreal, go to this video for a non-crappy comparison video. That guy seriously bitcrunched his audio to make it even harder to differentiate.
https://www.youtube.com/watch?v=zDH45ip2TUw

### Credits


<pre>VGM Sources Discord, for most of the instruments:
G-Boy, Mr. Miles, Infomanic95, michael102022, armageddon13, onion, Liam, Hinzoto, Aqua

General Sounds:
Map, Desko, Sean the Bermanator, Shutdown, Sound Effects Wiki,</pre>


### Sources

<pre>Super Smash Bros. Melee                Most of the mario voices
AKAI S1000                                  Banjo 1
E-MU Proteus/1                              Harpsikord
Korg 01R/W                                  Sawtooth Synth
Super Mario 64 OST                          "It's-a me, Mario!"
Super Mario World                           Yoshi
Nintendo Puzzle Collection                  Mario "Yahoo!"
Roland SC-88                                A good chunk of the instruments
Roland SC-55                                Pat, Menu Organ
Roland JD-990                               Crystal Rhodes, Lyric Pipe
Samplecell Vol.1                            A good chunk of the instruments
Sonic Images Library Vol. 1                 Monk Choir, Tambourine, Steel Drum
Sound Ideas Series 6000                     A good chunk of the general sounds
Voice Spectral Vol. 1                       Yelp, Pah Voice
Spectrasonic Bass Legends                   Accoustic Bass, Funk Bass
A Poke in the Ear with a Sharp Stick        Metal Rimshot, Kick Drum 2, Convolution, Lahna
ILIO Synclavier Percussion                  Timpani
Ensoniq EQ80                                Whistle
The Denny Jaeger Private Collection         Trombone
Prosonus Orchestral Hanz Zimmer Guitars     Hat 1+2, Cymbal, 
Hollywood Premiere Edition Vol. 1           Ukiki
Warner Bros. Sound Effect Library           A good chunk of the general sounds
Universal Studios Sound Effect Library      Bowser Roar, Boing 1, Boing 2 (Unused), Box Break</pre>


### Installation/Building

To use this mod, download from the release section and make sure your EX build has external resources enabled. Put it in your res folder (still zipped) and launch the game. If you encounter any audio clipping, lower your sfx volume. If the mod did not work out for any reason, continue reading.

To build this in with non-EX branches, or if you want to make changes to the mod, grab the contents of "Sounds for building (Mono)" and put them in your builder's sound/samples folder (Not the one inside your build folder, if you see aifc's you're in the wrong place. If there isn't a samples folder, make one). 

If you plan on sharing it, make sure you have external resources turned on so you can seperate the base content. Once done building, go to your res folder and open base.zip. In your sounds folder there should be 2 sound_data files. Grab them and zip them up with the file structure they were in, leaving them the only files in the whole pack.


### Notes

"HQ Sounds" is the archive of sounds that have been finalized to be cleaned up and as high quality as possible for any use. The "Sounds for Building" are exactly what the name says: They are for building with the various branches.

The Mono version is, well, mono. It has the fewest sounds for optimization, and is intended to be compatible with every branch. The Experimental version contains edits to the soundbanks to get around certain limitations, but as of now I can't find a way to get it to work. The Stereo version is a future proof version of HQ Sounds in the hex format, intended for whenever SM64 gets a proper audio engine.

Refer to the Render96 spreadsheet to know what sounds have a source or are upsampled, as well as the complete listing of every sound in the game. To get the vanilla sounds from the game, go to your sound/samples folder. If there is no folder, build the game (You do not have to wait till it's finished building, they are extracted at the start of the process)

https://docs.google.com/spreadsheets/d/1HB6RZmMlAcXAmR2IsTtpD7jrIylTjoCoRf0qfAICYik

For some personal discoveries about the soundbanks I found while trying to get around the limitations of the engine, as well as the quirks and stats of every instrument in the game, have this exhaustive spreadsheet

https://docs.google.com/spreadsheets/d/1dG3uEGYNnsd7gzLKqhknSeFj4g3C-B1I5IiXFcrf0gg


### Stats

<pre>Catagorized:          212/217 (97.6%)
Sources:              111/217 (51.2%)
Close enough's        26/217  (12%)
Upsampled:            53/217  (24.4%)
Sources + Upsampled:  3/217   (1.3%)

Sounds:               51/137  (37.2%)
Instruments:          58/80   (72.5%)

Total:                193/217 (88.9%)</pre>


### Future

This pack is to be updated alongside Render96 and it's updates, this is just a transfer of my work and several others (excluding the new sound system) to be compatible with EX.
