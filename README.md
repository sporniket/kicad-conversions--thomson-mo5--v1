# Conversion of the Thomson MO5 main board into Kicad

> [WARNING] Please read carefully this note before using this project. It contains important facts.

Content

1. What is **Conversion of the Thomson MO5 main board into Kicad**, and when to use it ?
2. What should you know before using **Conversion of the Thomson MO5 main board into Kicad** ?
3. How to use **Conversion of the Thomson MO5 main board into Kicad** ?
4. Known issues
5. Miscellanous

## 1. What is **Conversion of the Thomson MO5 main board into Kicad**, and when to use it ?

**Conversion of the Thomson MO5 main board into Kicad** is a conversion to Kicad EDA of the schematics of a computer released around 1984 known as the "Thomson MO5". 


### Licence

**Conversion of the Thomson MO5 main board into Kicad** is published under the Creative Commons CC0 license. You can find a copy of the licence there : https://creativecommons.org/publicdomain/zero/1.0/legalcode

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

**Conversion of the Thomson MO5 main board into Kicad** is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

### Release notes

#### v1.0.0-beta-2

* Issue #1 -- Small corrections for beta2
  * Schematic -- fixes unit of L01, 'nH' instead of 'mH'
  * wider lateral chamfers for extension connector, set to 1mm along x and y axis
  * prevent a small copper pour of GND inside the extension connector
  * exclude copper pour around internal mounting holes (front layer)
  * tweak the width of the pads of the extension connector, from 2mm to 1.5mm

* Issue #2 -- Small enhancements for beta2
  * Silkscreen -- add text to render REVISION and ISSUE_DATE
  * enlarge vias for modding cartridge port to get E and R/W 
  * Some additionnal fixes of DRC violations
  * Schematic -- D02 value becomes 'BZX46C12'
  * Reset switch -- ad-hoc footprint to combine regular switch with the original reset button footprint

#### v1.0.0-beta-1

The PCB is finished, ready for testing (mechanical, actual assembly) to spot errors.

#### v1.0.0-alpha-1 to v1.0.0-alpha-6

The whole schematics has been captured, need proofreading. A new alpha is produced regularly after some fixes are commited.

## 2. What should you know before using **Conversion of the Thomson MO5 main board into Kicad** ?

**Conversion of the Thomson MO5 main board into Kicad** is made using Kicad 7.

> Do not use **Conversion of the Thomson MO5 main board into Kicad** if this project is not suitable for your project.

## 3. How to use **Conversion of the Thomson MO5 main board into Kicad** ?

### From sources

To get the latest available work, one must clone the git repository.

	git clone --recurse-submodules https://github.com/sporniket/kicad-conversions--thomson-mo5--v1.git

Then, open the project with Kicad 7.

## 4. Known issues
See the [project issues](https://github.com/sporniket/kicad-conversions--thomson-mo5--v1/issues) page.

## 5. Miscellanous

### Report issues
Use the [project issues](https://github.com/sporniket/kicad-conversions--thomson-mo5--v1/issues) page.
