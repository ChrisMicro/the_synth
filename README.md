## wavetable synthesizer library for Arduino.

Simple to use 4 polyphonic wavetable synthesizer library for Arduino.


Specs:

20KHz sample rate using approx 45 % of the available CPU time ( On Atmega CPUs )

Attiny CPUs need more processing time because they have no hardware multiplier.

### Waveforms
Has 5 build in waveforms 

  - SINE
  - RAMP
  - SAW
  - SQUARE
  - NOISE.
  
Has 4 build in envelopes.

Each of the 4 voices has parameters for Waveform, Pitch (MIDI note or Frequency), Envelope, Duration and modulation
Each voice has trigger functions for simple ot MIDI note trigger.
Timing functions are available for sample rate sync and end-of-envelope detection.


### ATMEGA CPU ( e.g ARDUINO UNO)

Output audio as PWM on pin 11, pin 3 or ad differential signal
on both.

### ATTINY85

Output audio as PWM on pin PB1


### Main credit for this software
Dzl/Illutron 2014

dzlsevilgeniuslair.blogspot.dk
illutron.dk




