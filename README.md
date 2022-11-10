# Voron-0.1-4020-Zerofilter
A Zerofilter Mod for the Voron 0.1 with a 4020 blower.

![alt text](https://github.com/rajkumar-babu/Voron-0.1-4020-ZeroFilter/blob/6066546debe54b4b0afa53a18c9a37bf697b6ee0/Images/1.JPG)

This Mod uses a 4020 Blower fan instead of a 4010 to increase the airflow on the [zruncho's *Zerofilter*](https://github.com/zruncho3d/zerofilter) for the Voron 0.1. The aim is to use the cartridge for ABS printing and interchange it with a [Vez3D RSCS](https://github.com/VzBoT3D/VzBoT-Vz235/tree/main/Assemblies%20%26%20STL/RSCS) style duct for PLA printing. The inspiration was from the idea proposed by *Dingushippo#6564* on Discord to have interchangeable Cartridge and Airduct. The **Side Mount** used in this mod was inspired by [Revnull's *voron_v0.1_side_mount*](https://github.com/revnull-src/zerofilter/tree/main/Mods/revnull/voron_v0.1_side_mount).

![alt text](https://github.com/rajkumar-babu/Voron-0.1-4020-ZeroFilter/blob/6066546debe54b4b0afa53a18c9a37bf697b6ee0/Images/2.JPG)

# Parts to print
  * Core L ×1
  * Core R ×1
  * Lid L ×1
  * Lid R ×1
  * Side Mount L ×1
  * Side Mount R ×1

The parts are marked L and R for left and Right sides respectively and are properly oriented for printing.
  
# Print settings
  I followed the standard Voron print settings.
  * Material - ABS
  * 0.2mm layer height
  * 5 top and bottom layers
  * 4 perimeters
  * 40% infill
  * Forced 0.4mm width.

# BOM
  * Printed parts
  * 4020 Ball Bearing Blower Fans ×2
  * M3×6mm BHCS ×4
  * M3x8mm BHCS x4
  * M3×16mm BHCS x4
  * M3 Hex Nut ×4
  * M3 Heat Set Insert (M3×5mm×4mm) ×8
  * JST XH crimp terminals ×4
    * Or Microfit or JST PH or Ferrules as required for your setup.
  * JST XH 2 pin plug (Optional)
    * Can be reused from the fans.
  * 6mm×3mm Magnets ×8
    * Can get away with ×4 magnets as well.
  * Cartridge assembled and filled with carbon.
  
# Assembly Instructions

**STEP 1.**

Install the ×2 Heat Set Inserts on the inside of **Core** for mounting the fans. Be careful not to touch the narrow walls with the soldering iron. I used an LDO heatset installion tip and had enough clearance.

![alt text](https://github.com/rajkumar-babu/Voron-0.1-4020-ZeroFilter/blob/6066546debe54b4b0afa53a18c9a37bf697b6ee0/Images/3.JPG)

**STEP 2.**

Install the ×2 Heat Set Inserts on the inside of **Core** for mounting the **Side Mount**

![alt text](https://github.com/rajkumar-babu/Voron-0.1-4020-ZeroFilter/blob/6066546debe54b4b0afa53a18c9a37bf697b6ee0/Images/4.JPG)

**STEP 3.**

If your fan wires has a connector at the end remove the connector and snip the crimp terminals. Make sure you leave the wires as long as possible which aids in installation and can be trimmed later. This is essential to feed the wire through the channel.
Feed the wire through the slot on the inside of the **Core** and it should come out on the bottom.

![alt text](https://github.com/rajkumar-babu/Voron-0.1-4020-ZeroFilter/blob/6066546debe54b4b0afa53a18c9a37bf697b6ee0/Images/5.JPG)

**STEP 4.**

Gently Pull the fan wires out of the channel and guide the fans into the **Core** at the same time pushing it down. The fan orientation should not be an issue as it would go in all the way in only one direction. The channels are oversized and you shouldn't feel any resistance. If there is any resistance pull the wires slightly back and feed them again. The wires should sit flush to the top surface, not to interfere with the **Lid**

**STEP 5.**

Fasten the fan to the **Core** with x2 M3×16mm BHCS. Do not worry about the bolt heads sticking out. The **Lid** has enough clerance and would not hit or cause any binding as long as the bolts are ISO 7380-1. 

![alt text](https://github.com/rajkumar-babu/Voron-0.1-4020-ZeroFilter/blob/6066546debe54b4b0afa53a18c9a37bf697b6ee0/Images/6.JPG)

**STEP 6.**

Fasten the **Side Mount** to the **Core** using x2 M3×6mm BHCS.

![alt text](https://github.com/rajkumar-babu/Voron-0.1-4020-ZeroFilter/blob/6066546debe54b4b0afa53a18c9a37bf697b6ee0/Images/7.JPG)

**NEXT STEPS**

The next steps are
1. Install the magnets as per the [Zerofilter's guide](https://github.com/zruncho3d/zerofilter#assembly-instructions). Make sure the polarity matches with the corresponding Left and Right Cartridge.
2. Slide the **Lid**. The **Lid** is a remix of the [Zerofilter's Lid](https://github.com/zruncho3d/zerofilter#design-details) that attaches using a detent. There are notches at the bottom of the **Core** to remove the **Lid** if required. Take a note on the L and R markers on the **Lid** and intall it to their corresponding sides as they have intends to clear the rear M3 bolt heads.
3. Mark the length of wire required to connect the fan to the MCU or [Klipper Expander](https://github.com/VoronDesign/Voron-Hardware/tree/master/Klipper_Expander), cut to length, strip, crimp the terminals and plug them to your board. Follow [Zerofilter's Config](https://github.com/revnull-src/zerofilter#software-config) to setup the fans.
4. I used Revnull's [1515 Snap-in Mount](https://www.printables.com/model/163116-2-pin-jst-hx-1515-snap-in-mount) for the JST connectors inside the chamber for earier maintenance.

![alt text](https://github.com/rajkumar-babu/Voron-0.1-4020-ZeroFilter/blob/6066546debe54b4b0afa53a18c9a37bf697b6ee0/Images/8.JPG)

5. Mount the **Core** assembly to the frame as per [voron_v0.1_side_mount](https://github.com/revnull-src/zerofilter/tree/main/Mods/revnull/voron_v0.1_side_mount) or [Side Swipe](https://github.com/oldfar-t/Side-Swipe-Magnetic-Probe) or [Slide Swipe](https://github.com/chestwood96/SlideSwipe) instructions.
5. Attach the cartridge and start printing.

# What's next?

To design and test an [Vez3D RSCS](https://github.com/VzBoT3D/VzBoT-Vz235/tree/main/Assemblies%20%26%20STL/RSCS) style duct.
