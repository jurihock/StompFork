# StompFork

Active OpAmp audio signal splitter to feed multiple parallel stompboxes.

## Key features

- Split one line-level input into three outputs
- Direct output (unity from input buffer)
- Stompbox output 1 (level pot + output buffer)
- Stompbox output 2 (level pot + output buffer)

## Power supply

- Recommended 18 V
- Should work at 12 V
- May work at 9 V
- Series schottky protection included

## Impedance

- Hi‑Z input (~1 MΩ AC)
- Lo‑Z output (~100 Ω AC)

## Caps

Depending on your preference, you can use polarized electrolytic caps in the signal path, or you can replace them with "audiophile" caps. For this purpose, the KiCad project includes larger footprints for `C1` and `C5-C7`. If you decide to use the polarized electrolytic caps, ensure that the anode `+` is facing the opamp and the cathode `-` is facing the jacks.

Make sure you pick the proper voltage rating, e.g. 50 V.

## PCB

The circuit should fit on a standard 100x50 mm perfboard. You can save even more space by combining several smaller JST connectors into one larger one.

## Similar projects

- [The Splitter Kit](https://musikding.de/The-Splitter-kit) by [Das Musikding](https://musikding.de)
- [Signal Splitter](https://guitar-electronics.eu/en_US/c/SIGNAL-SPLITTER/68) by [Guitar Electronics](https://guitar-electronics.eu)

## Further reading

- [Designing With Opamps](https://sound-au.com/dwopa.htm) by [Rod Elliott](https://sound-au.com)
