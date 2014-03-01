touchdesginer-ir8-comps
=======================

Components for TouchDesigner and Rogue A/V platforms. Of interest to VJs and video artists.

flakeD          - A lightsynth that generates snowflake inspired patterns and LSystems

RougeComposions - Generators for the Rouge VJ system - see: http://www.maryfranck.net/rouge/

RougeFilters    - Filters for the Rouge VJ system, some of them ported from other people's work

ir8Eq           - Very simple and efficient 3 band EQ to CHOP

ir8TriggerEq    - Tunable 3 band EQ that triggers ON/OFF CHOP states. Refer to the Text DAT for instructions.

perlinTweak     - Based on PerlinNoise3dShader COMP - this version has no UI, but uses CHOP input data instead
                  Also, no background, composite the output TOP over whatever you like.

PyramidMap      - This is an example of a texturing tool for use with UV mapping. I created a UV map for a 
                  pyramid 3d model and exported both together to a FBX file. This black box component takes
                  4 TOP inputs, and transforms and composites them onto each unfolded face in the UV map. 
                  In a live system, this would be color mapped onto a Phong, which is then applied to you
                  imported Geometry (model + UV).

tuio-25d        - Quick and dirty fix to make the existing tuio component work in "2.5 D" mode

tuioToggleutton - For my LoveWave/SpacePalette build, I used this for the "buttons". A small tuio panel provides
                  the first input, and the second input is a script to run. This acts like a toggle button where
                  the first time you press it, the state changes to 1, the second time the state changes back to 0.

Fun with TUIO   - Checkout http://nosuch.com/tjt/multimultitouchtouch/index.html for some great software
                  that will turn a wooden frame and a kinect into a TUIO/OSC messages.
