# th.pitchshift

**Please consider to download and donate via http://gumroad.com/tmhglnd**

A mono time domain pitch shifter abstractionfor Max

## About

This is a mono time domain pitch shifter that uses the doppler effect for shifting up the pitch. Use a midi integer value to set the note (no shifting = 48), or use the attribute shiftratio to shift with ratio values (where no shift = 1, one octave up = 2, one octave down = 0.5, etc.). Also works with floating point midi values for microtonality. You can combine the original with the shifted sound with the wet attribute. Change the window size to fit your sound source, usually smaller window sizes sound better on percussive instruments (less delay) but result in more artifacts. Longer window sizes work well on sustaining sounds. All parameters can be initialized with attributes or adjusted by a message.

## Sources used

http://msp.ucsd.edu/techniques/v0.11/book-html/node115.html

## Install

```
1. download zip 
2. unzip in Max searchpath (eg. on MacOS ~/Documents/Max 8/Library)
3. restart Max8
```

```
1. open terminal
2. navigate to Max searchpath (eg. on MacOS cd ~/Documents/Max\ 8/Library)
3. $ git clone https://github.com/tmhglnd/th.pitchshift.git
```
