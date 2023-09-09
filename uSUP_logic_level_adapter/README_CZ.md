![uŠup TOP](https://github.com/LaskaKit/uSup/blob/main/uSUP_logic_level_adapter/img/2.jpg)

# uSUP logic level adapter

Připojit čidlo s I2C sběrnicí díky [uŠup konektoru](https://blog.laskakit.cz/predstavujeme-univerzalni-konektor-pro-propojeni-modulu-a-cidel-%ce%bcsup/) nebylo nikdy jednodušší. [uŠup konektor](https://blog.laskakit.cz/predstavujeme-univerzalni-konektor-pro-propojeni-modulu-a-cidel-%ce%bcsup/) má totiž standardní zapojení na všech modulech a navíc obsahuje i zámek. Není tak třeba se obávat o modulu nebo řídící desky. Řídících desek máme opravdu hodně. Některé s [ESP8266](https://www.laskakit.cz/laskakit-airboard-8266-deska-pro-mereni-kvality-vzduchu/), jiné s [ESP32](https://www.laskakit.cz/laskakit-esp32-devkit/?variantId=11481), další s [ESP32-C3](https://www.laskakit.cz/laskakit-meteo-mini/?variantId=10473) nebo ESP32-S2.

I když je uŠup kompatibilní s dalšími populárními konektory jako SparkFun Qwiic a Adafruit STEMMA, občas je potřeba připojit čidla k jiným deskám než jsou ty, které mají uŠup konektor. Pokud napájení desky je 3.3V, stačí [uŠup konektor na dupont samice](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-dupont-samice/). Pokud je řídící deska napájena 5V a má 5V logiku na I2C, je potřeba převodník logických úrovní nebo také level shifter. 

K tomu slouží právě tato miniaturní deska uŠup logic level adapter. Na jedné straně například [Arduino Uno](https://www.laskakit.cz/arduino-uno-rev3--original/) nebo [Arduino Mega](https://www.laskakit.cz/arduino-mega-adk-2560-r3--klon/) aj. a na straně druhé jedno z našich čidel.

Jaké? Třeba [BME688 - Senzor tlaku, teploty, vlhkosti a kvalitu vzduchu](https://www.laskakit.cz/laskakit-bme688-senzor-tlaku--teploty--vlhkosti-a-kvalitu-vzduchu/), [SGP41 - VOC a Nox senzor kvality ovzduší](https://www.laskakit.cz/laskakit-sgp41-voc-a-nox-senzor-kvality-ovzdusi/) a všechna ta data můžeš zobrazit na [OLED displeji 1.3"](https://www.laskakit.cz/laskakit-oled-displej-128x64-1-3--i2c/?variantId=11903).

## Modul koupíš na https://www.laskakit.cz/laskakit-prevodnik-logickych-urovni-i2c-5v-na-sup-3-3v/
