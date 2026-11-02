# Phenom

[Русский](README.ru.md)

Files and documentation for building the Ergohaven Phenom keyboard: case models, PCB manufacturing files, and assembly guides.

## Project status

This repository is being prepared. Manufacturing files and assembly guides have not been published yet. It is not currently a complete, validated DIY build package.

The full-size Phenom is the primary target of the assembly guides. Inclusion of Phenom Mini and Phenom Micro is not yet confirmed.

## Planned builds

- **PCB build:** a new unified switchplate PCB, without connectors between columns or the previous interconnect board; includes pointing-device and encoder modules.
- **Handwired build:** no modules; planned around RP2040 Zero and directly wired switch rows and columns, following the HPD handwired approach.

**The current firmware must not be assumed compatible with the planned RP2040 Zero wiring.** GPIO mapping changes and validation are required before publishing a supported handwired firmware procedure. Assembly instructions and a tested pinout are not yet available.

## Repository organization

See [the preparation plan and file organization](docs/project-plan.md). Hardware files will be added after their revisions and compatibility have been verified.

## Firmware and configuration

- [Firmware downloads and update instructions](https://docs.eh.works/firmware/)
- [QMK firmware source](https://github.com/ergohaven/vial-qmk)
- [Entropy configurator](https://entropy.tools/)

These links describe the existing product ecosystem, not confirmed support for the planned DIY hardware revisions.

## License

The files in this repository are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

See [LICENSE](LICENSE) for the full license text. Firmware in external repositories is governed by its own license.
