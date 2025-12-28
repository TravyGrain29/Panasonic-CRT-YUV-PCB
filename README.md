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
Panasonic CRTs that utilise the GP3 chassis but lack component input, still have the basic foundations present that allow us to provide our own component input. This is due to Panasonic reusing the same chassis and processors between higher end and lower end models. All that was required for this mod was to unlock component input as an AV option via the service menu and then installing the missing hardware and connections.

## How To
### Step 1:
First you need to determine if your CRT is compatible with this mod. It needs to be a Panasonic CRT that uses the GP3 chassis. You can check your TV model by inspecting the back of the unit for a sticker with the model number and chassis type. If you find the model number but not the chassis type, search for your model number online and inspect any available service manuals or spec sheets. While inspecting the rear of the TV, take note of what inputs are available. If you already have component input then this mod is unnecessary for you. If your TV has SCART inputs, it may be incompatible with this mod and potentially unnecessary. SCART inputs most likely mean the TV has RGB support and if that is the case the IC most likely has different programming which prevents the ability to unlock component input via the service menu. RGB is also a very high quality input which should be used instead of this mod if it is offered natively. The perfect candidate of this mod is a Panasonic TV that uses the GP3 chassis and lacks native component or RGB inputs.
### Step 2:
