# Richard's R36SX
## HOS 1.2 [PCB: R36S-V3.0 (2026.07.20)]

This is my notes for an R36S-style portable game console identified as the **R36SX**, with a **GB350-style clone** design. It's a FAKE R36S =), but I love it! 
Despite it's hardware limitations, the community around it is awesome! Everyday, new findings.

This repository documents my board layout R36S-V3.0 (2026.07.20). It is not an official product or firmware repository.

## Device information

| Item | Details |
|---|---|
| Device | R36SX |
| Design description | R36S-style portable console; GB350-style clone |
| Processor | MIPS, as reported for this unit |
| Stock operating system | HOS v1.2 |
| PCB marking/version | `R36S-V3.0 (2026.07.20)` |
| Repository | `my-R36SX-HOS-V3.0` |

## PCB overview

The attached photo shows the handheld’s main PCB with the enclosure opened. Visible features include:

- A large square main IC near the upper portion of the board, likely the main processor/SoC. Its top marking is not legible in the photo, so the exact part number and package cannot be confirmed here.
- A USB-C receptacle at the top edge of the PCB.
- A wide FPC connector near the center, likely for the display assembly.
- Two metal card-slot assemblies near the lower left and lower right. Their exact functions and card compatibility should be confirmed from the device or board documentation.
- A connector marked `SPK`, indicating the speaker connection.
- Red and black wires routed along the left side, likely part of the battery or power wiring; their function should be verified before probing or disconnecting.
- Numerous small surface-mount components around the processor and connectors, including passive components and likely power-management circuitry.

The photo is useful for identifying component placement, but it does not show readable chip markings, PCB traces on the reverse side, or enough detail to determine the exact memory, power-management, or storage components.

## Hardware identification notes

The processor is reported as MIPS, but the exact SoC is not confirmed from the image. Do not infer a specific chip model from the package appearance alone. To identify it, record the full marking printed on the IC and cross-check it against the board revision.

Likewise, the two card slots should not be assigned functions based only on their appearance. Check the device’s behavior, slot labels, or verified board documentation before documenting them as system-storage or game-card slots.

## Stock software

The unit is reported to run **HOS v1.2** as its stock operating system. This repository currently records that version as device information; it does not include firmware files or claim compatibility with other R36S-family hardware.

Before attempting firmware changes, verify the exact PCB revision and make a backup of the original storage media. Firmware intended for a visually similar console may not be compatible.

## Documentation status

- [x] Device name and reported platform details recorded
- [x] Visible board features noted from the attached photo
- [ ] Main SoC model confirmed from chip marking
- [ ] Card-slot functions confirmed
- [ ] PCB reverse side documented
- [ ] HOS v1.2 build details and backup procedure documented

## Disclaimer

This is an independent documentation project. Product names and model descriptions are used to identify the device being documented. No manufacturer affiliation is implied.
