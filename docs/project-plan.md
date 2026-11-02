# Phenom repository preparation / Подготовка репозитория Phenom

## Confirmed scope / Подтверждённый охват

- Public repository: `D19ital/phenom`; transfer to `ergohaven/phenom` only after final approval.
- Full-size Phenom is the primary build-guide target. Mini/Micro inclusion is undecided.
- PCB revision: new unified switchplate; no connectors between columns or the previous interconnect board.
- PCB guide: keyboard and modules. Handwired guide: keyboard without modules.
- Handwired: RP2040 Zero and directly wired switch matrix, based on the HPD approach. Component details and quantities must be verified for Phenom rather than copied verbatim.
- All repository files: CC BY-NC-SA 4.0. External firmware retains its own license.

## Stages / Этапы

1. Gather technical information, agree on structure and workflow, and create the repository foundation.
2. Receive and inspect hardware files; publish verified files, revision information, BOM, and project overview.
3. Prepare and review PCB assembly guides in Russian and English, including modules.
4. Prepare and review handwired assembly guides in Russian and English, without modules.

Review each stage before proceeding to the next. Do not present untested manufacturing or wiring instructions as validated.

## Planned layout / Планируемая структура

Directories are created when real files are ready, not as empty placeholders.

```text
README.md
README.ru.md
LICENSE
docs/
  project-plan.md
images/
case/
  stl/
  step/
pcb/
  gerber/
    <board>/<revision>/
  schematic/
    <board>/<revision>/
  source/
    <board>/<revision>/
build_guide/
  build_guide_en.md
  build_guide_ru.md
  images/
handwired/
  handwired.en.md
  handwired.ru.md
  images/
  stl/
  step/
```

Add model subdirectories if Mini/Micro are included. Board identifiers and revision names must come from the supplied designs. Keep PCB and handwired case variants distinct; document genuinely shared parts rather than assuming interchangeability.

## PCB publication proposal / Предложение по публикации плат

Pending inspection of the supplied CAD exports:

- Commit unpacked extended Gerber RS-274X layers and Excellon drill files, separated by board and revision, for use in third-party viewers.
- Include the board outline and identify plated/non-plated drill files where applicable; document units, layer mapping, stackup, and manufacturing requirements from the verified design.
- Publish a matching, verified ZIP manufacturing package as a release asset for convenient download. Do not mix boards or revisions in one manufacturing package.
- Publish schematics as PDF, alongside editable CAD sources and any dependencies needed to open them.
- Gerber is manufacturing artwork, not a substitute for a schematic or editable PCB design.
- Select exact extensions/export settings after inspecting the CAD tool, actual files, and target viewer/fabricator. Do not rename layer files blindly.

Viewer reference: [gerbv](https://gerbv.github.io/) supports RS-274X and Excellon. Actual export compatibility must be checked in a viewer before publication.

## Required input / Что ещё требуется

- Hardware revision identifiers and confirmed model coverage.
- STL/STEP files for PCB and handwired builds, including modules and shared parts where applicable.
- Gerber and drill exports, schematics, and editable PCB/CAD sources, with their authoring tools and versions.
- Phenom-specific BOM, component references, quantities, fasteners, and printing requirements.
- Assembly photos and confirmed PCB assembly sequence, module types and revisions.
- Handwired matrix, diode orientation, RP2040 Zero GPIO assignment, inter-half connection, reset/boot wiring, and a tested firmware target.

## Handwired firmware dependency / Зависимость от прошивки

RP2040 Zero is not a drop-in replacement for the current GPIO allocation. Inspect the current Phenom firmware and available pins, agree on a wiring map, implement the required mapping changes in the appropriate firmware repository, and validate the real hardware before finalizing the handwired guide. Firmware changes and testing are separate work; no compatibility or hardware-validation claim is made here.
