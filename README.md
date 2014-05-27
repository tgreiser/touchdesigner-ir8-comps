Components for TouchDesigner and Rouge A/V platforms. Of interest to VJs and video artists.

* flakeD          - *updated* A lightsynth that generates snowflake inspired patterns and LSystems

* RougeComposions - Generators for the Rouge VJ system - see: http://www.maryfranck.net/rouge/

* RougeFilters    - Filters for the Rouge VJ system, some of them ported from other people's work

* AutoLevelAdjust - Analyze a 60 second buffer of audio. Scale the audio level to maintain a peak volume of 1.

* iCONTROLS       - MIDI map for iCON i-Controls, a very nice compact MIDI controller with faders, knobs and buttons.

* ir8Eq           - Very simple and efficient 3 band EQ to CHOP

* ir8TriggerEq    - Tunable 3 band EQ that triggers ON/OFF CHOP states. Refer to the Text DAT for instructions.

* perlinTweak     - Based on PerlinNoise3dShader COMP - this version has no UI, but uses CHOP input data instead
                  Also, no background, composite the output TOP over whatever you like.

* PyramidMap      - This is an example of a texturing tool for use with UV mapping. I created a UV map for a 
                  pyramid 3d model and exported both together to a FBX file. This black box component takes
                  4 TOP inputs, and transforms and composites them onto each unfolded face in the UV map. 
                  In a live system, this would be color mapped onto a Phong, which is then applied to you
                  imported Geometry (model + UV).

* SixAxisReflection - Black box component to render content with reflectional and rotational symmetry along 6 axes. Render the hexagon output from the component and then apply SixAxisReflection/material to your Geometry. (See: SixAxisExample.toe)

* TOPtoDAT        - Stupid touch tricks. This is a nicely formatted DAT for pixel mapping content from a TOP.
                    Not high performance, intended to be used with LED screens maybe 64x64.

* TOPtoSOP        - Stupid touch tricks. Turn a TOP into a SOP. The only way I know to sort of texture inside
                  the SOP domain (without rendering). Useful for pixel mapping.

* tuio-25d        - Quick and dirty fix to make the existing tuio component work in "2.5 D" mode

* tuioToggleutton - For my LoveWave/SpacePalette build, I used this for the "buttons". A small tuio panel provides
                  the first input, and the second input is a script to run. This acts like a toggle button where
                  the first time you press it, the state changes to 1, the second time the state changes back to 0.

* Fun with TUIO   - Checkout http://nosuch.com/tjt/multimultitouchtouch/index.html for some great software
                  that will turn a wooden frame and a kinect into a TUIO/OSC messages.


You can see some projects I've done using these tools on my youtube channel.
http://www.youtube.com/user/AuralFixationMT/videos

Thanks to other developers who shared their tools and techniques:

* t3kt - http://t3kt.net/
* Mary Franck - http://www.maryfranck.net/rouge/
* Scott Pagano - http://www.neither-field.com/
* The authors of Mixxa - http://www.derivative.ca/wiki088/index.php?title=Mixxa2013
* Barakooda Kor - http://www.youtube.com/user/Barakooda3D

License: Copyleft Non-commercial use only - intended for educational and entertainment purposes. May contain a few pieces of derivative works under unknown license. Please let me know if you don't want your code used in this way. If you benefit from this tool and want to support my work I accept donations:

Bitcoin: 1PgpUiZXuCUzfLW2csymySiXEK9rKHUNaN
