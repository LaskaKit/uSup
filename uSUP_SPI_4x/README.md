![LaskaKit μShup-SPI 4x for DIP adapter](img/laskakit-sup-spi-4x-na-dip-adapter-1.jpg)

# LaskaKit μŠup-SPI 4x for DIP adapter

Need more SPI sensors or displays? This adapter splits one μŠup-SPI connector from your controller board to three more devices, such as a display and sensors. SDO, CLK, SDI and power are shared; each device needs its own CS (chip select) line so it knows the controller is talking to it.

## CS wiring

- Two connectors share **CS1** – plug the controller board (its μŠup-SPI CS) into one and the first device into the other.
- The other two connectors have their own **CS2** and **CS3**, broken out to the pin header. Wire them to free GPIOs on the controller.
- All signals are also on the pin header, so you can use the adapter in a breadboard or with a board that has no μŠup-SPI.

## Specifications

- **Connectors:** 4× μŠup-SPI (JST-SH 6-pin, 1 mm pitch, locking)
- **μŠup-SPI pinout:** 1 – GND, 2 – VCC (3.3 V), 3 – SDO, 4 – CLK, 5 – SDI, 6 – CS
- **Pin header:** 8 pins, 2.54 mm pitch – SDO, CLK, SDI, GND, VCC, CS1, CS2, CS3
- **PCB size:** 22.9 × 17.8 × 1.6 mm
- **Mounting holes:** 2× Ø 2.5 mm
- **Package contents:** adapter + 8-pin header

## Files

- [Schematic (PDF)](HW/uSup_SPI_4x.pdf)
- [Manufacturing data – Gerber, BOM, CPL](Production/)
- [3D model (STEP)](3D/)

## Available at https://www.laskakit.cz/en/laskakit-sup-spi-4x-na-dip-adapter/
