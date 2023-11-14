# Audio Equalizer 

## Overview

This MATLAB project implements an audio equalizer with user-defined parameters. The program allows users to input various parameters, design frequency band filters, analyze and export filter characteristics, filter an input audio wave file, amplify the output signals, and compare the results with the original signal.



## Usage

1. **Input Parameters:**
   - Use the `input` function to get the wave file name, gain of each frequency band, type of filters (FIR/IIR), and output sample rate.
   - You can also use the `menu` function to create a user interface for easier input.

2. **Filter Design:**
   - Frequency band filters are designed for the specified bands.

3. **Analysis and Export:**
   - Filter characteristics such as gain, phase, impulse, and step response, as well as order and poles/zeros, are analyzed and exported.

4. **Filter Audio:**
   - The wave file is filtered using the designed filters.

5. **Draw Output Signals:**
   - Output signals in time and frequency domains are drawn.

6. **Amplify Signals:**
   - User-defined gain is applied to amplify the output signals.

7. **Create Composite Signal:**
   - Amplified output signals are added in the time domain to form a composite signal.

8. **Compare with Original Signal:**
   - The composite signal is compared with the original signal in both time and frequency domains.

9. **Play and Save:**
   - The final output wave signal can be played and saved using the `wavwrite` or `sound` functions.
