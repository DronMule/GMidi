# General MIDI for Kontakt
This is just an arrange of Kontakt sampled instruments configured into an instrument bank to fit General MIDI Soundset. 
Kontakt Instrument Banks responds Program Changes from MIDI, so you could play a regular MIDI file from your DAW or MIDI Keyboard. Keep in mind that Kontakt Instrument Banks only allow 128 instruments, there's no variations patches like in General Midi 2 or Roland GS.
The nki files are a collection from [bigcat instruments](http://bigcatinstruments.blogspot.com/2014/08/gm-midi-instruments-for-kontakt.html) list (all credits listed there). I just included the least in size, so you can find more samples with better quality (and much bigger in size) listed there, so you can replace an instrument if you don't like any included here.


This contains two files and a subdirectory:
- General MIDI Instruments Bank.nkb: 
    <p>This contains the whole 128 instruments loaded, add as many as you need in a multi, for Standard MIDI files you need a maximum of 16, one bank per MIDI channel. Remember that you need to reserve a MIDI channel for Drum Kit, so probably you may add the following bank instead.
- General MIDI Drum Kits Bank.nkb:
    <p>This instrument bank just contains a pair of Standard Drum Kits, you need to load this one and set up MIDI Input to Channel 10.
- GM: 
    <p>This subdirectory contains nki files used by banks.
        
You need to have Full version of Kontatk.
        
This repository is using Git LFS

        
