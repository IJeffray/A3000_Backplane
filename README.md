# Acorn A3000 three-slot backplane

June 2023


![3D View](Generated/A3000_Backplane_3D_View.PNG)

A three-slot backplane for Acorn A3000 machines.
Designed to mechanically suit the Wild Vision A3000 Podule expansion box - this board relies on the A3000 motherboard having been patched with two wires to bring LA21 and S4* out to previously-unused pins on the external expansion connector.  The backplane then uses these two extra signals to generate new PSx and MSx signals using an onboard HC139, identically to how other backplanes operate.  The A3000 has this function on the motherboard (IC33), but only tracks-out podules 0 and 1 for the single internal and single external podule.

This design has not been built or tested yet.

## Licence

No warranty is provided, and this work is used at your own risk.  

Licenced as CC BY-SA 3.0

Copyright 2023 Ian Jeffray
