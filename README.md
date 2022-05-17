# Keybert
Copyright Travis W Rigg

This source describes Open Hardware and is licensed under the CERN-OHL-P
v2

You may redistribute and modify this documentation and make products
using it under the terms of the CERN-OHL-P v2 (https:/cern.ch/cern-ohl).
This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED
WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY
AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-P v2
for applicable conditions

## The keeb!
Keybert is an ortholinear split keyboard that is intended to be as inexpensive
as possible when built by ordering everything from scratch (including ordering
the PCBs from a PCB vendor that does custom orders). Keybert is also very basic.
The idea behind that was to keep things as simple as possible for the target
audience. Someday in the future, there may be a more feature rich version of
Keybert with all of the fancy things that make "endgame" keyboards "endgame."
But for now, you can get the full fat version of Keybert for not all that much
money (in the world of custom mechanical keyboards) and without needing to be a
wizard at soldering.

With all of that in mind, there are also some other decisions that have been
made to make Keybert a better keyboard for this target audience. Specifically,
there are absolutely no components with overlapping footprints like what you'd
see on some of the keyboards that Keybert was inspired by (in particular the
Let's Split by wootapoot).

An overall listing of features reads as follows:

1. A PCB that can also act as a bottom caseplate
2. Reversible PCB for cost savings when ordering boards
3. All diodes set outside of key matrix
4. Pro Micro set outside of key matrix
5. I2C (I still have no idea what this actually wins you, but it costs all of 2
   resisters so why exclude it from the schematic!?)
6. PCB designed with tenting in mind

## The Roadmap
There are some milestones that Keybert needs to acheive, as well as some pie in
the sky type dreams that might never be acheived, but hey, they'd be nice

Milestones:
1. ~~Compile all CERN OSH recommended documents (gerbers and PDFs)~~
2. Simplify PCB using
  [the aisler PCB design rules](https://aisler.community/t/pcb-design-rules/41)
2. Design switch plate
3. Perform basic cost estimate
4. Identify and resolve value shortcomings
5. Order all parts
6. Test build difficulty
7. Identify issues with prototype
8. User acceptance testing
9. Acheive inner peace, never to look at the mechanical keyboard community ever
   again, thus finally escaping the endless hamster wheel that is... "endgame"

Unreasonable dreams:
* Make use of all pins on the Elite C
* Alternative version using BlackPill microcontroller
* Alps compatibility
* Kailh Choc version
* 3D printed case CAD models
* A group buy (to bring prices down further than their already low target)
* Regular commercial availability (for even cheaper keyboards)