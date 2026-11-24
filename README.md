# Mic Array Polar Plot

Interactive 2-microphone linear and 3-microphone equilateral triangle polar response simulator.

**[Open Live Simulator](https://phaseresponse.github.io/mic-array/)**

## Parameters
* **Array Geometry:** Toggle between 2 mics (`-d/2`, `+d/2`) and 3 mics (`0°`, `120°`, `240°`). Each mode keeps its own settings.
* **d/λ:** Mic distance in wavelengths. The frequency and wavelength are shown below it.
* **d (cm):** Mic distance. Changing d with d/λ fixed changes only the frequency, not the pattern.
* **Reference mic (mic0):** Fixed at 0 dB, 0 µs, + polarity. The other mics are set relative to it.
* **Per-Mic Gain (dB):** Vertical slider for each adjustable mic.
* **Per-Mic Polarity (+/−):** Inverts that mic's signal (×−1) at all frequencies.
* **Per-Mic Delay:** Dial θ from 0 to π, giving delay τ = cos θ · d/c (from +d/c to −d/c).
* **2 mics:** θ is the look direction (polarity +) or null direction (polarity −), mirrored to 360° − θ.

The pattern is shaped by d/λ, gain, polarity and delay angle. The plot is normalized so the maximum possible response is 0 dB.
