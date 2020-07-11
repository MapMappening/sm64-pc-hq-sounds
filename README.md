# sm64-pc-hq-sounds
This is a project aiming to bring high quality sounds to Super Mario 64 for PC

Currently, this mod only works on EX branch of the port, but can be built with other forks. PAK versions will be coming once I have the time.
To use this mod, make sure your nightly build has external resources enabled. Put it in your res folder (still zipped) and launch the game. If you encounter any audio clipping, lower your sfx volume.

To build this in with non-EX branches, or if you want to make changes to the mod, grab the contents of "Sounds for building" and put them in your builder's sound/samples folder (Not the one inside your build folder, if you see aifc's you're in the wrong place. If there isn't a samples folder, make one). 

If you plan on sharing it, make sure you have external resources turned on so you can seperate the base content. Once done building, go to your res folder and open base.zip. In your sounds folder there should be 2 sound_data files. Grab them and zip them up with the file structure they were in, leaving them the only files in the whole pack.

The "Sounds for building" has certain differences with the "HQ Sounds" folder, as they are converted to mono, don't have every sound, and some are sampled lower to compensate for the audio engine. "HQ Sounds" is for future builds that support a more robust audio system.

The "Original Sounds" are there for comparison and organization, as well as showing how many sounds there are left to go.
