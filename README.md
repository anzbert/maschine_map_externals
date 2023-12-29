# Maschine Midi Mappings for External Devices

A collection of Maschine Midi Mappings for some of my devices. Mappings work on Maschine Plus standalone.

## Installation

To use, copy to this folder:

`Native Instruments/Maschine 2/Sounds`

Load mapping as a Sound into a Pad via the browser and use the mappings via the Macro menu. Make sure to set the correct Midi Device and Channel in the Channel Settings.

## Mappings

| Device Mapping        | Info                                                                                                                                                                                                                                                                                                                      |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| MAP ALL CCs           | This is a universal mapping, which includes all mappable Midi values in Maschine. ProgramChange and all CCs 0-127.                                                                                                                                                                                                        |
| Arturia Minifreak 2.0 | For FW Version 2.0+. Enable Program Changes in the Midi Menu on the device, if you want to control preset selection externally.                                                                                                                                                                                           |
| Korg Minilogue XD     | Made by [Crybo Synth Sounds](https://www.youtube.com/watch?v=iT-_8rAE6-A)                                                                                                                                                                                                                                                 |
| Korg NTS-1            | Default Channel is 1 on the NTS-1.                                                                                                                                                                                                                                                                                        |
| Digitakt 1.51 Track   | Control Settings on the built-in sampler tracks 1-8. The default MIDI Channels on the Digitakt for these tracks are 1-8.                                                                                                                                                                                                  |
| Digitakt 1.51 MIDI    | Control Settings on the external MIDI tracks 9-16. By default no MIDI channels are set for this. Make sure to set them in the Digitakt MIDI Settings, if you want to use this mapping.                                                                                                                                    |
| Digitakt 1.51 FX      | Control the global Delay, Reverb, Compressor and the External Mixer. The default MIDI Channel on the Digitakt is 9 for global FX.                                                                                                                                                                                         |
| SP404MK2 3.0          | Basic mapping, due to the limited implentation on the SP. Adressable channel are 1: FX1, 2: FX2, 3: FX3, 4:FX4 and 5: InputFX. Pattern Select only when the device is in Pattern Mode. Chromatic playing only works in Chromatic mode on channel 16. The SP doesn't send CC back to the Maschine when adjusting FX on it. |
|                       |                                                                                                                                                                                                                                                                                                                           |
|                       |                                                                                                                                                                                                                                                                                                                           |
