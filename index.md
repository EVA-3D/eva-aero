---
badges:
    - Official
---
# Aero

![preview](assets/Aero.__ALL__.png)

E3D Aero is a difficult to align extruder. It's one of those "front heavy" ones, where the motor is not over the center of the MGN Carriage but instead is "pulling" the carriage down by the front - this does not mean that it's worse than the others and will most likely not be enough for a MGN carriage to even care - just something to have in mind. That and the fact that due to the dimensions of it's assembly the whole print area of one's printer may not be accessible.

??? question "Why not bellow the rail?"

    I tried that. The distance to the anchor (MGN Carriage) with the weight of the motor produced enough force to output very bad Y ghosting. 

Aero has two options for bed probe mounting - one on the side (taking away X space) and one of the front (taking away Y space) with a different `aero_front_probe` part (listed in the BOM).

Assemble the carriage on the rail, add the motor and Aero last.

!!! tip "Custom Titan Tension Arm"

    ![Placeholder](assets/SSX.png){: align=left }
    The BOM contains my remix of the [E3D Titan Flex Upgrade](https://www.thingiverse.com/thing:2426505) thing which improves the Titan filament path greatly.  
    My remix improves it's printability - print on the side where the spring is. No supports are needed.

??? notice "MGN15"

    To mount EVA / Aero on a MGN15C carriage you will need a few different than the default parts and a few longer screws. The BOM replaces **only a few parts and screws** from the default BOM - for MGN15C you need to look at both - **what follows is not the full MGN15C BOM**.

{{ bom("drives/aero/bom/BOM_Aero.MGN15.csv", 4) }}

### Links

{{ eva_download_button("aero") }}

{{ eva_link("aero") }}

{{ onshape_link("aero") }}

### BOM

{{ bom("drives/aero/bom/BOM_Aero.__ALL__.csv", 0) }}

