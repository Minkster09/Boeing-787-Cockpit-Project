# Boeing 787 Cockpit Project

I worked on this project across Grades 10 and 11. I wanted to build physical Boeing 787 cockpit controls that could actually interact with Microsoft Flight Simulator, and it gradually grew into more than 20 individual panels with over 200 controls and components.

The panel faceplates were sourced, but I installed and wired the electronics myself. That included switches, buttons, rotary encoders, potentiometers, LEDs, displays, and other controls. I also drilled, cut, painted, soldered, glued, repaired, and reworked parts as the build changed.

For the electronics, I planned the wiring in Microsoft Visio and used multiplexers to connect large numbers of inputs to Arduino boards. The Arduinos then connected to the computer, where I used MobiFlight to link the physical controls to Microsoft Flight Simulator.

The software side took more work than I expected. Many 787 controls did not have ready-made mappings, so I used the simulator's developer tools to work out which internal variables controlled different functions and then configured the inputs and outputs myself.

One example was the APU switch. The physical three-position switch, OFF / ON / START, was being detected correctly by MobiFlight, but the aircraft in the simulator was not behaving consistently. I initially thought I had wired it incorrectly. After checking the hardware, I eventually found that the problem was the simulator variable I was using rather than the switch itself.

I finished the individual cockpit panels, but never built the full cockpit shell. My family moved from a larger house in the UAE to a smaller one, and there was no longer enough room to assemble the complete cockpit, so the panels went into storage.

This repository was created later to preserve the photos, wiring diagrams, and other files I kept from the project.

## Project summary

- 20+ Boeing 787 cockpit panels
- 200+ physical controls and components
- Arduino-based input/output system
- Multiplexer wiring planned in Microsoft Visio
- Microsoft Flight Simulator integration through MobiFlight
- Custom mapping of simulator inputs and outputs
- Hands-on assembly, soldering, drilling, painting, wiring, and repairs

## Files

This repository contains the surviving photos, wiring diagrams, and other project files I kept from the build.
