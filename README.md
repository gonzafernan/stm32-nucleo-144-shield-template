# STM32 Nucleo-144 Shield Template

A KiCad 8.0 template for designing shields compatible with STM32 Nucleo-144 development boards (NUCLEO-H743ZI, NUCLEO-F429ZI, NUCLEO-F746ZG and similar).

## What's Included

- Board outline matching the Nucleo-144 form factor
- Four shield connectors pre-placed and wired: CN8 (2×8), CN9 (2×15), CN7 (2×10), CN10/Zio (2×17)
- All STM32 GPIO ports (PA–PG) exposed as named nets
- Power rails: `+3V3`, `+5V`, `GND`, `AGND`, `AVDD`, `IOREF`, `VIN`

## Usage

1. In KiCad, open **File → New Project from Template** and select this template.
2. Add your components to the schematic using the pre-defined net labels.
3. Route your design within the ready-made PCB outline.

## License

MIT
