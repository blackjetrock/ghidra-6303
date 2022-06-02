# ghidra-6303
Ghidra 6303 support and 6303 projects
=====================================

There is support for the 6303 processor (as used in Psion organisers as well as other devices) in this repository. Put the 6303 directory into your Ghidra Processors directory and the 6303 support should appear when setting up a new project. The 'extra' 6303 instructions appear in the disassembly but I haven't added the procedural part so no decompilation will appear.

Psion Organiser
===============

The reason for doing this was to get a disassembly of Psion Organiser code going. There is a Ghidra project here that is a start of the work to disassemble Psion organiser things, starting with the 33-LA ROM. I started with this ROM as it doesn't have bank switching so is an easier ROM to start on.

Flash driver
============

It would also be usedful to have some idea of what the flash driver does, so the V1.9 driver OPK is also here.



