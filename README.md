# BackSlash-BS3

BackSlash-BS3 is a 16-bit CISC CPU ecosystem project covering the architecture specification, toolchain, emulator, and validation workflow.

## Project Scope
This repository tracks complete development of the BackSlash-BS3 platform from specification through implementation and end-to-end testing.

## Core Objectives
1. Define and document the BackSlash-BS3 ISA (16-bit CISC architecture)
2. Implement an assembler for BackSlash-BS3 binary generation
3. Develop a C compiler targeting BackSlash-BS3
4. Build a full-featured emulator with:
   - Complete CPU instruction execution
   - Advanced video/GFX subsystem (256x256 surfaces, tiles, sprites, layers, palette management)
   - Integrated debugger (step execution, breakpoints, register inspection/modification)
   - Disassembler for loaded binaries
5. Perform end-to-end integration testing with sample programs

## Key Reference Documents
- [BackSlashThree.txt](https://github.com/redcrab2016/BackSlash-BS3/blob/main/BackSlashThree/BackSlashThree.txt) — ISA specification, registers, memory map, instruction set (225 instructions)
- [BackSlashThree_GFX.txt](https://github.com/redcrab2016/BackSlash-BS3/blob/main/BackSlashThree/BackSlashThree_GFX.txt) — video hardware, graphics commands, sprite/tilemap system

## Workstreams / Sub-Issues
- [ ] ISA Design & Documentation
- [ ] Assembler Implementation
- [ ] C Compiler Toolchain
- [ ] Emulator (CPU + GFX + Debugger)
- [ ] Integration & Testing

## Current Status
Project initialization phase. All components must strictly adhere to the specifications in the reference documents.
