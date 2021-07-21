# ROLI-toys

Small apps for the ROLI Lightpad.

To install:
Copy the desired .littlefoot file to your Documents/ROLI/Littlefoot/ directory.
Script should appear in the ROLI Dashboard.

## Amuse
A 32-bit shift array with selectable tap locations, based on the Triadex Muse.
Outputs MIDI note over USB.
Note seclection available through the ROLI Dashboard.

### Physical Button:

Toggles playback on and off. MIDI panic.

### Touch Controls:

Track - Place selected tap.

Slider - Speed.

Touch Pads - Select tap.
Red and Blue are feedback taps.
Green and Yellow are output taps.

Touch with three fingers and release: Initialize controls and randomize memory.

## Shift Register
A 16-bit shift array with memory corruption, based on the Turing Machine eurorack module by Tom Whitwell.
Outputs MIDI note with velocity over USB.
Fixed velocity option available through the ROLI Dashboard.

### Physical Button:

Toggles playback on and off. MIDI panic.

### Touch Controls:

X-axis - Speed

Y-axis - Probability that a shifted bit will be inverted.

Touch with three fingers and release: Reset

## Tilt-O-Whirl
A 2D physics simulator, based on the Tombola sequencer by Teenage Engineering.
Up to eight balls roll on a tilted plate, triggering MIDI notes when they strike the edges.
Gradient indicates the direction of the tilt.
Outputs MIDI note over USB. Options available through the ROLI Dashboard.

### Physical Button:

Delete all balls. MIDI panic.

### Touch Controls:

Tap - Spawn a new ball

Drag and release - Throw a new ball
