# LindenMouse

LindenMouse is a Max/MSP instrument that uses mouse clicks and the position of your point on screen to generate simple harmonies with FM synthesis.

## Installation 

Open the LindenMouse.maxpat file and use like any other Max/MSP file.

## Usage

LindenMouse will start generating tones as soon as the sound engine is turned on.

Clicking anywhere on the screen will generate a tone. Moving left and right determines the fundamental frequency and moving up and down modifies the LFO. The pitch increases as you move towards the right. The LFO increases as you move towards the bottom of your screen.

### Modes

Choosing a different mode will influence how the Mousestate object in Max will interpret your location on screen. 

#### Mode 0

Mouse position is relative to your screen.

#### Mode 1 

Mouse position is relative to the LindenMouse patcher.

#### Mode 2 

Mouse position is relative to the front most patcher in use on Max.
