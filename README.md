# Lak
![Lak Photo](images/lak.jpeg)

Lak is a 40-key macro ~~pad~~ board

The stl files in this repo, with the rest of the physical components outlined in the bill of materials, can be used to create a 40-key programmable macroboard.

Lak is a hand-wired keyboard project powered by a [nice!nano](https://nicekeyboards.com/nice-nano) V1 and [ZMK](https://zmk.dev).
The shield config, keymap, and a prebuilt uf2 can be found [here](https://github.com/BrokenFlows/zmk-brokenflows).

## Instructions

The following instructions will provide details on how to assemble the project as well as covering the materials required.
The project requires some readily available keyboard components, some custom 3D printed components, and a nice!nano microcontroller which (at the time of writing) is available at somewhat frequent but irregular intervals.

### Hardware

The [tools](#Tools) and [materials](#Bill-of-Materials) will be used to assemble the final product, shown above. Once you have acquired the items required, you can follow the steps outlined in the [assembly](#Pre-assembly) section.

#### Tools
- Soldering Iron
- Solder Wire
- 3D Printer/ 3D Printing Service/ or some means of mimicking [the case and parts](./stls/) listed below
- Scissors/ wire cutter
- Glue/ Hot Glue Gun
- **Optional:** wire stripper


#### Bill of Materials
Item # | Quantity | Part Name                                                 | Description
------:|---------:|:----------------------------------------------------------|-------------
1      | 1        | [lak case.stl](./stls/lak\ case.stl)                      | The case and integrated switch plate for the keyboard
2      | 1        | [lak sled.stl](./stls/lak\ sled.stl)                      | The housing for the nice!nano at the back of the case
3      | 1        | [lak base plate.stl](./stls/lak\ base\ plate.stl)         | The bottom cover for the keyboard, to protect the wiring once built
4      | 40       | [MX-Style Switches](https://kbdfans.com/collections/gateron-swithes/products/gateron-swtich-3pin-or-5pin?variant=35765200333) | MX-style key switches will serve as the button mechanism
5      | 40       | [MX-Style Keycaps](https://www.adafruit.com/product/5039) | MX-style keycaps, a uniform profile will work best
6      | 40       | [Diodes](https://www.adafruit.com/product/1641)           | Diodes for creating the key matrix
7      | 6        | [Wires](https://www.ebay.ie/itm/232901601951)             | Lengths of wire to create the key matrix

The above BoM lists uniform profile keycaps and links to relegendable keycaps. I used a mixture of both of the following in my build:
- [Relgendable MX-Style Keycaps](https://www.adafruit.com/product/5039)
- [DSA Blank Keycaps](https://kbdfans.com/collections/dsa-profile/products/dsa-blank-keycaps-1u-10pcs)
If mixing and matching, or just getting one set, be sure to have 40 keycaps available for your build.

#### 3D Printing
I recommend 3D printing the stl files at the following settings:
Setting         | Value
:---------------|-----:
Filament        | PLA
Nozzle Diameter | < 0.4 mm
Layer Height    | < 0.2 mm
Infill          | 20% <
Supports        | Off


