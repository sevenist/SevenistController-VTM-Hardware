# Sevenist Controller — Hardware (VTM)

Custom PCB for the **Sevenist Controller**, a 64-track MIDI CC control surface built around an [ESP32-S3 Zero](https://docs.waveshare.com/ESP32-S3-Zero).

This repository holds the KiCad project, schematics and fabrication files for the board. The code for it : [VTM Firmware repository](https://github.com/sevenist/SevenistController-VTM-Firmware).

> **Status: updated, should work but not yet tested.**
> Fabricate at your own risk until it's confirmed working.

## Repository layout

```
relControll.kicad_pro / .kicad_sch / .kicad_pcb   KiCad 9 project, schematic, board
relControll.pdf / .svg / sch.prn                  Schematic exports for quick viewing
production/                                        Gerbers, drill and assembly files
EasyEDA.pretty / EasyEDA.3dshapes / *.kicad_sym   Imported footprints, 3D models, symbols
fabrication-toolkit-options.json                  Fabrication Toolkit settings
images/                                            Board renders
```

## Ordering

The files in `production/` are ready to upload to a PCB fab such as JLCPCB or PCBWay.
Open `relControll.kicad_pcb` in KiCad if you'd like to regenerate them or review the design first.

## License

Released under the [GPL-3.0](LICENSE) license.