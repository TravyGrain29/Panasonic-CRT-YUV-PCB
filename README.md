# Panasonic-CRT-YUV-PCB
Disclaimer: I'm not a professional, this was a side project I completed for fun. Feel free to make any adjustment and improvements.

CRT Model: Panasonic TC-21PM50A

Chassis: GP3

UOC IC/Jungle: TDA9590N48AX

This is a PCB I designed to allow my Panasonic Tau CRT to accept component (YPbPr) input.

It converts the incoming YPbPr signal into Y -B-Y -R-Y so that it can be accepted by the IC.

Originally the TV was only capable of accepting composite and RF inputs but upon inspecting the service manual, I discovered the IC had pins dedicated to RGB and YUV inputs.
After some tinkering in the service menu I was able to unlock component as an option in the AV input selector. I achieved this by changing the values of Option 5 from 00 to 01.
I then hooked up some RCA jacks to the YUV pads on the IC but found the colours wouldn't display properly. After some more research I found out the IC requires a seperate YUV circuit board to convert the YPbPr signals to Y -B-Y -R-Y.
I managed to find a schematic and part list for the circuit in the service manual of a different model CRT that shared the same chassis and IC as mine but also had component input.
I copied the schematic in Kicad with some minor changes and designed a PCB. I then searched for the parts I needed on Mouser, I opted to find superior modern alternatives rather than the original parts when creating my part list.
Then I put the YUV PCb together and connected shielded wires to the YUV pads and ground on the chassis.
After installation, the TV now properly displays component video.
