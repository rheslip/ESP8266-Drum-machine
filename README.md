909 style drum machine for ESP8266.
modification of Jan Ostman's code http://blog.dspsynth.eu/audio-hacking-on-the-esp8266/
this version uses trigger inputs instead of MIDI.
trigger inputs should be buffered so you don't exceed 3.3v.
I used NPN transistors - 100k to base, emitter grounded, collector to the port pin which has pullups enabled.
also added an audio mute to avoid the glitching that happens every once in a while.

R Heslip May 2018

