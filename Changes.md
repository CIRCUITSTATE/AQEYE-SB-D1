
# Changes

#
### **+05:30 10:56:55 AM 15-06-2025, Sunday**

  - Updated Readme.
  - Added poster image.
  - Generated PCB renders without the Asair sensors.

#
### **+05:30 05:03:43 PM 07-06-2025, Saturday**

  - Schematic
    - Realized that the main board can not supply 5V when the USB is not connected.
    - Added a `TPS61023` 5V boost converter to generate 5V from the 3.3V input.
    - Removed the 5V load switch since the 5V output can not be controlled via the boost converter.
    - The 5V converter enabled by default with a GPIO control.
    - Added `LM66100DCKR` single-channel ideal diode to connect the VBUS to the 5V rail.
    - Reset the annotations.
    - Updated the BoM.
  - PCB
    - Imported all changes to the PCB.
    - Placement and routing completed.
    - DRC passes.
    - Updated Fab layers.
    - Updated KiExport configuration.
      - New STEP and VRML options are added.
  - Generated manufacturing files.
  - No version change.

#
### **+05:30 06:52:30 PM 06-06-2025, Friday**

  - Schematic
    - Updated BoM.
    - Assigned all MPNs.
    - Added `Group by MPN-DNP` preset.
  - PCB
    - Imported all changes to the PCB.
    - Cleaned up the Fab layers.
    - Added CIRCUITSTATE logo and GitHub link to schematic.
    - Applied teardrops.
    - Added board stackup table and characteristics.
    - DRC passes.
  - Added KiExport configuration.
  - Added Git scripts.
  - Generated manufacturing files.

#
### **+05:30 09:57:26 PM 05-06-2025, Thursday**

  - Schematic
    - Completed the schematic.
    - Assigned all footprints.
    - Added net classes and colors.
    - ERC passes.
  - PCB
    - Imported all changes to the PCB.
    - Added PCB outline and arranged all of the components.
    - Added labels and logos.
    - Added design constraints.
    - Added a single fiducial on the top side.
    - Routing completed.
    - DRC passes.
    - Added dimensions.
    - Added missing 3D models.
  - TODO
    - Complete the BoM.
    - Recheck the board design constraints.
    - Cleanup the fab layers.
    - Add board stackup table and characteristics. 
    - Add more GND vias.
    - Add CIRCUITSTATE logo and GitHub link.
    - Generate manufacturing files.
  - Initial commit.
  - Added Changes and Readme files.
  - New Revision 🆕 `R0.1`.
