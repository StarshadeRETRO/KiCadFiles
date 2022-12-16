Symbol and footprint libraries for KiCad. When importing a library, you should add `!` to the start of the nickname. For instance, `SGFootprints.pretty` should have the nickname `!SGFootprints`. Doing so makes it appear at the beginning of the list. All our symbols, footprints, and PCBs assume it will be this way, so it is required to ensure everything is correctly linked. Doing this will keep the links between symbols, footprints, and PCBs, so you don't need to resolve the missing dependencies manually.

| Library                               | Type       | Systems    |
| ------------------------------------- | ---------- | ---------- |
| [SGSymbols.kicad_sym](#sgsymbols)     | Symbol     | SEGA       |
| [SGFootprints.pretty](#sgfootprints)  | Footprint  | SEGA       |

Key
===
| Status        | Description                                                                                                       |
| ------------- | ----------------------------------------------------------------------------------------------------------------- |
| ✔️ Verified  | A PCB has been manufactured based on this symbol/footprint, and physical compatibility has been confirmed.          |
| ❌ Broken    | This symbol/footprint needs revisions and has been confirmed inaccurate.                                           |
| ❓ Untested   | No one has verified if this symbol/footprint works, so it probably doesn't.                                        |

SGSymbols
=========
Unofficial symbols for SEGA systems.
| Symbol Name               | System         | Type              | Status        |
| ------------------------- | -------------- | ----------------- | ------------- |
| SG_GG_CARTRIDGE_FINGERS   | Game Gear      | Cartridge Fingers | ❓ Untested   |
| SG_GG_CARTRIDGE_SLOT      | Game Gear      | Cartridge Slot    | ❓ Untested   |
| SG_SMS_CARTRIDGE_FINGERS  | Master System  | Cartridge Fingers | ❓ Untested   |
| SG_SMS_CARTRIDGE_SLOT     | Master System  | Cartridge Slot    | ❓ Untested   |

SGFootprints
============
Unofficial footprints for SEGA systems.
| Footprint Name            | System         | Type              | Status        |
| ------------------------- | -------------- | ----------------- | ------------- |
| SG_GG_CARTRIDGE_FINGERS   | Game Gear      | Cartridge Fingers | ❓ Untested   |
| SG_GG_CARTRIDGE_SLOT      | Game Gear      | Cartridge Slot    | ❓ Untested   |
| SG_SMS_CARTRIDGE_FINGERS  | Master System  | Cartridge Fingers | ❓ Untested   |
| SG_SMS_CARTRIDGE_SLOT     | Master System  | Cartridge Slot    | ❓ Untested   |

Disclaimer
==========
SEGA, Master System, and Game Gear are registered trademarks of SEGA GAMES CO., LTD. Not sponsored, endorsed, or approved by SEGA.
