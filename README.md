# PSX_ENGINE

A collection of low-level rendering experiments on the original PlayStation, built using the official **Psy-Q SDK**.

> Note: despite the repo name, this isn't a reusable engine — it's a set of standalone experiments exploring fixed-function, hardware-constrained graphics programming on real retro console hardware.

## Experiments
- Text/font rendering on screen
- 3D cube rendering
- 2D geometry primitives

## Structure
Includes both a **C** and a **C++** version (`C/` and `CPP/` folders), each with its own build script (`C.BAT`, `CPP.BAT`).

## Tech
- **Platform:** Sony PlayStation (PSX)
- **SDK:** Psy-Q
- **Languages:** C, C++

## Why
Understanding the PSX's rendering pipeline and hardware constraints from the ground up, without any modern abstraction layer.
