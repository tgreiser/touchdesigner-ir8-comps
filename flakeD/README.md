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
TouchDesigner or TouchPlayer (Windows only, sorry) - https://www.derivative.ca//088/Downloads/Default.asp

Lsystem Rules:
Write your own rules, and save a text file in the LSystems directory. Please note, if you have systems that are sigificantly more complex, it is highly recommended to set a condition to limit the max generations on the rules. For example, see travellers.txt

F=F-F++F-F:t<4
On the end, :t<4 is the condition. This says, execute this rule while generations are less than 4. Without this safety condition in place, you will find that this LSystem will cause TouchDesigner to crash on most systems if you have your generations slider set above 4 or 5.

Examples of output:
http://www.youtube.com/watch?v=38LU8TNMFR0
http://www.youtube.com/watch?v=BOmZIwYflq0

Thanks to other developers who shared their tools and techniques:
* t3kt - http://t3kt.net/
* Mary Franck - http://www.maryfranck.net/rouge/
* Scott Pagano - http://www.neither-field.com/
* The authors of Mixxa - http://www.derivative.ca/wiki088/index.php?title=Mixxa2013
* Barakooda Kor - http://www.youtube.com/user/Barakooda3D

License: Copyleft
Non-commercial use only - intended for educational and entertainment purposes. May contain a few pieces of derivative works under unknown license. Please let me know if you don't want your code used in this way. If you benefit from this tool and want to support my work I accept donations:

Bitcoin:
1PgpUiZXuCUzfLW2csymySiXEK9rKHUNaN
