A light-synth based on L-Systems and inspired by snowflakes. Features a performance control panel, several modulation sources and (limited) MIDI support for TouchDesigner users.

This is built in TouchDesigner, a commercial system, but there is a non-commercial version available, and this should work in the TouchPlayer environment as well. It can be a little system intensive so 64 bit is recommended for best results.

flakedD.35
* 4 lfo modulators
* fully modular - add your own LSystem rules (see below)
* on screen projector controls / can now support TouchPlayer
* Now includes mappable audio reactivity
* 9 band EQ - pick freq1 (lowest frequency) through freq9 (highest frequency) and control the master volume.
* midi - if you have a midimap set up, this uses lots of sliders or knobs. You can assign midi (slider) or audioMidi (knob) to your midimap names at /flaked/settings. This table is kind of the brains of the app.

Requirements:
TouchDesigner or TouchPlayer - https://www.derivative.ca//088/Downloads/Default.asp

Lsystem Rules:
Write your own rules, and save a text file in the LSystems directory. Please note, if you have systems that are sigificantly more complex, it is highly recommended to set a condition to limit the max generations on the rules. For example, see travellers.txt

F=F-F++F-F:t<4
On the end, :t<4 is the condition. This says, execute this rule while generations are less than 4. Without this safety condition in place, you will find that this LSystem will cause TouchDesigner to crash on most systems if you have your generations slider set above 4 or 5.

Examples of output:
http://www.youtube.com/watch?v=38LU8TNMFR0
http://www.youtube.com/watch?v=BOmZIwYflq0
