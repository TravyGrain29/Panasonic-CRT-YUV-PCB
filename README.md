# Panasonic-CRT-YUV-PCB
## DISCLAIMER
I'm not a professional, this was a side project I completed for fun. I am not responsible for any damage or harm you may inflict upon yourself or your devices. Working on CRTs is very dangerous and should only be done by individuals with the required knowledge and experience. Do not attempt this project if you are a novice with electronics or CRTs.

## CRT Specs
Model: Panasonic Tau TC-21PM50A

Chassis: GP3

UOC IC/Jungle: TDA9590N48AX

## What is this?
This is a PCB I designed, based off exisiting Panasonic schematics, that allows Panasonic Tau CRTs using the GP3 chassis to accept component (YPbPr) video input. This is intended for use with GP3 CRTs that lack native component or RGB inputs. The board converts incoming YPbPr signals from an external device into sigals that the video processor can understand and display properly. Without this PCB, the video will not display correctly and will appear distorted.

## How does it work?
Panasonic CRTs that utilise the GP3 chassis but lack component input, still have the basic foundations present that allow us to provide our own component input. This is due to Panasonic reusing the same chassis and processors between higher end and lower end models. All that was required for this mod was to unlock component input as an AV option via the service menu and then installing the missing hardware and connections.

Originally the TV was only capable of accepting composite and RF inputs but upon inspecting the service manual, I discovered the IC had pins dedicated to RGB and YUV inputs.
After some tinkering in the service menu I was able to unlock component as an option in the AV input selector. I achieved this by changing the values of Option 5 from 00 to 01.
I then hooked up some RCA jacks to the YUV pads on the IC but found the colours wouldn't display properly. After some more research I found out the IC requires a seperate YUV circuit board to convert the YPbPr signals to Y -B-Y -R-Y.
I managed to find a schematic and part list for the circuit in the service manual of a different model CRT that shared the same chassis and IC as mine but also had component input.
I copied the schematic in Kicad with some minor changes and designed a PCB. I then searched for the parts I needed on Mouser, I opted to find superior modern alternatives rather than the original parts when creating my part list.
Then I put the YUV PCb together and connected shielded wires to the YUV pads and ground on the chassis.
After installation, the TV now properly displays component video.
