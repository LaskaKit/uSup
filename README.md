# μŠup – adaptéry a moduly

**μŠup** je univerzální konektor LaskaKitu pro jednoduché a bezpečné propojení čidel, modulů a vývojových desek. Používá konektor **JST-SH s roztečí 1 mm**, který je malý, vydrží časté připojování a odpojování a má **zámek**, takže ho nezapojíš obráceně. I2C verze μŠup je **pinově kompatibilní se SparkFun Qwiic a Adafruit STEMMA QT**.

Víc o vzniku a zapojení μŠup najdeš v článku [Představujeme univerzální konektor pro propojení modulů a čidel μŠup](https://www.laskakit.cz/navody-ke-zbozi/predstavujeme-univerzalni-konektor-pro-propojeni-modulu-a-cidel-sup/).

*English version below.*

## Zapojení konektorů

### μŠup (I2C) – JST-SH 4-pin

| Pin | Signál | Barva vodiče v kabelu |
|-----|--------|-----------------------|
| 1 | GND | černá |
| 2 | VCC (3,3 V) | červená |
| 3 | SDA | modrá |
| 4 | SCL | žlutá |

### μŠup-SPI – JST-SH 6-pin

| Pin | Signál |
|-----|--------|
| 1 | GND |
| 2 | VCC (3,3 V) |
| 3 | SDO |
| 4 | CLK |
| 5 | SDI |
| 6 | CS |

## Produkty v tomto repozitáři

| Složka | Produkt | K čemu slouží | Rozměry PCB |
|--------|---------|---------------|-------------|
| [uSUP_4x](uSUP_4x/) | [LaskaKit μŠup 4x na DIP adaptér](https://www.laskakit.cz/laskakit-sup-4x-na-dip-adapter/) | rozbočovač I2C – 4× μŠup + kolíková lišta | 17,8 × 15,2 mm |
| [uSUP_DIP](uSUP_DIP/) | [LaskaKit μŠup na DIP adaptér](https://www.laskakit.cz/laskakit-sup-na-dip-adapter/) | 2× μŠup na kolíkovou lištu s volitelným pořadím pinů | 14,0 × 12,4 mm |
| [uSUP_SPI_4x](uSUP_SPI_4x/) | [LaskaKit μŠup-SPI 4x na DIP adaptér](https://www.laskakit.cz/laskakit-sup-spi-4x-na-dip-adapter/) | rozbočovač SPI – 4× μŠup-SPI + kolíková lišta se 3 CS | 22,9 × 17,8 mm |
| [uSUP_logic_level_adapter](uSUP_logic_level_adapter/) | [LaskaKit převodník logických úrovní I2C 5V na μŠup 3.3V](https://www.laskakit.cz/laskakit-prevodnik-logickych-urovni-i2c-5v-na-sup-3-3v/) | připojení 3,3V μŠup čidel k 5V deskám (Arduino Uno, Mega) | 12,7 × 16,5 mm |

Každá složka obsahuje:

- `HW/` – schéma v PDF
- `Production/` – Gerber data, BOM a pick-and-place (CPL) pro výrobu
- `3D/` – 3D model desky (STEP)
- `img/` – fotografie
- `README_CZ.md` / `README.md` – popis v češtině a angličtině

## Propojovací kabely

**μŠup (I2C, 4-pin):**

- [kabel 5 cm](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-5cm/), [10 cm](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-10cm/), [20 cm](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-20cm/)
- [kabel – dupont samice](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-dupont-samice/), [kabel – dupont samec](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-dupont-samec/)
- [kabel s testovacím háčkem](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-s-testovacim-hackem/)

**μŠup-SPI (6-pin):**

- [kabel 5 cm](https://www.laskakit.cz/--sup-spi-jst-sh-6-pin-kabel-5cm/), [10 cm](https://www.laskakit.cz/--sup-spi-jst-sh-6-pin-kabel-10cm/), [20 cm](https://www.laskakit.cz/--sup-spi-jst-sh-6-pin-kabel-20cm/)
- [kabel – dupont samice](https://www.laskakit.cz/--sup-spi-jst-sh-6-pin-kabel-dupont-samice/), [kabel – dupont samec](https://www.laskakit.cz/--sup-spi-jst-sh-6-pin-kabel-dupont-samec/)
- [kabel s testovacím háčkem](https://www.laskakit.cz/--sup-spi-jst-sh-6-pin-kabel-s-testovacim-hackem/)

Všechny kabely najdeš v sekci [Propojovací kabely](https://www.laskakit.cz/vodice/).

---

# μŠup (μShup) – adapters and modules

**μŠup** is LaskaKit's universal connector for quick and safe wiring of sensors, modules and development boards. It uses a **1 mm pitch JST-SH connector** with a **locking latch**, so it cannot be plugged in reversed. The I2C version of μŠup is **pin-compatible with SparkFun Qwiic and Adafruit STEMMA QT**.

## Pinout

**μŠup (I2C) – JST-SH 4-pin:** 1 – GND (black), 2 – VCC 3.3 V (red), 3 – SDA (blue), 4 – SCL (yellow)

**μŠup-SPI – JST-SH 6-pin:** 1 – GND, 2 – VCC 3.3 V, 3 – SDO, 4 – CLK, 5 – SDI, 6 – CS

## Products in this repository

| Folder | Product | Purpose | PCB size |
|--------|---------|---------|----------|
| [uSUP_4x](uSUP_4x/) | [LaskaKit μShup 4x for DIP adapter](https://www.laskakit.cz/en/laskakit-sup-4x-na-dip-adapter/) | I2C hub – 4× μŠup + pin header | 17.8 × 15.2 mm |
| [uSUP_DIP](uSUP_DIP/) | [LaskaKit μShup for DIP adapter](https://www.laskakit.cz/en/laskakit-sup-na-dip-adapter/) | 2× μŠup to pin header with configurable pinout | 14.0 × 12.4 mm |
| [uSUP_SPI_4x](uSUP_SPI_4x/) | [LaskaKit μShup-SPI 4x for DIP adapter](https://www.laskakit.cz/en/laskakit-sup-spi-4x-na-dip-adapter/) | SPI hub – 4× μŠup-SPI + pin header with 3 CS lines | 22.9 × 17.8 mm |
| [uSUP_logic_level_adapter](uSUP_logic_level_adapter/) | [LaskaKit logic level converter I2C 5V to μShup 3.3V](https://www.laskakit.cz/en/laskakit-prevodnik-logickych-urovni-i2c-5v-na-sup-3-3v/) | connects 3.3 V μŠup sensors to 5 V boards (Arduino Uno, Mega) | 12.7 × 16.5 mm |

Each folder contains the schematic (`HW/`), manufacturing data – Gerber, BOM, CPL (`Production/`), a STEP 3D model (`3D/`) and photos (`img/`).
