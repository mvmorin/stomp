# Keyboard Parts
KiCad library of MX and Alps compatible footprints and other miscellaneous footprints and symbols.

# Design
The main focus is the ease of PCB and plate creation. The switch footprints and symbol already have the diodes included. This eliminates almost half of the components and traces. Each switch footprint also comes with the corresponding plate-cutout for both MX and Alps switches as well as a silk-screen layer for the plate. The PCB can then serve as the master for the plate with the corresponding layers being exported for use in the plate design. The cutouts are mainly aimed at PCB/FR4 plates and are/will be dimensioned to accommodate the looser tolerances of PCB-milling.

# Features
* Combined switch-and-diode footprints.
* *eco1*-layer: Outline for MX cutouts.
* *eco2*-layer: Outline for Alps cutouts.
* *cmts*-layer: Silk-screen for plate.

The main benefit of these footprints is the extra information of the keyboard backplate they contain. To easily export these features to the backplate KiCad project, the *eco1*, *eco2*, and *cmts* layers of all other footprints used need to either be empty or contain the corresponding information.

# Known Issues
* ~~Alps cutouts are a little tight. About 60% of the cutouts in the test print needed filing.~~
* ~~Cherry stabilizer cutout are tight but usable.~~

# Untested Footprints
Footprint features that not have been test printed/manufactured:
* The new 0.1mm larger Alps switch and MX stabilizer cutouts.
* The double sided switch footprints.

# Licenses
[![License: CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

The library is released under the [Creative Commons CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode) license, Copyright (c) Martin Morin 2020.
Some footprints and symbols are based on parts from the [KiCad libraries](https://kicad-pcb.org/libraries/), released under the same [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode) license.
