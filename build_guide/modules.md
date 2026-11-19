# Phenom PCB assembly guide — Modules

![Phenom encoder, touchpad and trackball modules](images/phenom_modules.jpg)

[Keyboard body assembly guide](body.md)

## Before assembly

Assemble the keyboard body first, then follow the sections for the modules you need

Download the module models: [STL](../stl/modules/) or [STEP](../step/modules/). Encoder, trackball and touchpad parts are in their respective subfolders; the shared LED insert is in the modules root

The photographs show boards with SMD components already installed. Full SMD assembly is not covered by this guide

## BOM

Each table covers one complete module and applies to either keyboard half; only the printed housing determines the module side. Each table already includes its pogo system base and module boards; do not add another shared pogo system BOM on top of these quantities

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

## Encoder module

### Step 01. Prepare the encoder module parts

Prepare the left module housing ([STL](../stl/modules/encoder/Phenom-enc-body-left.stl), [STEP](../step/modules/encoder/Phenom-enc-body-left.stp)) and right module housing ([STL](../stl/modules/encoder/Phenom-enc-body-right.stl), [STEP](../step/modules/encoder/Phenom-enc-body-right.stp)), left module bottom cover ([STL](../stl/modules/encoder/Phenom-enc-bot-left.stl), [STEP](../step/modules/encoder/Phenom-enc-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/encoder/Phenom-enc-bot-right.stl), [STEP](../step/modules/encoder/Phenom-enc-bot-right.stp)), [Pogo system module PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip), [Pogo system base PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip), [Encoder PCB](../pcb/modules/encoder/Gerber_PCB_Encoder.zip) and [Led PCB](../pcb/modules/Gerber_PCB_Led.zip), an EC11 encoder, and an Encoder Knob 26x17mm, Black

<details>
<summary>Step illustrations</summary>

![Prepare the encoder module parts — phenom_bg_15_01.jpg](images/phenom_bg_15_01.jpg)

</details>

### Step 02. Solder the encoder module pogo contacts

Install and solder eight 7 mm pogo contacts to the [module connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) in the orientation shown. Check that they are straight and move freely

<details>
<summary>Step illustrations</summary>

![Solder the encoder module pogo contacts — phenom_bg_16_01.jpg](images/phenom_bg_16_01.jpg)

![Solder the encoder module pogo contacts — phenom_bg_16_02.jpg](images/phenom_bg_16_02.jpg)

![Solder the encoder module pogo contacts — phenom_bg_16_03.jpg](images/phenom_bg_16_03.jpg)

</details>

### Step 03. Solder the encoder

Fit the EC11 encoder to the [Encoder PCB](../pcb/modules/encoder/Gerber_PCB_Encoder.zip) and solder its leads

<details>
<summary>Step illustrations</summary>

![Solder the encoder — phenom_bg_17_01.jpg](images/phenom_bg_17_01.jpg)

![Solder the encoder — phenom_bg_17_02.jpg](images/phenom_bg_17_02.jpg)

</details>

### Step 04. Connect the encoder module boards

Connect a JST SH 1.0 6-Pin 60mm cable to the [encoder board](../pcb/modules/encoder/Gerber_PCB_Encoder.zip) and a JST SH 1.0 4-Pin 50mm cable to the [Led PCB](../pcb/modules/Gerber_PCB_Led.zip)

<details>
<summary>Step illustrations</summary>

![Connect the encoder module boards — phenom_bg_18_01.jpg](images/phenom_bg_18_01.jpg)

![Connect the encoder module boards — phenom_bg_18_02.jpg](images/phenom_bg_18_02.jpg)

![Connect the encoder module boards — phenom_bg_18_03.jpg](images/phenom_bg_18_03.jpg)

![Connect the encoder module boards — phenom_bg_18_04.jpg](images/phenom_bg_18_04.jpg)

</details>

### Step 05. Prepare the encoder housing and docking area

Fit the white LED insert ([STL](../stl/modules/Phenom-led-insert.stl), [STEP](../step/modules/Phenom-led-insert.stp)) into its seat in the housing. Check that the left module housing ([STL](../stl/modules/encoder/Phenom-enc-body-left.stl), [STEP](../step/modules/encoder/Phenom-enc-body-left.stp)) and right module housing ([STL](../stl/modules/encoder/Phenom-enc-body-right.stl), [STEP](../step/modules/encoder/Phenom-enc-body-right.stp)) aligns with the keyboard docking area

Install five Bar Magnet 5x2x10mm magnets with the opposite mating pole to the case magnets. Before inserting each magnet into the module, check that its mating face is attracted to the case

<details>
<summary>Step illustrations</summary>

![Prepare the encoder housing and docking area — phenom_bg_19_01.jpg](images/phenom_bg_19_01.jpg)

![Prepare the encoder housing and docking area — phenom_bg_19_02.jpg](images/phenom_bg_19_02.jpg)

![Prepare the encoder housing and docking area — phenom_bg_19_03.jpg](images/phenom_bg_19_03.jpg)

</details>

### Step 06. Secure the encoder module boards

Secure the [connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) with M2x4 flat screws, and the [encoder board](../pcb/modules/encoder/Gerber_PCB_Encoder.zip) and [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) with M2x4 screws. Route cables without tension or pinching

<details>
<summary>Step illustrations</summary>

![Secure the encoder module boards — phenom_bg_20_01.jpg](images/phenom_bg_20_01.jpg)

![Secure the encoder module boards — phenom_bg_20_02.jpg](images/phenom_bg_20_02.jpg)

![Secure the encoder module boards — phenom_bg_20_03.jpg](images/phenom_bg_20_03.jpg)

![Secure the encoder module boards — phenom_bg_20_04.jpg](images/phenom_bg_20_04.jpg)

</details>

### Step 07. Finish the encoder module

Fit the left module bottom cover ([STL](../stl/modules/encoder/Phenom-enc-bot-left.stl), [STEP](../step/modules/encoder/Phenom-enc-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/encoder/Phenom-enc-bot-right.stl), [STEP](../step/modules/encoder/Phenom-enc-bot-right.stp)) and encoder knob. Apply three Bumpons 8x2 mm feet

<details>
<summary>Step illustrations</summary>

![Finish the encoder module — phenom_bg_21_01.jpg](images/phenom_bg_21_01.jpg)

![Finish the encoder module — phenom_bg_21_02.jpg](images/phenom_bg_21_02.jpg)

![Finish the encoder module — phenom_bg_21_03.jpg](images/phenom_bg_21_03.jpg)

</details>

## Touchpad module

### Step 08. Prepare the touchpad module parts

Prepare the left module housing ([STL](../stl/modules/touchpad/Phenom-tp-body-left.stl), [STEP](../step/modules/touchpad/Phenom-tp-body-left.stp)) and right module housing ([STL](../stl/modules/touchpad/Phenom-tp-body-right.stl), [STEP](../step/modules/touchpad/Phenom-tp-body-right.stp)), left module bottom cover ([STL](../stl/modules/touchpad/Phenom-tp-bot-left.stl), [STEP](../step/modules/touchpad/Phenom-tp-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/touchpad/Phenom-tp-bot-right.stl), [STEP](../step/modules/touchpad/Phenom-tp-bot-right.stp)), [Pogo system module PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip), [Pogo system base PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip) and [Led PCB](../pcb/modules/Gerber_PCB_Led.zip), the Azoteq IQS43 Sensor touchpad, and the Acrylic Touchpad Plate

<details>
<summary>Step illustrations</summary>

![Prepare the touchpad module parts — phenom_bg_22_01.jpg](images/phenom_bg_22_01.jpg)

</details>

### Step 09. Prepare the touchpad connection board

Install and solder six 7 mm pogo contacts. Install and solder the four-pin PH2.0 connector with 2 mm pitch and a 90-degree angle

Check the connector orientation against the schematic. Trim the protruding leads as shown without damaging the solder joints

<details>
<summary>Step illustrations</summary>

![Prepare the touchpad connection board — phenom_bg_23_01.jpg](images/phenom_bg_23_01.jpg)

![Prepare the touchpad connection board — phenom_bg_23_02.jpg](images/phenom_bg_23_02.jpg)

![Prepare the touchpad connection board — phenom_bg_23_03.jpg](images/phenom_bg_23_03.jpg)

![Prepare the touchpad connection board — phenom_bg_23_04.jpg](images/phenom_bg_23_04.jpg)

![Prepare the touchpad connection board — phenom_bg_23_05.jpg](images/phenom_bg_23_05.jpg)

![Prepare the touchpad connection board — phenom_bg_23_06.jpg](images/phenom_bg_23_06.jpg)

![Prepare the touchpad connection board — phenom_bg_23_07.jpg](images/phenom_bg_23_07.jpg)

</details>

### Step 10. Connect the touchpad cable and prepare the overlay

Prepare the PH2.0 4 Pins 60mm one head cable. Solder its free ends to the touchpad pads according to the verified pinout

Secure the soldered cable exit with hot glue. Apply the acrylic overlay

<details>
<summary>Step illustrations</summary>

![Connect the touchpad cable and prepare the overlay — phenom_bg_24_01.jpg](images/phenom_bg_24_01.jpg)

![Connect the touchpad cable and prepare the overlay — phenom_bg_24_02.jpg](images/phenom_bg_24_02.jpg)

![Connect the touchpad cable and prepare the overlay — phenom_bg_24_03.jpg](images/phenom_bg_24_03.jpg)

</details>

### Step 11. Prepare the touchpad housing and docking area

Fit the white LED insert ([STL](../stl/modules/Phenom-led-insert.stl), [STEP](../step/modules/Phenom-led-insert.stp)) and check that the left module housing ([STL](../stl/modules/touchpad/Phenom-tp-body-left.stl), [STEP](../step/modules/touchpad/Phenom-tp-body-left.stp)) and right module housing ([STL](../stl/modules/touchpad/Phenom-tp-body-right.stl), [STEP](../step/modules/touchpad/Phenom-tp-body-right.stp)) aligns with the keyboard

Install five Bar Magnet 5x2x10mm magnets with the opposite mating pole to the case magnets. Before inserting each magnet into the module, check that its mating face is attracted to the case

<details>
<summary>Step illustrations</summary>

![Prepare the touchpad housing and docking area — phenom_bg_25_01.jpg](images/phenom_bg_25_01.jpg)

![Prepare the touchpad housing and docking area — phenom_bg_25_02.jpg](images/phenom_bg_25_02.jpg)

![Prepare the touchpad housing and docking area — phenom_bg_25_03.jpg](images/phenom_bg_25_03.jpg)

![Prepare the touchpad housing and docking area — phenom_bg_25_04.jpg](images/phenom_bg_25_04.jpg)

</details>

### Step 12. Connect the touchpad module boards

Connect the touchpad using the prepared PH2.0 cable, and the [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) using a JST SH 1.0 4-Pin 50mm cable

<details>
<summary>Step illustrations</summary>

![Connect the touchpad module boards — phenom_bg_26_01.jpg](images/phenom_bg_26_01.jpg)

![Connect the touchpad module boards — phenom_bg_26_02.jpg](images/phenom_bg_26_02.jpg)

</details>

### Step 13. Secure the touchpad module electronics

Fit the touchpad and acrylic overlay. Secure the [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) with M2x4 screws and the [connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) with M2x4 flat screws. Route the cables so they do not interfere with the bottom cover

<details>
<summary>Step illustrations</summary>

![Secure the touchpad module electronics — phenom_bg_27_01.jpg](images/phenom_bg_27_01.jpg)

![Secure the touchpad module electronics — phenom_bg_27_02.jpg](images/phenom_bg_27_02.jpg)

![Secure the touchpad module electronics — phenom_bg_27_03.jpg](images/phenom_bg_27_03.jpg)

![Secure the touchpad module electronics — phenom_bg_27_04.jpg](images/phenom_bg_27_04.jpg)

![Secure the touchpad module electronics — phenom_bg_27_05.jpg](images/phenom_bg_27_05.jpg)

![Secure the touchpad module electronics — phenom_bg_27_06.jpg](images/phenom_bg_27_06.jpg)

![Secure the touchpad module electronics — phenom_bg_27_07.jpg](images/phenom_bg_27_07.jpg)

</details>

### Step 14. Finish the touchpad module

Fit the left module bottom cover ([STL](../stl/modules/touchpad/Phenom-tp-bot-left.stl), [STEP](../step/modules/touchpad/Phenom-tp-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/touchpad/Phenom-tp-bot-right.stl), [STEP](../step/modules/touchpad/Phenom-tp-bot-right.stp)) and apply three Bumpons 8x2 mm feet

<details>
<summary>Step illustrations</summary>

![Finish the touchpad module — phenom_bg_28_01.jpg](images/phenom_bg_28_01.jpg)

![Finish the touchpad module — phenom_bg_28_02.jpg](images/phenom_bg_28_02.jpg)

</details>

## Trackball module

### Step 15. Prepare the trackball module parts

Prepare the left module housing ([STL](../stl/modules/trackball/Phenom-tb-body-left.stl), [STEP](../step/modules/trackball/Phenom-tb-body-left.stp)) and right module housing ([STL](../stl/modules/trackball/Phenom-tb-body-right.stl), [STEP](../step/modules/trackball/Phenom-tb-right.stp)), left module bottom cover ([STL](../stl/modules/trackball/Phenom-tb-bot-left.stl), [STEP](../step/modules/trackball/Phenom-tb-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/trackball/Phenom-tb-bot-right.stl), [STEP](../step/modules/trackball/Phenom-tb-bot-right.stp)), [Pogo system module PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip), [Pogo system base PCB](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_base.zip), [Trackball PCB](../pcb/modules/trackball/Gerber_PCB_Trackball.zip) and [Led PCB](../pcb/modules/Gerber_PCB_Led.zip), the PMW3610 sensor, LM18-LSI lens, and dark-red 32 mm trackball

<details>
<summary>Step illustrations</summary>

![Prepare the trackball module parts — phenom_bg_29_01.jpg](images/phenom_bg_29_01.jpg)

</details>

### Step 16. Solder the trackball module pogo contacts

Install and solder eight 7 mm pogo contacts to the [module connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) in the orientation shown

<details>
<summary>Step illustrations</summary>

![Solder the trackball module pogo contacts — phenom_bg_30_01.jpg](images/phenom_bg_30_01.jpg)

![Solder the trackball module pogo contacts — phenom_bg_30_02.jpg](images/phenom_bg_30_02.jpg)

![Solder the trackball module pogo contacts — phenom_bg_30_03.jpg](images/phenom_bg_30_03.jpg)

</details>

### Step 17. Assemble the trackball sensor board

Install and solder the sensor-board connector and PMW3610 sensor. Check the solder joints and fit the LM18-LSI lens

<details>
<summary>Step illustrations</summary>

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

</details>

### Step 18. Connect the trackball module boards

Connect the [sensor board](../pcb/modules/trackball/Gerber_PCB_Trackball.zip) to the [module connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) with a JST SH 1.0 6-Pin 60mm cable, and connect the [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) with a JST SH 1.0 4-Pin 50mm cable

<details>
<summary>Step illustrations</summary>

![Connect the trackball module boards — phenom_bg_32_01.jpg](images/phenom_bg_32_01.jpg)

![Connect the trackball module boards — phenom_bg_32_02.jpg](images/phenom_bg_32_02.jpg)

![Connect the trackball module boards — phenom_bg_32_03.jpg](images/phenom_bg_32_03.jpg)

![Connect the trackball module boards — phenom_bg_32_04.jpg](images/phenom_bg_32_04.jpg)

</details>

### Step 19. Prepare the trackball housing and docking area

Fit the white LED insert ([STL](../stl/modules/Phenom-led-insert.stl), [STEP](../step/modules/Phenom-led-insert.stp)) and check that the left module housing ([STL](../stl/modules/trackball/Phenom-tb-body-left.stl), [STEP](../step/modules/trackball/Phenom-tb-body-left.stp)) and right module housing ([STL](../stl/modules/trackball/Phenom-tb-body-right.stl), [STEP](../step/modules/trackball/Phenom-tb-right.stp)) aligns with the keyboard

Install eight Bar Magnet 5x2x10mm magnets with the opposite mating pole to the case magnets. Before inserting each magnet into the module, check that its mating face is attracted to the case

<details>
<summary>Step illustrations</summary>

![Prepare the trackball housing and docking area — phenom_bg_33_01.jpg](images/phenom_bg_33_01.jpg)

![Prepare the trackball housing and docking area — phenom_bg_33_02.jpg](images/phenom_bg_33_02.jpg)

![Prepare the trackball housing and docking area — phenom_bg_33_03.jpg](images/phenom_bg_33_03.jpg)

</details>

### Step 20. Secure the trackball module electronics

Secure the [sensor board](../pcb/modules/trackball/Gerber_PCB_Trackball.zip) and [Led PCB](../pcb/modules/Gerber_PCB_Led.zip) with M2x4 screws, and the [connection board](../pcb/pogo_system/Gerber_PCB_Phenom_pogo_system_module.zip) with M2x4 flat screws. Route the cables clear of the optical opening and bottom cover

<details>
<summary>Step illustrations</summary>

![Secure the trackball module electronics — phenom_bg_34_01.jpg](images/phenom_bg_34_01.jpg)

![Secure the trackball module electronics — phenom_bg_34_02.jpg](images/phenom_bg_34_02.jpg)

![Secure the trackball module electronics — phenom_bg_34_03.jpg](images/phenom_bg_34_03.jpg)

![Secure the trackball module electronics — phenom_bg_34_04.jpg](images/phenom_bg_34_04.jpg)

</details>

### Step 21. Install the support balls

Press three 3 mm support balls into the bowl recesses using a suitable rounded tool

> [!WARNING]
> Do not use the trackball itself to press the support balls into place: this can deform its surface

<details>
<summary>Step illustrations</summary>

![Install the support balls — phenom_bg_35_01.jpg](images/phenom_bg_35_01.jpg)

![Install the support balls — phenom_bg_35_02.jpg](images/phenom_bg_35_02.jpg)

![Install the support balls — phenom_bg_35_03.jpg](images/phenom_bg_35_03.jpg)

</details>

### Step 22. Close the trackball module

Fit the left module bottom cover ([STL](../stl/modules/trackball/Phenom-tb-bot-left.stl), [STEP](../step/modules/trackball/Phenom-tb-bot-left.stp)) and right module bottom cover ([STL](../stl/modules/trackball/Phenom-tb-bot-right.stl), [STEP](../step/modules/trackball/Phenom-tb-bot-right.stp)) and apply three Bumpons 8x2 mm feet

<details>
<summary>Step illustrations</summary>

![Close the trackball module — phenom_bg_36_01.jpg](images/phenom_bg_36_01.jpg)

![Close the trackball module — phenom_bg_36_02.jpg](images/phenom_bg_36_02.jpg)

</details>

### Step 23. Install the trackball

Place the dark-red 32 mm trackball in the bowl. Check that it rests on all three support balls and rotates without binding

<details>
<summary>Step illustrations</summary>

![Install the trackball — phenom_bg_37_01.jpg](images/phenom_bg_37_01.jpg)

![Install the trackball — phenom_bg_37_02.jpg](images/phenom_bg_37_02.jpg)

</details>
