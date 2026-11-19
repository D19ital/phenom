# Phenom PCB assembly guide — Body

![Phenom — assembled keyboard](images/phenom_bg_14_01.jpg)

[Module assembly guide](modules.md)

## Before assembly

Download the matching keyboard housings, bottom covers and module-port plug: [STL](../stl/body/) or [STEP](../step/body/)

The photographs show boards with SMD components already installed. Full SMD assembly is not covered by this guide

## BOM

The tables below list the parts for the keyboard body and holder boards

<details>
<summary><strong>Phenom body</strong></summary>

| Component | Quantity |
| --- | ---: |
| [Switchplate + thumb keys PCBs](../pcb/switchplate/Gerber_PCB_Phenom_switchplate.zip) | 1 pc |
| Diode 1N4148WT | 52 pcs |
| MX Hotswap sockets | 58 pcs |
| ZX-SH1.0-6PWT | 2 pcs |
| ZX-SH1.0-12PWT | 2 pcs |
| JST SH 1.0 Cable, 6-Pin, 100mm | 2 pcs |
| JST SH 1.0 Cable, 12-Pin, 100mm | 2 pcs |
| M2x4 Screw | 32 pcs |
| M3x5 Screw | 10 pcs |
| M3x5 Insert | 10 pcs |
| Bar Magnet 5x2x10mm | 18 pcs |
| Bumpons, 8x2 mm | 10 pcs |

</details>

<details>
<summary><strong>Holder</strong></summary>

| Component | Quantity |
| --- | ---: |
| [MCU holder PCBs](../pcb/holder/Gerber_PCB_Phenom_holder.zip) | 1 pc |
| Capacitor 1uF, 0402 | 4 pcs |
| Capacitor 15pF, 0402 | 4 pcs |
| Capacitor 100nF, 0402 | 10 pcs |
| Capacitor 2.2uF, 0402 | 2 pcs |
| ZX-SH1.0-12PWT | 2 pcs |
| ZX-SH1.0-6PWT | 2 pcs |
| ZX-SH1.0-14PWT | 2 pcs |
| Diode 1N4148WT | 10 pcs |
| Microcontroller RP2040 | 2 pcs |
| Resistor 5.1kΩ, 0402 | 6 pcs |
| Resistor 1kΩ, 0402 | 2 pcs |
| Resistor 200Ω, 0402 | 2 pcs |
| Resistor 27Ω, 0402 | 4 pcs |
| Push button GT-TC084E-H065-L5 | 4 pcs |
| LDO, SOT-23-3, 662K | 2 pcs |
| Flash memory W25Q32JVSSIQ | 2 pcs |
| USB-C connector USB-TYPE-C-018 | 4 pcs |
| 12 MHz crystal XXHCCLNANF-12.000000MHZ | 1 pc |

</details>

## Keyboard base assembly

### Step 01. Check the case parts

Prepare the left housing ([STL](../stl/body/Phenom-body-left.stl), [STEP](../step/body/Phenom-body-left.stp)) and right housing ([STL](../stl/body/Phenom-body-right.stl), [STEP](../step/body/Phenom-body-right.stp)), left bottom cover ([STL](../stl/body/Phenom-bot-left.stl), [STEP](../step/body/Phenom-bot-left.stp)) and right bottom cover ([STL](../stl/body/Phenom-bot-right.stl), [STEP](../step/body/Phenom-bot-right.stp)), and [switchplate and thumb-key PCBs](../pcb/switchplate/Gerber_PCB_Phenom_switchplate.zip). Check the parts against the case and switchplate BOM

The BOM lists 58 MX hot-swap sockets and 52 1N4148WT diodes. The photographs show populated boards; component assembly is not illustrated here

<details>
<summary>Step illustrations</summary>

![Check the case parts — phenom_bg_01_01.jpg](images/phenom_bg_01_01.jpg)

</details>

> [!NOTE]
> Phenom Mini and Micro halves are assembled in the same way as full-size Phenom. Use the matching housings and bottom covers from the STL and STEP directories

- **Phenom Mini** — left housing: [STL](../stl/body/Phenom-mini-body-left.stl), [STEP](../step/body/Phenom-mini-body-left.stp); right housing: [STL](../stl/body/Phenom-mini-body-right.stl), [STEP](../step/body/Phenom-mini-body-right.stp); left bottom cover: [STL](../stl/body/Phenom-mini-bot-left.stl), [STEP](../step/body/Phenom-mini-bot-left.stp); right bottom cover: [STL](../stl/body/Phenom-mini-bot-right.stl), [STEP](../step/body/Phenom-mini-bot-right.stp)
- **Phenom Micro** — left housing: [STL](../stl/body/Phenom-micro-body-left.stl), [STEP](../step/body/Phenom-micro-body-left.stp); right housing: [STL](../stl/body/Phenom-micro-body-right.stl), [STEP](../step/body/Phenom-micro-body-right.stp); left bottom cover: [STL](../stl/body/Phenom-micro-bot-left.stl), [STEP](../step/body/Phenom-micro-bot-left.stp); right bottom cover: [STL](../stl/body/Phenom-micro-bot-right.stl), [STEP](../step/body/Phenom-micro-bot-right.stp)

Before fitting the switchplate PCBs into a Mini or Micro housing, remove the unused sections with flush cutters:

- **Mini:** remove the top row from each full-size switchplate PCB
- **Micro:** remove the top row and the outermost column from each full-size switchplate PCB

Cut only at the green-marked bridges, above the screw-mount tabs of the row that remains. Keep each mounting tab and its screw hole intact. Red shading shows only the PCB sections to discard. The thumb-key PCBs are unchanged. Perform cutting with power disconnected and remove loose fragments before continuing assembly

<details>
<summary>Mini and Micro — switchplate illustrations</summary>

#### Phenom Mini

![Phenom Mini — remove the top row at the marked bridges](images/phenom_mini_switchplate_cuts.jpg)

#### Phenom Micro

![Phenom Micro — remove the top row and outermost columns](images/phenom_micro_switchplate_cuts.jpg)

</details>

### Step 02. Install the case magnets (optional)

Magnets secure the modules and wrist rests. Skip this step if you will not use either accessory

Place 18 Bar Magnet 5x2x10mm magnets in the designated recesses in the housings and covers

> [!IMPORTANT]
> Install every case magnet with the same pole facing the same direction at its mounting location

Before securing the magnets permanently, check that mating parts attract each other

<details>
<summary>Step illustrations</summary>

![Install the case magnets (optional) — phenom_bg_02_01.jpg](images/phenom_bg_02_01.jpg)

![Install the case magnets (optional) — phenom_bg_02_02.jpg](images/phenom_bg_02_02.jpg)

![Install the case magnets (optional) — phenom_bg_02_03.jpg](images/phenom_bg_02_03.jpg)

![Install the case magnets (optional) — phenom_bg_02_04.jpg](images/phenom_bg_02_04.jpg)

</details>

### Step 03. Install the case threaded inserts

Prepare 10 M3x5 threaded inserts. Install them in their mounting locations using a heated insertion tool, such as a temperature-controlled soldering iron set to 240–260 °C

<details>
<summary>Step illustrations</summary>

![Install the case threaded inserts — phenom_bg_03_01.jpg](images/phenom_bg_03_01.jpg)

![Install the case threaded inserts — phenom_bg_03_02.jpg](images/phenom_bg_03_02.jpg)

![Install the case threaded inserts — phenom_bg_03_03.jpg](images/phenom_bg_03_03.jpg)

![Install the case threaded inserts — phenom_bg_03_04.jpg](images/phenom_bg_03_04.jpg)

</details>

### Step 04. Position the switchplate PCBs

Align the left and right [switchplate PCBs](../pcb/switchplate/Gerber_PCB_Phenom_switchplate.zip) with their respective left housing ([STL](../stl/body/Phenom-body-left.stl), [STEP](../step/body/Phenom-body-left.stp)) and right housing ([STL](../stl/body/Phenom-body-right.stl), [STEP](../step/body/Phenom-body-right.stp)). Check that the switch openings and mounting points line up

<details>
<summary>Step illustrations</summary>

![Position the switchplate PCBs — phenom_bg_04_01.jpg](images/phenom_bg_04_01.jpg)

![Position the switchplate PCBs — phenom_bg_04_02.jpg](images/phenom_bg_04_02.jpg)

</details>

### Step 05. Install switches and secure the switchplates

Install MX switches in groups, alternating switch insertion with PCB fastening as shown. The switches align the [switchplate PCB](../pcb/switchplate/Gerber_PCB_Phenom_switchplate.zip) before it is secured with screws. Check that each switch has straight pins before inserting it

Use 32 M2x4 screws to secure the switchplates: 16 per half

<details>
<summary>Step illustrations</summary>

![Install switches and secure the switchplates — phenom_bg_05_01.jpg](images/phenom_bg_05_01.jpg)

![Install switches and secure the switchplates — phenom_bg_05_02.jpg](images/phenom_bg_05_02.jpg)

![Install switches and secure the switchplates — phenom_bg_05_03.jpg](images/phenom_bg_05_03.jpg)

![Install switches and secure the switchplates — phenom_bg_05_04.jpg](images/phenom_bg_05_04.jpg)

![Install switches and secure the switchplates — phenom_bg_05_05.jpg](images/phenom_bg_05_05.jpg)

![Install switches and secure the switchplates — phenom_bg_05_06.jpg](images/phenom_bg_05_06.jpg)

![Install switches and secure the switchplates — phenom_bg_05_07.jpg](images/phenom_bg_05_07.jpg)

![Install switches and secure the switchplates — phenom_bg_05_08.jpg](images/phenom_bg_05_08.jpg)

![Install switches and secure the switchplates — phenom_bg_05_09.jpg](images/phenom_bg_05_09.jpg)

![Install switches and secure the switchplates — phenom_bg_05_10.jpg](images/phenom_bg_05_10.jpg)

![Install switches and secure the switchplates — phenom_bg_05_11.jpg](images/phenom_bg_05_11.jpg)

</details>

### Step 06. Connect the switchplate cables

Prepare two JST SH 1.0 6-Pin 100mm cables and two JST SH 1.0 12-Pin 100mm cables. Connect them to the corresponding [switchplate PCB](../pcb/switchplate/Gerber_PCB_Phenom_switchplate.zip) connectors and route them along the inside edges of the housings

Use straight-through cables with pin-to-pin wiring

<details>
<summary>Step illustrations</summary>

![Connect the switchplate cables — phenom_bg_06_01.jpg](images/phenom_bg_06_01.jpg)

![Connect the switchplate cables — phenom_bg_06_02.jpg](images/phenom_bg_06_02.jpg)

![Connect the switchplate cables — phenom_bg_06_03.jpg](images/phenom_bg_06_03.jpg)

</details>

### Step 07. Connect and secure the holder boards

Prepare the populated [holder boards](../pcb/holder/Gerber_PCB_Phenom_holder.zip). Connect the switchplate cables to the corresponding ZX-SH1.0-6PWT and ZX-SH1.0-12PWT connectors

Position the boards at the USB-C openings and secure each board with two M3x5 screws

<details>
<summary>Step illustrations</summary>

![Connect and secure the holder boards — phenom_bg_07_01.jpg](images/phenom_bg_07_01.jpg)

![Connect and secure the holder boards — phenom_bg_07_02.jpg](images/phenom_bg_07_02.jpg)

![Connect and secure the holder boards — phenom_bg_07_03.jpg](images/phenom_bg_07_03.jpg)

![Connect and secure the holder boards — phenom_bg_07_04.jpg](images/phenom_bg_07_04.jpg)

</details>

### Step 08. Flash the firmware and test the key matrix

1. Open the [firmware selector](https://docs.eh.industries/firmware/), select **Phenom** and the required firmware type, then download the files
2. Follow the selector instructions to flash both halves. QMK uses the same UF2 for both halves; RMK uses separate left and right files
3. With power disconnected, connect the halves to each other, then connect the keyboard to your computer
4. Open [Entropy](https://entropy.tools/), select the keyboard, and open **Config → Matrix Tester**
5. If the device requires unlocking, use **Config → Unlock device** and hold the highlighted physical keys, then return to Matrix Tester
6. Press every installed switch and check that the corresponding position is highlighted. If a position does not respond, disconnect power and check the switch pins, socket, solder joints, and cable connections before closing the case

<details>
<summary>Step illustrations</summary>

![Entropy Matrix Tester — all 58 positions tested](images/entropy_matrix_tester.png)

</details>

The screenshot illustrates the tester interface. Keyboard geometry and the total number of matrix positions depend on the connected device

After testing, disconnect USB power before continuing assembly

### Step 09. Prepare the bottom-cover contact assemblies (optional)

The contact boards are needed for modules. Skip this step if you will not use modules

Prepare the [base contact boards](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip) and their cables, then secure the boards to the left bottom cover ([STL](../stl/body/Phenom-bot-left.stl), [STEP](../step/body/Phenom-bot-left.stp)) and right bottom cover ([STL](../stl/body/Phenom-bot-right.stl), [STEP](../step/body/Phenom-bot-right.stp)) in the positions shown

<details>
<summary>Step illustrations</summary>

![Prepare the bottom-cover contact assemblies (optional) — phenom_bg_08_01.jpg](images/phenom_bg_08_01.jpg)

![Prepare the bottom-cover contact assemblies (optional) — phenom_bg_08_02.jpg](images/phenom_bg_08_02.jpg)

![Prepare the bottom-cover contact assemblies (optional) — phenom_bg_08_03.jpg](images/phenom_bg_08_03.jpg)

</details>

### Step 10. Connect the contact assemblies to the holder boards (optional)

Connect each bottom-cover [base contact assembly](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip) to its [holder board](../pcb/holder/Gerber_PCB_Phenom_holder.zip) with a JST SH 1.0 Cable, 14-Pin, 60mm

<details>
<summary>Step illustrations</summary>

![Connect the contact assemblies to the holder boards (optional) — phenom_bg_09_01.jpg](images/phenom_bg_09_01.jpg)

![Connect the contact assemblies to the holder boards (optional) — phenom_bg_09_02.jpg](images/phenom_bg_09_02.jpg)

</details>

### Step 11. Close the keyboard halves

Make sure no cables are trapped between case parts. Fit the left bottom cover ([STL](../stl/body/Phenom-bot-left.stl), [STEP](../step/body/Phenom-bot-left.stp)) and right bottom cover ([STL](../stl/body/Phenom-bot-right.stl), [STEP](../step/body/Phenom-bot-right.stp)) and secure each one with three M3x5 screws

<details>
<summary>Step illustrations</summary>

![Close the keyboard halves — phenom_bg_10_01.jpg](images/phenom_bg_10_01.jpg)

![Close the keyboard halves — phenom_bg_10_02.jpg](images/phenom_bg_10_02.jpg)

</details>

### Step 12. Install the keycaps

Fit the keycaps to the switches

<details>
<summary>Step illustrations</summary>

![Install the keycaps — phenom_bg_11_01.jpg](images/phenom_bg_11_01.jpg)

</details>

### Step 13. Fit the case feet

Apply Bumpons 8x2 mm to the positions shown: five feet per half

<details>
<summary>Step illustrations</summary>

![Fit the case feet — phenom_bg_12_01.jpg](images/phenom_bg_12_01.jpg)

![Fit the case feet — phenom_bg_12_02.jpg](images/phenom_bg_12_02.jpg)

</details>

### Step 14. Fit the module-port plugs (optional)

If a half will be used without a module, fit the module-port plug ([STL](../stl/body/Phenom-plug-body.stl), [STEP](../step/body/Phenom-plug-body.stp)) into its module connection recess. Skip the plug on any half where a module will be installed

<details>
<summary>Step illustrations</summary>

![Fit the module-port plugs](images/phenom_bg_13_01.jpg)

</details>

Continue with the [module assembly guide](modules.md) if you will use an encoder, touchpad or trackball
