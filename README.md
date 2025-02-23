# squeeki-kleen-Video-FC

An open source hardware external composite video bypass preamplifier modboard
for the Famicom/NES

<img src="docs/squeeki-kleen Video FC.png" style="max-width:80%;" />

## About

I made a compact daughterboard composite video output based on the
[composite amplifier circuit from the AV Famicom](https://www.nesdev.org/wiki/PPU_pinout#Composite_Video_Output).
This is designed to make AV modding RF-only consoles such as the RF Famicom and the Toploading NES-101 compact and simple.

## How to install

TODO: image demonstrations.

1. If your board does not have tented vias, cover the area underneath the PPU with insulating tape. Be sure to also cover underneath the MMCX connector footprint to avoid shorts.
2. To reduce stray inductive connections, isolate pin 21 of the PPU by cutting any traces connecting to it as close to the through-hole pad as much as possible.
3. If needed, add additional bypass capacitors in the empty C3 and C4 footprints.

## PCB specifications

Note that this project is optimized for JLCPCB manufacturing.

- 2 layers
- 50.80 x 17.78 mm
- 0.8 mm thickness (or 1.60 mm if you plan to attach the MMCX connector)
- Any surface finish
- Any soldermask/silkscreen color
- Tented vias
	- alternatively, cover area under board with kapton/insulative tape
	

## License

This is licensed under the [TAPR Open Hardware Licence](https://tapr.org/the-tapr-open-hardware-license/). Copyright Persune 2025.

## Credits

Special thanks to:
- The NESDev community for advice and help
- lidnariq for advice
- Finny (grievre/arreffem) for inspiration
- j4m13c0 for testing the board (and notifying me of Q1 pinout error!)

## Support

If you enjoy this project or find it helpful, please support me using the links below!

- <a href='https://ko-fi.com/A0A63YA8J' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi3.png?v=6' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
- [Patreon](https://patreon.com/persune)
