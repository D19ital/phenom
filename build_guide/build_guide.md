# Phenom PCB assembly guide

![Phenom — assembled keyboard](images/phenom_bg_14_01.jpg)

## Before assembly

Download the PCB-version models: [STL](../stl/) or [STEP](../step/). The `body/` folders contain Phenom, Mini and Micro housings, bottom covers and the module-port plug. The `modules/` folders contain encoder, trackball and touchpad parts in separate subfolders; the shared LED insert is in the `modules/` root

The photographs show boards with SMD components already installed. Full SMD assembly is not covered by this guide

## BOM

The tables below list the parts for each assembly. Each module table covers one complete module and applies to either keyboard half; only the printed housing determines the module side

Each module table includes its pogo system base and module boards; do not add another shared pogo system BOM on top of these quantities

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

<details>
<summary><strong>Encoder module</strong></summary>

| Component | Quantity |
| --- | ---: |
| [Pogo system module PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) | 1 pc |
| [Pogo system base PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip) | 1 pc |
| [Encoder PCB](../pcb/modules/encoder/Gerber_PCB_Encoder.zip) | 1 pc |
| [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) | 1 pc |
| LED SK6812 mini-e | 1 pc |
| ZX-SH1.0-4PWT | 1 pc |
| ZX-SH1.0-4PWT | 1 pc |
| ZX-SH1.0-6PWT | 2 pc |
| ZX-SH1.0-14PWT | 1 pc |
| Pogo Pin Connector, 7mm | 8 pcs |
| EC11 Rotary Encoder | 1 pc |
| Diode 1N4148WT | 1 pc |
| Encoder Knob 26x17mm, Black | 1 pc |
| JST SH 1.0 Cable, 6-Pin, 60mm | 1 pc |
| JST SH 1.0 Cable, 4-Pin, 50mm | 1 pc |
| JST SH 1.0 Cable, 14-Pin, 60mm | 1 pc |
| Bar Magnet 5x2x10mm | 5 pcs |
| M2x4 Screw | 6 pcs |
| M2x4 Screw flat | 2 pcs |
| Bumpons, 8x2 mm | 3 pcs |

</details>

<details>
<summary><strong>Touchpad module</strong></summary>

| Component | Quantity |
| --- | ---: |
| [Pogo system module PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) | 1 pc |
| [Pogo system base PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip) | 1 pc |
| [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) | 1 pc |
| LED SK6812 mini-e | 1 pc |
| ZX-SH1.0-4PWT | 1 pc |
| ZX-SH1.0-4PWT | 1 pc |
| ZX-SH1.0-14PWT | 1 pc |
| Pogo Pin Connector, 7mm | 6 pcs |
| Azoteq IQS43 Sensor | 1 pc |
| Acrylic Touchpad Plate | 1 pc |
| Connector PH2.0 4 pins, 2mm, 90 degree | 1 pc |
| Cable connector PH2.0 4 Pins, 60mm, one head | 1 pc |
| JST SH 1.0 Cable, 4-Pin, 50mm | 1 pc |
| JST SH 1.0 Cable, 14-Pin, 60mm | 1 pc |
| Bar Magnet 5x2x10mm | 5 pcs |
| M2x4 Screw | 2 pcs |
| M2x4 Screw flat | 2 pcs |
| Bumpons, 8x2 mm | 3 pcs |

</details>

<details>
<summary><strong>Trackball module</strong></summary>

| Component | Quantity |
| --- | ---: |
| [Pogo system module PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) | 1 pc |
| [Pogo system base PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip) | 1 pc |
| [Trackball PCB](../pcb/modules/trackball/Gerber_PCB_Trackball.zip) | 1 pc |
| [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) | 1 pc |
| LED SK6812 mini-e | 1 pc |
| ZX-SH1.0-4PWT | 1 pc |
| ZX-SH1.0-4PWT | 1 pc |
| ZX-SH1.0-9PWT | 1 pc |
| ZX-SH1.0-14PWT | 1 pc |
| Pogo Pin Connector, 7mm | 8 pcs |
| Bearing Ball 3mm | 3 pcs |
| Trackball Ball 32mm, Dark Red | 1 pc |
| PMW3610 Sensor | 1 pc |
| Lens LM18-LSI | 1 pc |
| JST SH 1.0 Cable, 6-Pin, 60mm | 1 pc |
| JST SH 1.0 Cable, 4-Pin, 50mm | 1 pc |
| JST SH 1.0 Cable, 14-Pin, 60mm | 1 pc |
| Bar Magnet 5x2x10mm | 8 pcs |
| M2x4 Screw | 5 pcs |
| M2x4 Screw flat | 2 pcs |
| Bumpons, 8x2 mm | 3 pcs |

</details>

PCB manufacturing BOMs and pick-and-place files are available in the corresponding [pcb/](../pcb/) directories

## Keyboard base assembly

### Step 01. Check the case parts

Prepare the left housing ([STL](../stl/body/Phenom-body-left.stl), [STEP](../step/body/Phenom-body-left.stp)) and right housing ([STL](../stl/body/Phenom-body-right.stl), [STEP](../step/body/Phenom-body-right.stp)), left bottom cover ([STL](../stl/body/Phenom-bot-left.stl), [STEP](../step/body/Phenom-bot-left.stp)) and right bottom cover ([STL](../stl/body/Phenom-bot-right.stl), [STEP](../step/body/Phenom-bot-right.stp)), and [switchplate and thumb-key PCBs](../pcb/switchplate/Gerber_PCB_Phenom_switchplate.zip). Check the parts against the case and switchplate BOM

The BOM lists 58 MX hot-swap sockets and 52 1N4148WT diodes. The photographs show populated boards; component assembly is not illustrated here

![Check the case parts — phenom_bg_01_01.jpg](images/phenom_bg_01_01.jpg)

### Step 02. Install the case magnets (optional)

Magnets secure the modules and wrist rests. Skip this step if you will not use either accessory

Place 18 Bar Magnet 5x2x10mm magnets in the designated recesses in the housings and covers

> [!IMPORTANT]
> Install every case magnet with the same pole facing the same direction at its mounting location

Before securing the magnets permanently, check that mating parts attract each other

![Install the case magnets (optional) — phenom_bg_02_01.jpg](images/phenom_bg_02_01.jpg)

![Install the case magnets (optional) — phenom_bg_02_02.jpg](images/phenom_bg_02_02.jpg)

![Install the case magnets (optional) — phenom_bg_02_03.jpg](images/phenom_bg_02_03.jpg)

![Install the case magnets (optional) — phenom_bg_02_04.jpg](images/phenom_bg_02_04.jpg)

### Step 03. Install the case threaded inserts

Prepare 10 M3x5 threaded inserts. Install them in their mounting locations using a heated insertion tool, such as a temperature-controlled soldering iron set to 240–260 °C

![Install the case threaded inserts — phenom_bg_03_01.jpg](images/phenom_bg_03_01.jpg)

![Install the case threaded inserts — phenom_bg_03_02.jpg](images/phenom_bg_03_02.jpg)

![Install the case threaded inserts — phenom_bg_03_03.jpg](images/phenom_bg_03_03.jpg)

![Install the case threaded inserts — phenom_bg_03_04.jpg](images/phenom_bg_03_04.jpg)

### Step 04. Position the switchplate PCBs

Align the left and right [switchplate PCBs](../pcb/switchplate/Gerber_PCB_Phenom_switchplate.zip) with their respective left housing ([STL](../stl/body/Phenom-body-left.stl), [STEP](../step/body/Phenom-body-left.stp)) and right housing ([STL](../stl/body/Phenom-body-right.stl), [STEP](../step/body/Phenom-body-right.stp)). Check that the switch openings and mounting points line up

![Position the switchplate PCBs — phenom_bg_04_01.jpg](images/phenom_bg_04_01.jpg)

![Position the switchplate PCBs — phenom_bg_04_02.jpg](images/phenom_bg_04_02.jpg)

### Step 05. Install switches and secure the switchplates

Install MX switches in groups, alternating switch insertion with PCB fastening as shown. The switches align the [switchplate PCB](../pcb/switchplate/Gerber_PCB_Phenom_switchplate.zip) before it is secured with screws. Check that each switch has straight pins before inserting it

Use 32 M2x4 screws to secure the switchplates: 16 per half

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

### Step 06. Connect the switchplate cables

Prepare two JST SH 1.0 6-Pin 100mm cables and two JST SH 1.0 12-Pin 100mm cables. Connect them to the corresponding [switchplate PCB](../pcb/switchplate/Gerber_PCB_Phenom_switchplate.zip) connectors and route them along the inside edges of the housings

Use straight-through cables with pin-to-pin wiring

![Connect the switchplate cables — phenom_bg_06_01.jpg](images/phenom_bg_06_01.jpg)

![Connect the switchplate cables — phenom_bg_06_02.jpg](images/phenom_bg_06_02.jpg)

![Connect the switchplate cables — phenom_bg_06_03.jpg](images/phenom_bg_06_03.jpg)

### Step 07. Connect and secure the holder boards

Prepare the populated [holder boards](../pcb/holder/Gerber_PCB_Phenom_holder.zip). Connect the switchplate cables to the corresponding ZX-SH1.0-6PWT and ZX-SH1.0-12PWT connectors

Position the boards at the USB-C openings and secure each board with two M3x5 screws

![Connect and secure the holder boards — phenom_bg_07_01.jpg](images/phenom_bg_07_01.jpg)

![Connect and secure the holder boards — phenom_bg_07_02.jpg](images/phenom_bg_07_02.jpg)

![Connect and secure the holder boards — phenom_bg_07_03.jpg](images/phenom_bg_07_03.jpg)

![Connect and secure the holder boards — phenom_bg_07_04.jpg](images/phenom_bg_07_04.jpg)

### Step 08. Flash the firmware and test the key matrix

1. Open the [firmware selector](https://docs.eh.industries/firmware/), select **Phenom** and the required firmware type, then download the files
2. Follow the selector instructions to flash both halves. QMK uses the same UF2 for both halves; RMK uses separate left and right files
3. With power disconnected, connect the halves to each other, then connect the keyboard to your computer
4. Open [Entropy](https://entropy.tools/), select the keyboard, and open **Config → Matrix Tester**
5. If the device requires unlocking, use **Config → Unlock device** and hold the highlighted physical keys, then return to Matrix Tester
6. Press every installed switch and check that the corresponding position is highlighted. If a position does not respond, disconnect power and check the switch pins, socket, solder joints, and cable connections before closing the case

![Entropy Matrix Tester — interface shown in Russian](images/entropy_matrix_tester_ru.jpg)

The screenshot illustrates the tester interface. Keyboard geometry and the total number of matrix positions depend on the connected device

After testing, disconnect USB power before continuing assembly

### Step 09. Prepare the bottom-cover contact assemblies (optional)

The contact boards are needed for modules. Skip this step if you will not use modules

Prepare the [base contact boards](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip) and their cables, then secure the boards to the left bottom cover ([STL](../stl/body/Phenom-bot-left.stl), [STEP](../step/body/Phenom-bot-left.stp)) and right bottom cover ([STL](../stl/body/Phenom-bot-right.stl), [STEP](../step/body/Phenom-bot-right.stp)) in the positions shown

![Prepare the bottom-cover contact assemblies (optional) — phenom_bg_08_01.jpg](images/phenom_bg_08_01.jpg)

![Prepare the bottom-cover contact assemblies (optional) — phenom_bg_08_02.jpg](images/phenom_bg_08_02.jpg)

![Prepare the bottom-cover contact assemblies (optional) — phenom_bg_08_03.jpg](images/phenom_bg_08_03.jpg)

### Step 10. Connect the contact assemblies to the holder boards (optional)

Connect each bottom-cover [base contact assembly](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip) to its [holder board](../pcb/holder/Gerber_PCB_Phenom_holder.zip) with a JST SH 1.0 Cable, 14-Pin, 60mm

![Connect the contact assemblies to the holder boards (optional) — phenom_bg_09_01.jpg](images/phenom_bg_09_01.jpg)

![Connect the contact assemblies to the holder boards (optional) — phenom_bg_09_02.jpg](images/phenom_bg_09_02.jpg)

### Step 11. Close the keyboard halves

Make sure no cables are trapped between case parts. Fit the left bottom cover ([STL](../stl/body/Phenom-bot-left.stl), [STEP](../step/body/Phenom-bot-left.stp)) and right bottom cover ([STL](../stl/body/Phenom-bot-right.stl), [STEP](../step/body/Phenom-bot-right.stp)) and secure each one with three M3x5 screws

![Close the keyboard halves — phenom_bg_10_01.jpg](images/phenom_bg_10_01.jpg)

![Close the keyboard halves — phenom_bg_10_02.jpg](images/phenom_bg_10_02.jpg)

### Step 12. Install the keycaps

Fit the keycaps to the switches

![Install the keycaps — phenom_bg_11_01.jpg](images/phenom_bg_11_01.jpg)

### Step 13. Fit the case feet

Apply Bumpons 8x2 mm to the positions shown: five feet per half

![Fit the case feet — phenom_bg_12_01.jpg](images/phenom_bg_12_01.jpg)

![Fit the case feet — phenom_bg_12_02.jpg](images/phenom_bg_12_02.jpg)

### Step 14. Fit the module-port plugs (optional)

If a half will be used without a module, fit the module-port plug ([STL](../stl/body/Phenom-plug-body.stl), [STEP](../step/body/Phenom-plug-body.stp)) into its module connection recess. Skip the plug on any half where a module will be installed

![Fit the module-port plugs](images/phenom_bg_13_01.jpg)

## Encoder module

### Step 15. Prepare the encoder module parts

Prepare the left module housing ([STL](../stl/modules/encoder/Phenom-enc-body-left.stl), [STEP](../step/modules/encoder/Phenom-enc-body-left.stp)) and right module housing ([STL](../stl/modules/encoder/Phenom-enc-body-right.stl), [STEP](../step/modules/encoder/Phenom-enc-body-right.stp)), left module bottom cover ([STL](../stl/modules/encoder/Phenom-enc-bot-left.stl), [STEP](../step/modules/encoder/Phenom-enc-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/encoder/Phenom-enc-bot-right.stl), [STEP](../step/modules/encoder/Phenom-enc-bot-right.stp)), [Pogo system module PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip), [Pogo system base PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip), [Encoder PCB](../pcb/modules/encoder/Gerber_PCB_Encoder.zip) and [Led PCB](../pcb/modules/Gerber_PCB_Led.zip), an EC11 encoder, and an Encoder Knob 26x17mm, Black

![Prepare the encoder module parts — phenom_bg_15_01.jpg](images/phenom_bg_15_01.jpg)

### Step 16. Solder the encoder module pogo contacts

Install and solder eight 7 mm pogo contacts to the [module connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) in the orientation shown. Check that they are straight and move freely

![Solder the encoder module pogo contacts — phenom_bg_16_01.jpg](images/phenom_bg_16_01.jpg)

![Solder the encoder module pogo contacts — phenom_bg_16_02.jpg](images/phenom_bg_16_02.jpg)

![Solder the encoder module pogo contacts — phenom_bg_16_03.jpg](images/phenom_bg_16_03.jpg)

### Step 17. Solder the encoder

Fit the EC11 encoder to the [Encoder PCB](../pcb/modules/encoder/Gerber_PCB_Encoder.zip) and solder its leads

![Solder the encoder — phenom_bg_17_01.jpg](images/phenom_bg_17_01.jpg)

![Solder the encoder — phenom_bg_17_02.jpg](images/phenom_bg_17_02.jpg)

### Step 18. Connect the encoder module boards

Connect a JST SH 1.0 6-Pin 60mm cable to the [encoder board](../pcb/modules/encoder/Gerber_PCB_Encoder.zip) and a JST SH 1.0 4-Pin 50mm cable to the [Led PCB](../pcb/modules/Gerber_PCB_Led.zip)

![Connect the encoder module boards — phenom_bg_18_01.jpg](images/phenom_bg_18_01.jpg)

![Connect the encoder module boards — phenom_bg_18_02.jpg](images/phenom_bg_18_02.jpg)

![Connect the encoder module boards — phenom_bg_18_03.jpg](images/phenom_bg_18_03.jpg)

![Connect the encoder module boards — phenom_bg_18_04.jpg](images/phenom_bg_18_04.jpg)

### Step 19. Prepare the encoder housing and docking area

Fit the white LED insert ([STL](../stl/modules/Phenom-led-insert.stl), [STEP](../step/modules/Phenom-led-insert.stp)) into its seat in the housing. Check that the left module housing ([STL](../stl/modules/encoder/Phenom-enc-body-left.stl), [STEP](../step/modules/encoder/Phenom-enc-body-left.stp)) and right module housing ([STL](../stl/modules/encoder/Phenom-enc-body-right.stl), [STEP](../step/modules/encoder/Phenom-enc-body-right.stp)) aligns with the keyboard docking area

Install five Bar Magnet 5x2x10mm magnets with the opposite mating pole to the case magnets. Before inserting each magnet into the module, check that its mating face is attracted to the case

![Prepare the encoder housing and docking area — phenom_bg_19_01.jpg](images/phenom_bg_19_01.jpg)

![Prepare the encoder housing and docking area — phenom_bg_19_02.jpg](images/phenom_bg_19_02.jpg)

![Prepare the encoder housing and docking area — phenom_bg_19_03.jpg](images/phenom_bg_19_03.jpg)

### Step 20. Secure the encoder module boards

Secure the [connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) with M2x4 flat screws, and the [encoder board](../pcb/modules/encoder/Gerber_PCB_Encoder.zip) and [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) with M2x4 screws. Route cables without tension or pinching

![Secure the encoder module boards — phenom_bg_20_01.jpg](images/phenom_bg_20_01.jpg)

![Secure the encoder module boards — phenom_bg_20_02.jpg](images/phenom_bg_20_02.jpg)

![Secure the encoder module boards — phenom_bg_20_03.jpg](images/phenom_bg_20_03.jpg)

![Secure the encoder module boards — phenom_bg_20_04.jpg](images/phenom_bg_20_04.jpg)

### Step 21. Finish the encoder module

Fit the left module bottom cover ([STL](../stl/modules/encoder/Phenom-enc-bot-left.stl), [STEP](../step/modules/encoder/Phenom-enc-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/encoder/Phenom-enc-bot-right.stl), [STEP](../step/modules/encoder/Phenom-enc-bot-right.stp)) and encoder knob. Apply three Bumpons 8x2 mm feet

![Finish the encoder module — phenom_bg_21_01.jpg](images/phenom_bg_21_01.jpg)

![Finish the encoder module — phenom_bg_21_02.jpg](images/phenom_bg_21_02.jpg)

![Finish the encoder module — phenom_bg_21_03.jpg](images/phenom_bg_21_03.jpg)

## Touchpad module

### Step 22. Prepare the touchpad module parts

Prepare the left module housing ([STL](../stl/modules/touchpad/Phenom-tp-body-left.stl), [STEP](../step/modules/touchpad/Phenom-tp-body-left.stp)) and right module housing ([STL](../stl/modules/touchpad/Phenom-tp-body-right.stl), [STEP](../step/modules/touchpad/Phenom-tp-body-right.stp)), left module bottom cover ([STL](../stl/modules/touchpad/Phenom-tp-bot-left.stl), [STEP](../step/modules/touchpad/Phenom-tp-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/touchpad/Phenom-tp-bot-right.stl), [STEP](../step/modules/touchpad/Phenom-tp-bot-right.stp)), [Pogo system module PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip), [Pogo system base PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip) and [Led PCB](../pcb/modules/Gerber_PCB_Led.zip), the Azoteq IQS43 Sensor touchpad, and the Acrylic Touchpad Plate

![Prepare the touchpad module parts — phenom_bg_22_01.jpg](images/phenom_bg_22_01.jpg)

### Step 23. Prepare the touchpad connection board

Install and solder six 7 mm pogo contacts. Install and solder the four-pin PH2.0 connector with 2 mm pitch and a 90-degree angle

Check the connector orientation against the schematic. Trim the protruding leads as shown without damaging the solder joints

![Prepare the touchpad connection board — phenom_bg_23_01.jpg](images/phenom_bg_23_01.jpg)

![Prepare the touchpad connection board — phenom_bg_23_02.jpg](images/phenom_bg_23_02.jpg)

![Prepare the touchpad connection board — phenom_bg_23_03.jpg](images/phenom_bg_23_03.jpg)

![Prepare the touchpad connection board — phenom_bg_23_04.jpg](images/phenom_bg_23_04.jpg)

![Prepare the touchpad connection board — phenom_bg_23_05.jpg](images/phenom_bg_23_05.jpg)

![Prepare the touchpad connection board — phenom_bg_23_06.jpg](images/phenom_bg_23_06.jpg)

![Prepare the touchpad connection board — phenom_bg_23_07.jpg](images/phenom_bg_23_07.jpg)

### Step 24. Connect the touchpad cable and prepare the overlay

Prepare the PH2.0 4 Pins 60mm one head cable. Solder its free ends to the touchpad pads according to the verified pinout

Secure the soldered cable exit with hot glue. Apply the acrylic overlay

![Connect the touchpad cable and prepare the overlay — phenom_bg_24_01.jpg](images/phenom_bg_24_01.jpg)

![Connect the touchpad cable and prepare the overlay — phenom_bg_24_02.jpg](images/phenom_bg_24_02.jpg)

![Connect the touchpad cable and prepare the overlay — phenom_bg_24_03.jpg](images/phenom_bg_24_03.jpg)

### Step 25. Prepare the touchpad housing and docking area

Fit the white LED insert ([STL](../stl/modules/Phenom-led-insert.stl), [STEP](../step/modules/Phenom-led-insert.stp)) and check that the left module housing ([STL](../stl/modules/touchpad/Phenom-tp-body-left.stl), [STEP](../step/modules/touchpad/Phenom-tp-body-left.stp)) and right module housing ([STL](../stl/modules/touchpad/Phenom-tp-body-right.stl), [STEP](../step/modules/touchpad/Phenom-tp-body-right.stp)) aligns with the keyboard

Install five Bar Magnet 5x2x10mm magnets with the opposite mating pole to the case magnets. Before inserting each magnet into the module, check that its mating face is attracted to the case

![Prepare the touchpad housing and docking area — phenom_bg_25_01.jpg](images/phenom_bg_25_01.jpg)

![Prepare the touchpad housing and docking area — phenom_bg_25_02.jpg](images/phenom_bg_25_02.jpg)

![Prepare the touchpad housing and docking area — phenom_bg_25_03.jpg](images/phenom_bg_25_03.jpg)

![Prepare the touchpad housing and docking area — phenom_bg_25_04.jpg](images/phenom_bg_25_04.jpg)

### Step 26. Connect the touchpad module boards

Connect the touchpad using the prepared PH2.0 cable, and the [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) using a JST SH 1.0 4-Pin 50mm cable

![Connect the touchpad module boards — phenom_bg_26_01.jpg](images/phenom_bg_26_01.jpg)

![Connect the touchpad module boards — phenom_bg_26_02.jpg](images/phenom_bg_26_02.jpg)

### Step 27. Secure the touchpad module electronics

Fit the touchpad and acrylic overlay. Secure the [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) with M2x4 screws and the [connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) with M2x4 flat screws. Route the cables so they do not interfere with the bottom cover

![Secure the touchpad module electronics — phenom_bg_27_01.jpg](images/phenom_bg_27_01.jpg)

![Secure the touchpad module electronics — phenom_bg_27_02.jpg](images/phenom_bg_27_02.jpg)

![Secure the touchpad module electronics — phenom_bg_27_03.jpg](images/phenom_bg_27_03.jpg)

![Secure the touchpad module electronics — phenom_bg_27_04.jpg](images/phenom_bg_27_04.jpg)

![Secure the touchpad module electronics — phenom_bg_27_05.jpg](images/phenom_bg_27_05.jpg)

![Secure the touchpad module electronics — phenom_bg_27_06.jpg](images/phenom_bg_27_06.jpg)

![Secure the touchpad module electronics — phenom_bg_27_07.jpg](images/phenom_bg_27_07.jpg)

### Step 28. Finish the touchpad module

Fit the left module bottom cover ([STL](../stl/modules/touchpad/Phenom-tp-bot-left.stl), [STEP](../step/modules/touchpad/Phenom-tp-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/touchpad/Phenom-tp-bot-right.stl), [STEP](../step/modules/touchpad/Phenom-tp-bot-right.stp)) and apply three Bumpons 8x2 mm feet

![Finish the touchpad module — phenom_bg_28_01.jpg](images/phenom_bg_28_01.jpg)

![Finish the touchpad module — phenom_bg_28_02.jpg](images/phenom_bg_28_02.jpg)

## Trackball module

### Step 29. Prepare the trackball module parts

Prepare the left module housing ([STL](../stl/modules/trackball/Phenom-tb-body-left.stl), [STEP](../step/modules/trackball/Phenom-tb-body-left.stp)) and right module housing ([STL](../stl/modules/trackball/Phenom-tb-body-right.stl), [STEP](../step/modules/trackball/Phenom-tb-right.stp)), left module bottom cover ([STL](../stl/modules/trackball/Phenom-tb-bot-left.stl), [STEP](../step/modules/trackball/Phenom-tb-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/trackball/Phenom-tb-bot-right.stl), [STEP](../step/modules/trackball/Phenom-tb-bot-right.stp)), [Pogo system module PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip), [Pogo system base PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip), [Trackball PCB](../pcb/modules/trackball/Gerber_PCB_Trackball.zip) and [Led PCB](../pcb/modules/Gerber_PCB_Led.zip), the PMW3610 sensor, LM18-LSI lens, and dark-red 32 mm trackball

![Prepare the trackball module parts — phenom_bg_29_01.jpg](images/phenom_bg_29_01.jpg)

### Step 30. Solder the trackball module pogo contacts

Install and solder eight 7 mm pogo contacts to the [module connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) in the orientation shown

![Solder the trackball module pogo contacts — phenom_bg_30_01.jpg](images/phenom_bg_30_01.jpg)

![Solder the trackball module pogo contacts — phenom_bg_30_02.jpg](images/phenom_bg_30_02.jpg)

![Solder the trackball module pogo contacts — phenom_bg_30_03.jpg](images/phenom_bg_30_03.jpg)

### Step 31. Assemble the trackball sensor board

Install and solder the sensor-board connector and PMW3610 sensor. Check the solder joints and fit the LM18-LSI lens

![Assemble the trackball sensor board — phenom_bg_31_01.jpg](images/phenom_bg_31_01.jpg)

![Assemble the trackball sensor board — phenom_bg_31_02.jpg](images/phenom_bg_31_02.jpg)

![Assemble the trackball sensor board — phenom_bg_31_03.jpg](images/phenom_bg_31_03.jpg)

![Assemble the trackball sensor board — phenom_bg_31_04.jpg](images/phenom_bg_31_04.jpg)

![Assemble the trackball sensor board — phenom_bg_31_05.jpg](images/phenom_bg_31_05.jpg)

![Assemble the trackball sensor board — phenom_bg_31_06.jpg](images/phenom_bg_31_06.jpg)

![Assemble the trackball sensor board — phenom_bg_31_07.jpg](images/phenom_bg_31_07.jpg)

![Assemble the trackball sensor board — phenom_bg_31_08.jpg](images/phenom_bg_31_08.jpg)

![Assemble the trackball sensor board — phenom_bg_31_09.jpg](images/phenom_bg_31_09.jpg)

![Assemble the trackball sensor board — phenom_bg_31_10.jpg](images/phenom_bg_31_10.jpg)

![Assemble the trackball sensor board — phenom_bg_31_11.jpg](images/phenom_bg_31_11.jpg)

![Assemble the trackball sensor board — phenom_bg_31_12.jpg](images/phenom_bg_31_12.jpg)

![Assemble the trackball sensor board — phenom_bg_31_13.jpg](images/phenom_bg_31_13.jpg)

![Assemble the trackball sensor board — phenom_bg_31_14.jpg](images/phenom_bg_31_14.jpg)

![Assemble the trackball sensor board — phenom_bg_31_15.jpg](images/phenom_bg_31_15.jpg)

### Step 32. Connect the trackball module boards

Connect the [sensor board](../pcb/modules/trackball/Gerber_PCB_Trackball.zip) to the [module connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) with a JST SH 1.0 6-Pin 60mm cable, and connect the [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) with a JST SH 1.0 4-Pin 50mm cable

![Connect the trackball module boards — phenom_bg_32_01.jpg](images/phenom_bg_32_01.jpg)

![Connect the trackball module boards — phenom_bg_32_02.jpg](images/phenom_bg_32_02.jpg)

![Connect the trackball module boards — phenom_bg_32_03.jpg](images/phenom_bg_32_03.jpg)

![Connect the trackball module boards — phenom_bg_32_04.jpg](images/phenom_bg_32_04.jpg)

### Step 33. Prepare the trackball housing and docking area

Fit the white LED insert ([STL](../stl/modules/Phenom-led-insert.stl), [STEP](../step/modules/Phenom-led-insert.stp)) and check that the left module housing ([STL](../stl/modules/trackball/Phenom-tb-body-left.stl), [STEP](../step/modules/trackball/Phenom-tb-body-left.stp)) and right module housing ([STL](../stl/modules/trackball/Phenom-tb-body-right.stl), [STEP](../step/modules/trackball/Phenom-tb-right.stp)) aligns with the keyboard

Install eight Bar Magnet 5x2x10mm magnets with the opposite mating pole to the case magnets. Before inserting each magnet into the module, check that its mating face is attracted to the case

![Prepare the trackball housing and docking area — phenom_bg_33_01.jpg](images/phenom_bg_33_01.jpg)

![Prepare the trackball housing and docking area — phenom_bg_33_02.jpg](images/phenom_bg_33_02.jpg)

![Prepare the trackball housing and docking area — phenom_bg_33_03.jpg](images/phenom_bg_33_03.jpg)

### Step 34. Secure the trackball module electronics

Secure the [sensor board](../pcb/modules/trackball/Gerber_PCB_Trackball.zip) and [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) with M2x4 screws, and the [connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) with M2x4 flat screws. Route the cables clear of the optical opening and bottom cover

![Secure the trackball module electronics — phenom_bg_34_01.jpg](images/phenom_bg_34_01.jpg)

![Secure the trackball module electronics — phenom_bg_34_02.jpg](images/phenom_bg_34_02.jpg)

![Secure the trackball module electronics — phenom_bg_34_03.jpg](images/phenom_bg_34_03.jpg)

![Secure the trackball module electronics — phenom_bg_34_04.jpg](images/phenom_bg_34_04.jpg)

### Step 35. Install the support balls

Press three 3 mm support balls into the bowl recesses using a suitable rounded tool

> [!WARNING]
> Do not use the trackball itself to press the support balls into place: this can deform its surface

![Install the support balls — phenom_bg_35_01.jpg](images/phenom_bg_35_01.jpg)

![Install the support balls — phenom_bg_35_02.jpg](images/phenom_bg_35_02.jpg)

![Install the support balls — phenom_bg_35_03.jpg](images/phenom_bg_35_03.jpg)

### Step 36. Close the trackball module

Fit the left module bottom cover ([STL](../stl/modules/trackball/Phenom-tb-bot-left.stl), [STEP](../step/modules/trackball/Phenom-tb-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/trackball/Phenom-tb-bot-right.stl), [STEP](../step/modules/trackball/Phenom-tb-bot-right.stp)) and apply three Bumpons 8x2 mm feet

![Close the trackball module — phenom_bg_36_01.jpg](images/phenom_bg_36_01.jpg)

![Close the trackball module — phenom_bg_36_02.jpg](images/phenom_bg_36_02.jpg)

### Step 37. Install the trackball

Place the dark-red 32 mm trackball in the bowl. Check that it rests on all three support balls and rotates without binding

![Install the trackball — phenom_bg_37_01.jpg](images/phenom_bg_37_01.jpg)

![Install the trackball — phenom_bg_37_02.jpg](images/phenom_bg_37_02.jpg)
