Symbol and footprint libraries for KiCad. When importing a library, you should add `!` to the start of the nickname. For instance, `SGFootprints.pretty` should have the nickname `!SGFootprints`. Doing so makes it appear at the beginning of the list. All our symbols, footprints, and PCBs assume it will be this way, so it is required to ensure everything is correctly linked. Doing this will keep the links between symbols, footprints, and PCBs, so you don't need to resolve the missing dependencies manually.

| Library                                   | Type       | Systems    |
| ----------------------------------------- | ---------- | ---------- |
| [MiscFootprints.pretty](#miscfootprints)  | Footprint  | Misc       |
| [SGSymbols.kicad_sym](#sgsymbols)         | Symbol     | SEGA       |
| [SGFootprints.pretty](#sgfootprints)      | Footprint  | SEGA       |

Key
===
| Status        | Description                                                                                                       |
| ------------- | ----------------------------------------------------------------------------------------------------------------- |
| ✔️ Verified  | A PCB has been manufactured based on this symbol/footprint, and physical compatibility has been confirmed.          |
| ❌ Broken    | This symbol/footprint needs revisions and has been confirmed inaccurate.                                           |
| ❓ Untested   | No one has verified if this symbol/footprint works, so it probably doesn't.                                        |

MiscFootprints
==============
Footprints for graphics and various components.
| Footprint Name                           | Type           | License           | Comment                                                        | Status        |
| ---------------------------------------- | -------------- | ----------------- | -------------------------------------------------------------- | ------------- |
| FPC Connector - 45-pin - Multiple        | FPC Header     | Project           | 45-pin FPC connector; mainly for use with RetroSix's GG Slot.  | ✔️ Verified  |
| Graphic - OSHW Logo - Silk - Small       | Graphic        | CC-SA             |                                                                | ✔️ Verified  |
| Graphic - Starshade Logo - Mask - Small  | Graphic        | Proprietary       | Use without permission is prohibited.                          | ✔️ Verified  |
| Graphic - Starshade Logo - Silk - Small  | Graphic        | Proprietary       | Use without permission is prohibited.                          | ✔️ Verified  |

**Note**: Use of the Starshade logo without permission is prohibited. In addition, the Starshade logo must be removed from any PCB, even ones in this repository, if being used for commercial purposes (i.e. resale). See the README in the project root for details.

SGSymbols
=========
Unofficial symbols for SEGA systems.
| Symbol Name               | System         | Type              | Comment                      | Status        |
| ------------------------- | -------------- | ----------------- | ---------------------------- | ------------- |
| SG_GG_CARTRIDGE_FINGERS   | Game Gear      | Cartridge Fingers |                              | ❓ Untested   |
| SG_GG_CARTRIDGE_SLOT      | Game Gear      | Cartridge Slot    |                              | ✔️ Verified  |
| SG_GG_CARTRIDGE_SLOT_R6   | Game Gear      | Cartridge Slot    | FPC header for RetroSix slot | ✔️ Verified  |
| SG_SMS_CARTRIDGE_FINGERS  | Master System  | Cartridge Fingers |                              | ✔️ Verified  |
| SG_SMS_CARTRIDGE_SLOT     | Master System  | Cartridge Slot    |                              | ❓ Untested   |

SGFootprints
============
Unofficial footprints for SEGA systems.
| Footprint Name            | System         | Type              | Comment                      | Status        |
| ------------------------- | -------------- | ----------------- | ---------------------------- | ------------- |
| SG_GG_CARTRIDGE_FINGERS   | Game Gear      | Cartridge Fingers |                              | ❓ Untested   |
| SG_GG_CARTRIDGE_SLOT      | Game Gear      | Cartridge Slot    |                              | ✔️ Verified  |
| SG_GG_CARTRIDGE_SLOT_2H   | Game Gear      | Cartridge Slot    | 2-hole version               | ✔️ Verified  |
| SG_SMS_CARTRIDGE_FINGERS  | Master System  | Cartridge Fingers |                              | ✔️ Verified  |
| SG_SMS_CARTRIDGE_SLOT     | Master System  | Cartridge Slot    |                              | ❓ Untested   |

Disclaimers
===========
* SEGA and Game Gear are registered trademarks of SEGA CORPORATION (Japan). SEGA Master System is a trademark of Sega of America, Inc./SEGA CORPORATION (Japan). Neither affiliated with, nor authorized, sponsored, or approved by SEGA.
* RetroSix is a registered trademark of Luke Malpass (UK). Neither affiliated with, nor authorized, sponsored, or approved by RetroSix/Luke Malpass.
* Any other use of unowned trademarks is purely to demonstrate compatibility and is not meant to be taken as authorization, sponsorship, or affiliation.
