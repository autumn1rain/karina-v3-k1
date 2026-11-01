# Karina — firmware for Quansheng UV-K5 V3 / UV-K1

Based on fagci's UV-K5 mod (v1.2.1).

Прошивка Karina для Quansheng UV-K5 V3 / UV-K1. Основана на моде fagci (v1.2.1).

## Download / Скачать

https://github.com/autumn1rain/karina-v3-k1/releases/latest

| File | Radio / Рация |
| --- | --- |
| `karina-v3.packed.bin` | UV-K5 V3 |
| `karina-v3.bin` | UV-K5 V3 |
| `karina-k1.packed.bin` | UV-K1 |
| `karina-k1.bin` | UV-K1 |

## Flashing / Прошивка

Полная инструкция в файлах [karina-v3-k1-install.pdf](karina-v3-k1-install.pdf) [karina-v3-k1-manual.pdf](karina-v3-k1-manual.pdf) / большая благодарность - @DmitrBukatov

1. Back up your radio's calibration and settings first. / Сначала сохрани калибровку и настройки.
2. Turn the radio off, hold PTT and turn it on (flash mode). / Выключи рацию, зажми PTT и включи (режим прошивки).
3. Flash with any of the tools / Прошей одним из инструментов:

| Tool | File |
| --- | --- |
| Web flasher [UV Studio](https://armel.github.io/uvstudio/#flash) (Chrome/Edge/Opera/Brave), UV-K5 V3 / UV-K1 | see the tool's page |
| [Official Quansheng updater]https://en.qsfj.com/support/downloads/8483) | `*.packed.bin` |
| [k5prog](https://github.com/sq5bpf/k5prog): `./k5prog -F -YYY -b <file>.bin` | `*.bin` |
| Web flasher [uvtools](https://egzumer.github.io/uvtools) (Chrome/Edge) | see the tool's page |
| [K5K1 Prog](https://github.com/ERuban/k5k1prog-mac) (macOS), UV-K5 / UV-K5 V3 / UV-K1 | `*.bin` or `*.packed.bin` |

Check that the tool supports your radio. / Проверь, что инструмент поддерживает твою рацию.

Use at your own risk. / Используешь на свой риск.

## TG Chat

https://t.me/k5fwmod чат в комментариях.

## Credits / Благодарности

- Dual Tachyon — https://github.com/DualTachyon
- Mikhail (fagci) — https://github.com/fagci
- OneOfEleven — https://github.com/OneOfEleven
- muzkr — https://github.com/muzkr
- armel — https://github.com/armel
- Andrej — https://github.com/Tunas1337
- ERuban — @vkusni https://github.com/ERuban
- DmitroBuka — @DmitrBukatov
- Kolyan — @Kolyanuch
- PunkTracker
- Avers — @aversreg
- Киловольт Киловольтович
- Ivan — @s_ivan96
- Руслан Румянцев
- QUANSHENG и другие..

## License / Лицензия

Copyright 2023 Dual Tachyon <https://github.com/DualTachyon>
Copyright 2023 fagci <https://github.com/fagci>
Copyright 2023 OneOfEleven https://github.com/OneOfEleven
Copyright 2025 muzkr <https://github.com/muzkr>
Copyright 2025 armel <https://github.com/armel>
Modifications Copyright 2026 autumn1rain <https://github.com/autumn1rain>

Licensed under the Apache License, Version 2.0. See [LICENSE](LICENSE) for the full text and list of copyright holders.
