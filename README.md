# SDGecko-2.0
MicroSD Card Adapter For GameCube's Front Memcard Slots v2.0

Based on the SD2SP2 2.0 made by Extrems, Thank you for your hard work!

***Important Note about Old Gerbers/Worn out SD Card Issues***

Previous version of gerbers could cause 3v3 short to GND by some sus SD card models that have worn out edges exposing 3v3 plane to CD pin when inserted, this is fixed in new gerbers by making the SD card slot GND shield floating to prevent the issue regardless of the card being worn out.

One solution for old gerbers is to snip off the GND shield that the CD switch engages when a card is inserted to prevent old worn SD card edges from shorting to GND as shown in the image below.

<img width="598" height="557" alt="oldSlot solution" src="https://github.com/user-attachments/assets/04e8b78a-500f-41d3-8bf1-3794f4c9d381" />

**Important**

When using the adapter make sure to have the Latest Version of Swiss, Due to the way Swiss handles it in SLOT A it 
acts like a normal speed Passive SDGecko, in SLOT B it works in Semi-Passive 2.0 enhanced speed mode.

https://github.com/emukidid/swiss-gc


![pic2-min](https://github.com/silverstee1/SDGecko-2.0/assets/54997238/59c93b1c-e125-4f11-bd6a-de820ad7bec4)


![pic1-min](https://github.com/silverstee1/SDGecko-2.0/assets/54997238/1bf45114-eea7-4dab-b3b1-8283326eda77)



SDGecko+2.0 BOM
=====================================
The PCB must be ordered (e.g. from jlcpcb) in 1.6mm thickness with surface finish ENIG at minimum.

**3D Printed Case Enclosure**

You'll need to 3D print the case enclosure Top and Bottom pieces from the Case folder to use it in your Memcard Slot preferably on an FDM printer, 
the case screws are countersunk self tapping M2x5 screws.

**Note**

R1,R2,D1,D2 are not necessary if you don't want to have LED's in your adapter or want to minimize on components.

**SDGecko2.0+ PCB**

**C1:** 0402 22u Capactior (10V Min) - DigiKey Part# 490-GRM158R61A226ME15DCT-ND

LCSC Part# C3845593

**R1:** 0402 14ohm Resistor - Digikey Part# P14.0LCT-ND

LCSC Part# C400609

**R2:** 0402 14ohm Resistor - Digikey Part# P14.0LCT-ND

LCSC Part# C400609

**D1:** 0402 Green Led 20ma (Dot on PCB footprint marks LED Cathode side) - Digikey Part# 1516-1216-1-ND

LCSC Part# C2856703

**D2:** 0402 Blue Led 20ma (Dot on PCB footprint marks LED Cathode side) - Digikey Part# 1516-1215-1-ND

LCSC Part # C965797

**J4:** MicroSD Slot - DigiKey Part# 2223-MSD-4-ACT-ND

LCSC Part# C113206

**U1:** OR Gate IC - DigiKey Part# 296-1093-1-ND

LCSC Part# C7470

Alt Nexperia Digikey Part# 1727-3067-1-ND

LCSC Alt Nexperia Part# C12488
