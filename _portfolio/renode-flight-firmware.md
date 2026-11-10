---
title: "Flight-Control Firmware Simulation in Renode"
excerpt: "Emulated a nano-quadcopter's firmware on an STM32F405 target during a research traineeship at GTRE, DRDO."
collection: portfolio
date: 2026-09-01
---

Completed during my research traineeship at the Gas Turbine Research Establishment (GTRE), DRDO (Aug-Sep 2026).

I emulated the flight-control firmware of a Crazyflie nano-quadcopter in **Renode**, an open-source hardware emulator, running against its target **STM32F405** chip.

**Stack:** C, C#, C++, Crazyflie, Renode

**Highlights**
- Built a **keyboard-control bridge** that forwards keypresses to a custom Renode peripheral, standing in for the drone's radio input link.
- Lets the firmware be exercised and controlled without physical hardware.

[Code](URL)
