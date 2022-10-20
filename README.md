# FL2K TBC Player

A Simple TBC playback utility, currently only CLI (Command Line Interface)

This will later be both GUI/CLI.

## What is a TBC? 

Its a digital Time Base Corrected video file thats in 1 file for Composite streams and 2 files for S-Video streams.

## How do I get a TBC file? 

Via [VHS-Decode](https://github.com/oyvindln/vhs-decode) (Tape Decoding) and [LD-Decode](https://github.com/happycube/ld-decode) (LaserDisk Decoding) or [CVBS-Decode](https://github.com/oyvindln/vhs-decode/wiki/CVBS-Composite-Decode) (Composite Decoding) 

# Setup 

## Windows 

Simply download the windows relisese.

Decompress the .zip file.

For GUI users 

Oopen the fl2k-tbc-player.bat file.

For CLI users 

Open an CMD Window and open the directory with CD once inside simply use fl2k-tbc-player.exe to open the software.

## Linux

Downlaod the software 

`git clone https://github.com/vrunk11/fl2k-tbc-player/.git fl2k-tbc-player`

Enter into the install directory 

`cd fl2k-tbc-player`

Build the driver

'sudo make fl2k-tbc-player`

Run the software with 

`fl2k-tbc-player [insurt example arguments]`

cd make 

## MacOS 

Support yet to be Implimented.

# Usage 

As its an VGA RGB adapter there is 3 ADC's

`-d` device_index (default: 0)

`-s` samplerate (default: 100 MS/s) you can write `-s ntsc` or `-s pal`

`-u` Set sample type to unsigned

`-R` filename (use '-' to read from stdin)

`-G` filename (use '-' to read from stdin)

`-G` filename (use '-' to read from stdin)

`-R16` (convert bits 16 to 8)

`-G16` (convert bits 16 to 8)

`-B16` (convert bits 16 to 8)

`-tbcR` interpret R as tbc file

`-tbcG` interpret G as tbc file

`-tbcB` interpret B as tbc file

#### Based off the [osmo_fl2K project](https://osmocom.org/projects/osmo-fl2k/wiki) software.
