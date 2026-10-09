![LaskaKit převodník logických úrovní I2C 5V na μŠup 3.3V](img/2.jpg)

# LaskaKit převodník logických úrovní I2C 5V na μŠup 3.3V

Miniaturní deska, která umožní připojit 3,3V čidla a moduly s konektorem μŠup k řídicím deskám s 5V logikou, jako je Arduino Uno nebo Arduino Mega. **Na 5V straně je kolíková lišta pro připojení k řídicí desce, na 3,3V straně konektor μŠup pro připojení čidla.** Obousměrný převod úrovní na linkách SDA a SCL zajišťují dva MOSFET tranzistory BSS138 a napájení 3,3 V pro čidlo vyrábí stabilizátor ME6211C33 přímo z 5 V.

Pokud má tvoje řídicí deska 3,3V logiku (ESP32, ESP8266 apod.), převodník nepotřebuješ – stačí [kabel μŠup – dupont samice](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-dupont-samice/).

## Specifikace

- **Funkce:** obousměrný převodník logických úrovní I2C 5 V ↔ 3,3 V
- **Převod úrovní:** 2× MOSFET BSS138, pull-up rezistory 10 kΩ na obou stranách (SDA i SCL)
- **Napájení:**
  - **Vstup (5V strana):** 5 V z řídicí desky
  - **Výstup pro čidlo (3,3V strana):** 3,3 V z LDO ME6211C33, max. 500 mA
- **Připojení:**
  - **5V strana (řídicí deska):** kolíková lišta 4 piny, rozteč 2,54 mm – SDA, SCL, GND, 5V
  - **3,3V strana (čidlo/modul):** μŠup (JST-SH 4-pin, rozteč 1 mm, se zámkem) – 1 GND, 2 VCC 3,3 V, 3 SDA, 4 SCL
- **Kompatibilita konektoru:** μŠup, SparkFun Qwiic, Adafruit STEMMA QT
- **Rozměry PCB:** 12,7 × 16,5 × 1,6 mm
- **Montážní otvor:** 1× Ø 2,5 mm

## Vhodné řídicí desky s 5V logikou

- [Arduino Uno rev3, originál](https://www.laskakit.cz/arduino-uno-rev3--original/)
- [LaskaKit Mega ADK 2560 R3](https://www.laskakit.cz/arduino-mega-adk-2560-r3--klon/)

## Vhodná čidla a moduly s μŠup

- [LaskaKit BME688 Senzor tlaku, teploty, vlhkosti a kvality vzduchu](https://www.laskakit.cz/laskakit-bme688-senzor-tlaku--teploty--vlhkosti-a-kvalitu-vzduchu/)
- [LaskaKit SGP41 VOC a NOx senzor kvality ovzduší](https://www.laskakit.cz/laskakit-sgp41-voc-a-nox-senzor-kvality-ovzdusi/)
- [LaskaKit SHT40 Senzor teploty a vlhkosti vzduchu](https://www.laskakit.cz/laskakit-sht40-senzor-teploty-a-vlhkosti-vzduchu/)
- [LaskaKit BME280 Senzor tlaku, teploty a vlhkosti vzduchu](https://www.laskakit.cz/arduino-senzor-tlaku--teploty-a-vlhkosti-bme280/)
- [LaskaKit OLED displej 128x64 1.3" I²C](https://www.laskakit.cz/laskakit-oled-displej-128x64-1-3--i2c/)

## Propojovací kabely

- [μŠup, STEMMA QT, Qwiic JST-SH 4-pin kabel – 5 cm](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-5cm/)
- [μŠup, STEMMA QT, Qwiic JST-SH 4-pin kabel – 10 cm](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-10cm/)
- [μŠup, STEMMA QT, Qwiic JST-SH 4-pin kabel – 20 cm](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-20cm/)

## Soubory

- [Schéma (PDF)](HW/uSUP_logic_level_adapter.pdf)
- [Výrobní data – Gerber, BOM, CPL](Production/)
- [3D model (STEP)](3D/)
- [Historie verzí](Version.md)

## Modul koupíš na https://www.laskakit.cz/laskakit-prevodnik-logickych-urovni-i2c-5v-na-sup-3-3v/
