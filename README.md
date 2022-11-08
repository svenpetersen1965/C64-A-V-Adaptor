# C64-A-V-Adaptor
An A/V-adaptor board for the C64
This board is intended to connect to the Commodore C64 and use standard cables (audio, composite with RCA connector and/or s-video with a mini-DIN cable).

It also provides a 330Ohm resistor, which attenuates the s-video chroma line. This resistor can be bridged with a jumper. 

Also an optional stereo output on pin 7 of the a/v jack (stereo sid, FPGA SID etc.) can be connected to the right audio channel. By default, this channel is also connected to the (mono) audio output.

<img src="https://github.com/svenpetersen1965/C64-A-V-Adaptor/blob/master/Rev.%200/pictures/2810_AV-adaptor_breadbin.JPG" width="300" alt="C64 A/V-Adaptor">

<img src="https://github.com/svenpetersen1965/C64-A-V-Adaptor/blob/master/Rev.%200/pictures/2811_-_av-adaptor_bottom.JPG" width="300" alt="C64 A/V-Adaptor (bottom)">

<img src="https://github.com/svenpetersen1965/C64-A-V-Adaptor/blob/master/Rev.%200/pictures/2823_-_side_view_with_cables.JPG" width="300" alt="C64 A/V-Adaptor (side view with cables)">

There is another source of the Lumberg DIN connector found for north America: https://www.alliedelec.com/product/lumberg/sv-80/70151558/ 

# Case

I have added a 3D printable case for this adaptor.

<img src="https://github.com/svenpetersen1965/C64-A-V-Adaptor/blob/master/case/Rev.%200/pictures/AV%20adaptor%20case%20explosion.png" width="300" alt="C64 A/V-Adaptor Case">

<img src="https://github.com/svenpetersen1965/C64-A-V-Adaptor/blob/master/case/Rev.%200/pictures/2864_-_Adaptor_with_C64_front.JPG" width="300" alt="C64 A/V-Adaptor Case">

<img src="https://github.com/svenpetersen1965/C64-A-V-Adaptor/blob/master/case/Rev.%200/pictures/AV-Adaptor_case%20v15.png" width="300" alt="C64 A/V-Adaptor Case">

# Revision 1
Rev. 1 is exactly the same as Rev. 0, except the spacer, that had to be cut off manually was removed to myke this board a little more mass production friendly. All masures and positions stayed the same. The BOM has not been changed, either (except the PCB Rev. No.).

# Revision 2
In Rev. 2, the obsolete Lumberg BTOR1 RCA jacks are replaced with a model from CUI Inc. Also, there is an alternative from Keystone. Check ou the BOM.

# Prices

I have added a price calculation with prices of May 2020. The  prices per item were retrieved from reichelt.de. They might differ from distributor to distributor (the Lumberg connectors are more expensive in North America) and they don't include any shipping fees.

A standard A/V Adaptor is worth 12,75€ (May 2020) plus the 3D printed case and label.

In September 2022, a new price had to be calculated. The BOM Value is now (Sepüt. 2nd, 2022) 16.63€. 

# VIC-20 & C128

This AV-Adaptor is blocking the Expansion Port of the VIC-20 (the 5 pin version) and the IEC bus of the C128! There are dedicated versions for each.

* <a href="https://github.com/svenpetersen1965/C128-A-V-Adapter">C128 A/V-Adapter</a>
* <a href="https://github.com/svenpetersen1965/VIC-20_AV-Adapter">VIC-20 A/V-Adapter</a>


