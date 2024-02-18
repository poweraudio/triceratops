**PowerAudio fork of Triceratops**

This fork of Triceratops has the following changes:

* Replaced `waf` binary blob with [autowaf] in source form.
* Changed installation destination from /usr to /usr/local.

[autowaf]: https://github.com/poweraudio/autowaf

---

# triceratops

Triceratops is a virtual subtractive synthesizer plugin with 3 oscillators, 3 ADSR envelopes and 3 LFOs. Oscillators have unison mode, filter has three modes low pass resonant 24db, high pass and band pass. Oscillator sync, inertia (portamento) and basic FM is implemented. 

Triceratops now uses waf / wscript to compile unpack and cd into the source folder, type :-

`./waf configure`

`./waf`

`sudo ./waf install`

To clean the build directory type:

`./waf clean`


Once installed launch using jalv.gtk type:-

`jalv.gtk http://nickbailey.co.nr/triceratops`

To uninstall and remove type this from the source directory:-

`sudo ./waf uninstall`
