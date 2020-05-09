# PulseEffects Config for Acer Swift 5 (2017 model)

If you face the same problem as me, trying to switch to Ubuntu on your Acer Swift 5 just to find out, that the sound is absolute garbage and doesn't sound nearly as good as on windows, here is the solution:

1. Install the PulseEffects package (https://github.com/wwmm/pulseeffects/wiki/Package-Repositories#debian--ubuntu).
2. Copy the Impulse Response File (.irs) into your `~/.config/PulseEffects/irs` folder or just import it via the PulseEffects GUI (Convolver Module -> Waveform Button).
3. Copy the PulseEffects preset (.json) into your `~/.config/PulseEffects/output` folder or just import it via the menu bar in the PulseEffects GUI.
4. Apply the preset and check that the correct .irs file is selected in the Convolver module (this is the key component in making it sound good).
5. Enjoy. :)
