# Bioinstrumentation Circuit Projects

This repository contains five ECE 444 bioinstrumentation hardware projects. Each folder includes the project handout and my written report.

## Projects

- [Project 1: Instrumentation Amplifier](Proj1/)  
  Designed, built, and tested a three-op-amp instrumentation amplifier using LF411 op amps. I characterized its differential gain, frequency response, common-mode rejection, and power consumption for small biosignal-style inputs.

- [Project 2: Active Low-Pass Filter](Proj2/)  
  Designed and tested a second-order Sallen-Key Butterworth low-pass filter with a 100 Hz cutoff and gain of 2. The project focused on passing EEG-range signals while attenuating higher-frequency noise.

- [Project 3: Passive High-Pass Filter](Proj3/)  
  Built a third-order passive Butterworth high-pass filter using an LC ladder design. I transformed a normalized low-pass prototype into a high-pass circuit and tested its measured cutoff behavior against the design target.

- [Project 4: Bridge Circuit for Transducer Interface](Proj4/)  
  Constructed a Wheatstone bridge for a resistive strain-gauge transducer and powered it with a regulated 5 V supply. I measured the raw bridge response to strain and documented the failed attempt to integrate it with the instrumentation amplifier.

- [Project 5: Not-Quite Pulse Oximeter](Proj5/)  
  Built a simple optical pulse detector using a red LED, phototransistor, RC coupling, and LF411 amplifier. The circuit was intended to show the pulsatile change in transmitted light through a fingertip, without calculating blood oxygen saturation.
