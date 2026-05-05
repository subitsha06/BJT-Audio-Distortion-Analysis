## Diode Clipping Distortion Circuit

circuit schematic
<img width="1906" height="846" alt="image" src="https://github.com/user-attachments/assets/d40eb640-fba3-4959-8a2e-c1fff33111be" />



This circuit extends the amplifier by introducing diode-based clipping to create distortion.

After amplification, the signal passes through a resistor and reaches a pair of anti-parallel diodes (D1 and D2). These diodes limit the output voltage by clipping the positive and negative peaks of the waveform once the threshold voltage (~0.7V) is exceeded.

This clipping alters the waveform shape, introducing harmonic content and producing a distorted audio signal. The effect is similar to distortion used in guitar pedals.

The resistor before the diodes controls the clipping intensity, while the load resistor ensures proper output referencing.

This type of clipping is known as hard clipping and results in a more aggressive distortion.
