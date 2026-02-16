# CD32 to The A500 Gamepad

This is a replacement PCB for The A500 gamepad making it a true CD32 pad.

Based on Commodore CD32 gamepad schematics.

YouTube video on the design, assembly and testing of this project can be viewed here - https://youtu.be/vLGpuEnnuxA



## Assembly

Within the JLCPCB folder you will find Gerbers along with a BOM and CPL files suited to LSSC components.

I recommend having the board produced with the EINT finish and get JLC to do all SMD work as its 0402 and very fiddly.

You must fit the through hole capacitor yourself (47uF 2mm pin spacing 5mm diameter) as it needs to be folded over onto the PCB.

For the shoulder button switches, you can just take them off the original PCB or the part numbers are below.

You will obviously need a new wire, I'd recommend a simple DB9 extension cable and cut the end off.  The holes labelled 1-9
on the PCB correspond to pins 1-9  on the DB9.  This is at 1.27mm pitch so be careful not to bridge anything!



## Bill of Materials

U1  - 74LS165        - SOIC16

U2  - 74LS125        - SOIC14

R1  - 220ohm 1%      - 0402

R10 - 10k ohm 1%     - 0402

R11 - 10k ohm 1%     - 0402

R15 - 100ohm 1%      - 0402

RP1 - 10k 1%         - 4x0402

RP2 - 10k 1%         - 4x0402

C1  - 100pF          - 0402 ceramic

C2  - 47uF           - 2mm lead spacing 5mm diameter (remember to fold this over)

C3  - 1000pF         - 0402 ceramic

C4  - 0.1uF          - 0402 ceramic

C5  - 0.1uF          - 0402 ceramic

FB1 - 1kohm @ 100MHz - 0402

SW9 - PTS645Vx39-2LFS- Tactile SPST Angled Switch (or take this off the old PCB)

SW10- PTS645Vx39-2LFS- Tactile SPST Angled Switch (or take this off the old PCB)



## License

CERN Open Hardware Licence v2

Do with as you like just don't blame me if your Amiga goes up in smoke!

