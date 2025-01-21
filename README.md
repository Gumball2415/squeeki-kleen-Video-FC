# squeeki-kleen-Video-FC

An open source hardware external composite video bypass preamplifier modboard
for the Famicom/NES

<img src="docs\squeeki-kleen Video FC.png" style="max-width:80%;" />

## About
I stumbled upon this [composite amplifier circuit](https://www.nesdev.org/wiki/PPU_pinout#Composite_Video_Output)
on the NESDev wiki and wanted to give it a whirl.

## How to install

1. If your board does not have tented vias, cover the area underneath the PPU with kapton tape. be sure to also cover underneath the MMCX connector footprint to avoid shorts. (image here)
2. To reduce stray inductive connections, solate pin 21 of the PPU by cutting any traces connecting to it as close to the through-hole pad as much as possible. (image here)
3. 

## PCB specifications

Note that this project is optimized for JLCPCB manufacturing.
- 2 layers
- 50.80 x 17.78 mm
- 0.8 mm thickness (or 1.60 mm if you plan to attach the MMCX connector)
- any surface finish
- any soldermask/silkscreen color
- tented vias
	- alternatively, cover area under board with kapton/insulative tape
	

## License

This is licensed under the
[TAPR Open Hardware Licence](https://tapr.org/the-tapr-open-hardware-license/).

## Credits

Special thanks to:
- The NESDev community for advice and help
- lidnariq for advice
- Finny (grievre/arreffem) for inspiration
- j4m13c0 for testing the board (and notifying me of Q1 pinout error!)

## Support

If you enjoy this project or find it helpful, please support me on
[Ko-Fi](https://ko-fi.com/persune) or [Patreon](https://www.patreon.com/persune)!
