# ROLI-toys

Small apps for the ROLI Lightpad.

To install:
Copy the desired .littlefoot file to your Documents/ROLI/Littlefoot/ directory.
Script should appear in the ROLI Dashboard.

## Amuse
A 32-bit shift array with selectable tap locations, based on the Triadex Muse.
Outputs MIDI notes.
Options available through the ROLI Dashboard.

### Controls:

Physical Button - Play/Pause. MIDI panic.

Track - Place selected tap.

Slider - Speed.

Touch Pads - Select tap.
Red and Blue are feedback taps.
Green and Yellow are output taps.

Touch with three fingers and release: Randomize memory.

## Bresenham
A four-track Euclidean rhythm generator.
Top-left number indicates the number of pulses on the active track.
Top-right number indicates the length of the active track.
Color of the top-right number indicates the active track.
Outputs MIDI notes.
Options available through the ROLI Dashboard.

### Controls:

Physical Button - Select active track.

Tap top of digit - Increase digit.

Tap bottom of digit - Decrease digit.

Slider - Speed.

Touch Pads - Play/Stop track.

## Gauss
A MIDI CC generator using the Gauss continued fraction map.
Outputs MIDI CC, channel pressure, or pitchbend.
Options available through the ROLI Dashboard.

### Controls:

Physical Button - Play/Pause.

Touch while playing - Speed.

Touch while stopped - Spawn new particle.

## Henon
A MIDI CC generator using the Henon map.
Spawns a new particle if the current particle escapes the viewing window.
Outputs MIDI CC, channel pressure, or pitchbend.
Options available through the ROLI Dashboard.

Note - viewing window is calibrated for default parameters only.

### Controls:

Physical Button - Play/Pause.

Touch while playing - Speed.

Touch while stopped - Spawn new particle.

## Shift Register
A 16-bit shift array with memory corruption, based on the Turing Machine eurorack module by Tom Whitwell.
Outputs MIDI note with velocity.
Options available through the ROLI Dashboard.

### Controls:

Physical Button - Play/Pause. MIDI panic.

Top Slider - Probability that a shifted bit will be inverted.

Bottom Slider - Speed.

## Tilt-O-Whirl
A 2D physics simulator, based on the Tombola sequencer by Teenage Engineering.
Up to eight balls roll on a tilted plate, triggering MIDI notes when they strike the edges.
Gradient indicates the direction of the tilt.
Outputs MIDI notes.
Options available through the ROLI Dashboard.

### Controls:

Physical Button - Delete all balls. MIDI panic.

Tap - Spawn a new ball

Drag and release - Throw a new ball
