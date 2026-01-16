# Panasonic-CRT-YUV-PCB
## DISCLAIMER
I'm not a professional, this was a side project I completed for fun. I cannot guarantee compatibility with your model CRT. I am not responsible for any damage or harm you may inflict upon yourself or your devices. Working on CRTs is very dangerous and should only be done by individuals with the required knowledge and experience. Do not attempt this project if you are a novice with electronics or CRTs.

## Overview

### CRT Specs
Model: Panasonic Tau TC-21PM50A

Chassis: GP3

UOC IC/Jungle: TDA9590N48AX

### What is this?
This is a PCB I designed, based off exisiting Panasonic schematics, that allows Panasonic Tau CRTs using the GP3 chassis to accept component (YPbPr) video input. This is intended for use with GP3 CRTs that lack native component or RGB inputs. The board converts incoming YPbPr signals from an external device into sigals that the video processor can understand and display properly. Without this PCB, the video will not display correctly and will appear distorted.

### How does it work?
Panasonic CRTs that utilise the GP3 chassis but lack component input, still have the basic foundations present that allow us to provide our own component input. This is due to Panasonic reusing the same chassis and processors between higher end and lower end models. All that was required for this mod was to unlock component input as an AV option via the service menu and then installing the missing hardware and connections. This board replaces the missing YUV circuit board that came with component enabled models, allowing us to build the YUV input path ourselves.

### How can I build this?
A written guide will be provided in PDF format with instructions on how to perform the modification.
