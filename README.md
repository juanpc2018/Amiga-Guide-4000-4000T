# Amiga Guide 4000D / 4000T

"from Zero to Hero" </br>

**v0.00000001** </br>

This is a compilation / combined knowledge of many websites, </br>
Condensed as much as possible, "for Beginners". </br>

## Background History

[Amiga 4000 (1992-1994)](https://en.wikipedia.org/wiki/Amiga_4000) "Desktop" & Tower [A4000T (1994-1996)](https://en.wikipedia.org/wiki/Amiga_4000T) </br>
were the last & best Amiga made around Motorola 68K 030 040 CPU's, </br>
has optional 3rd party accelerator boards that allow CPU upgrades </br>
there are different kinds of CPU upgrades: ARM "Bare Metal SW Emulation", FPGA, & Real Motorola 68060 CPU's </br> 
Amiga 500/1000 were much more common = most games were designed for Kickstart 1.3 ROM & 68000 CPU. </br>

There were changes over the years to accomodate New technologies "better graphics like AGA custom chips"  </br>
Motorola also did changes to the CPU's 68k 020 030 040 060 to increase speed, less common instructions were removed. </br>
architectures were combined in 040 = 030 + [68882](https://en.wikipedia.org/wiki/Motorola_68881) FPU, </br>
060 was redesigned for [SuperScalar](https://en.wikipedia.org/wiki/Superscalar_processor) architecture, like SGI RISC CPUs </br>
with dual pipelines "Pseudo-Parallelism / Early Pre-Dual Core Era" </br>
transistor technology was improved with every revision </br>
many improvements were made But... 100% backward compatibility was lost. </br> 
some SW designed for Kickstart ROM v1.3 and 68K 000 CPU's  </br>
behave weird issues, or don't work at all on newer A4000 / A1200 with AGA & 060... </br> 
in 1993 a software called ReloKick [v1.41](https://archive.org/details/ReloKick_v1.41_1994_Geesus) & [1.4a](https://archive.org/details/ReloKick_v1.4a_1994_DCS) </br>
was made to create a soft-compatibility layer: </br>
Emulate Kickstart 1.3 ROM in RAM on Newer [Kickstart](https://en.wikipedia.org/wiki/Kickstart_(Amiga)) </br>
SW came with [CU Amiga Magazine issue 037 - March 1993](https://archive.org/details/cuamiga-magazine-037/page/n11/mode/2up) </br>
Requires minimum 1MB of FAST RAM, Today thats Not a problem, most CPU accelerator boards have plenty of Fast RAM. </br>
The SW is Not available on [aminet website](https://aminet.net/) "Amiga AppStore / Pre-PPA Repository" </br>

Amiga 4000 is Pre-TCP/IP era, pre-SSL era </br>
there are several Ehternet 100Mbps cards available for Zorro slots. </br>
but requires several software to connect to internet and websites like: Aminet website directly. </br>
like iBrowser has CPU SSL emulation layer </br>
Newer latest generation CPU Accelerator boards some have HW SSL decoder like A3660 + FPGA Accelerator board. </br>
New ZZ9000 GPU with updated firmware also has planned SSL HW Accelerator / Decoder. </br>

to trasfer files from FreeDOS / MS-DOS "FAT16/32" to Amiga FastFileSystem "FFS" </br>
AmigaOS has an emulator SW, does Not start at boot by default </br>
The other ways "writing Amiga 880k floppy directly on Mac/PC/Linux" has different options:  </br>
HW [KryoFlux Floppy emulator](https://kryoflux.com/?page=kf_features) </br>
SW [Amiga Explorer](https://www.amigaforever.com/ae/) machine-to-machine communication using serial port, or USB Bluetooth (RS-232) adapters. </br>
Gotek USB Floppy Emulators "STM32" with optional HxC Firmware &/or Flash Floppy Firmware </br>
WinUAE, FS-UAE, E-UAE "Linux" </br>

the Amiga 1200 is "the same" AGA Graphics custom chip like 4000 in a compact format, </br>
like Atari Falcon 030 vs Mega or TT030 </br>

Amiga has a software that allow to run macOS8.1 designed for Motorola 68K CPU </br>
"The fastest Mac is an Amiga" </br>
both Amiga & Apple had UnixOS A/UX & AMIX </br>
some claim that Classic Macs were locked in ROM Bios so it cannot be upgraded to 060 CPU's </br>
because Mac was moving to PPC, did Not wanted a Fair comptetition. </br>

Early 4000D "Desktop" all had battery leak that damaged the boards </br>
A4000-CR "Cost-Reduced" verson (1993-1994) battery was replaced with coin battery. </br>
several Amiga enthusiasts repaired the "survivors" from land fills & recycling centers </br>
4000D (1992-1994) has differet board revisions "was a work in progress" </br>
some repairs were not feasible "too much damage", thats how Recreation Boards were born. </br>

A4000"T" Tower has a different coin battery, there is only 1 Rev4 board,  </br>
has built-in SCSI-2 NEC 53C710 controller. </br>
A4000"D" has many optional Card upgrades like SCSI-2 Axxx </br> 
schematics were reverse eng. and recreation boards were made.  </br>

Amiga 4000 series D/T have Zorro-3 Slots "faster" </br>
AGA video chipset </br>
All Amigas come with a "basic" GPU, that requires special 15KHz monitor,  </br>
rare DB23 connector / adapter to VGA </br>
The A/T had standard AT Power supply "low efficiency 68%"  </br>
The "D" had a different custom PSU, with different connectors. </br>

many Amiga store websites sell most parts for DIY or pre-built adapters. </br>

A3000 & A2000 have a similar story, but more advanced,  </br>
because boards were more "available", easy to find,  </br>
some recreated failing custom chips in fpga "drop in replacements"  </br>

When Apple transitioned to PPC, some Amiga developers also created Dual CPU accelerator boards </br>
like Cyberstorm Mk3 060 & PPC 603e or 604e </br>
AmigaOS4 was recompiled for PPC architecture, </br>
and Newer Amiga X1000 X5000 for PPC were launched </br>
Those PPC had a CPU similar to PowerMac G5 "64-Bit" Single/Dual-Core versions </br>
but the CPU they chosed does Not have Altivec "MMX instructions" </br>
There are Modern PPC Cpus today for embedded systems that contain Altivec "Newer" generations </br>
That was a major design flaw in my opinion. </br>

## GPU's
Older GPus like PicassoIV v1.2 and other similar like [Piccolo SD64](https://www.youtube.com/watch?v=bqqmQgWlQX0) </br>
based on CirrusLogic IC "VGA" and custom FPGA </br>
are failing due to age... </br> but were very desired because didnt had the 15KHz limitation, allows "modern" SVGA/XGA CRT's. </br>
New GPU's like MNT [ZZ9000](https://www.youtube.com/watch?v=NTnixC5ym-o) latest Rev. take Amiga to a New level. </br>
some PCI upgrade Riser cards like Mediator allow installing Voodoo PCI cards + Warp3D drivers. </br>

## 68K Alternatives: 
Minimig is a hybrid FPGA custom chip emulation board, with socket for Real 68K CPU &/or compatible accelerator boards. </br>
MIST made by Lohratec in Poland "complete custom FPGA emulator" </br>
MISTer complete FPGA emulator baseded on Terasic De-10 Nano dev board </br>
Apollo Vampire V4 has custom 080 FPGA accelerator boards "060 compatible" </br>
stand alone complete FPGA emulator: small portable & A6000 similasr to Amiga 600/1200 "All-In-One keyboard" format, and some PiKeyboard versions </br>

## SOFTWARE
There are many ABANDONEARE software titles "TOSEC" </br>
there is also New developers like [Geezer games](https://mcgeezer.itch.io/) </br>
if you search youtube New Games in 2020 / 2021 / [2022](https://www.youtube.com/watch?v=KK9zg2Vh7AI) for Amiga, there are several [youtube channels](https://www.youtube.com/@retrogamingdino) with links to the developers. </br>
Some developers improve older games with AGA graphics, unlocked FPS, taking advantage of CPU accelerator boards & More FastRAM </br>
others Port old Arcade ROM games to Amiga </br>
others create Open Source OS like CaffeineOS, AROS, T2-Linux, etc... </br>

## DIY
If you buy a Replica board from one of the many Amiga sellers / stores, </br>
to replace the old damaged board "transplant components" or to create a New machine. </br>

### Create a New HW machine or use Software Emulators: </br>

Requires purchasing Legal Kickstart ROM images from 1.3 to 3.1 from [AmigaForever Plus .iso](https://www.amigaforever.com/plus/) "Cloanto" </br>
ROMs 3.X with CAPITAL X, is "10" 3.10 ROM but that was an early jump. </br>
Later Hyperion created ROMs 3.1.4 in (2018) </br>
Roms 3.2 in 2020 as Physical Purchase <br>
ROMs 3.2.x as [Digital Download](https://www.hyperion-entertainment.com/index.php/where-to-buy/direct-downloads/327-amigaos-32) in (2026) </br>

IF you buy the Digital Downloads, and you are making a New machine, </br>
you need prepare the ROMs before Burning with a TL866-II or similar T48 Eprom Programmer </br>
Compatilble ROMs UV Eresable Am27C400 or similar faster  than <200ns access time. </br>
you need to Change from Little.Endian to Big.Endian "Swap the Bytes Order" </br>
and Splt the ROM image from the Digital Download to fit 2x EPROMS </br>
also you need a Zif-Socket adapter board, because TL866-II / T48 Eproms only have 40-pins, </br>

1. AmigaForvere 3.1 ROMs
2. Hyperion 3.2 ROMs
3. prepare Roms "Swap & Split" Non needed using UAE Emulators.
4. buy or diy a Zif-socket adapter for TL866-ii / T48 "more than 40-pins"
5. Buy 2 Roms. "if making a New machine"
6. Burn 2 Roms with TL866-II / T48 or similar Eprom Programmer.

Alternate: if UV Ereasable ROMs are "Hard to Find" or Expensive </br>
there is also the Project [OneROM](https://onerom.org/) that Emulate EPROMs based on STM32 "more than 40-pins Required" </br>

UV Ereseable Roms do Not Erase with LED UV-A flashlights </br>
Some Chinese sellers have a Proper UV-Eraser Plastic Box, IF buy USED UV Eproms </br>
UV Ereasable Eproms are designed to last much more than Flash memory, does Not have the problem of "Write Times" nor "Temperature" </br>

The Proper UV-Eraser Box contains a 6" Pure Quartz vacuum tube "like CFL lamps" with 2 or 3 Mercury 3mm BallBearings's inside. </br>
High Voltage "120v" Evaporate Mercury, Mercury Glow like Neon signs, generates a 200nm Peak UV-C, </br>
Human Eyes cannot see 200nm, but also generates Harmonics / Resonances around 450nm "Cyan Blue" Visible range, </br>
Requires only a Few minutes. </br>
Using the Sun requires much more time becasue Ozone Layer Blocks UV-C </br>
cannot be Erased indors because Normal Glass Blocks UV-C </br>

## IDE vs. SCSI-2

Mechanical IDE or SCSI HDD's are most gone / damaged, but.. </br>
but there are CompactFlash CF to IDE adapters and to SCSI-2,
RaSCSIm ZuluSCSI, XT-IDE, </br>
there is also SSD SATA to IDE and SATA to SCSI-2 adapters </br>

i have an "Acme" SATA SSD-to->IDE adapter, Generic IC, </br>
Startech sell similar with Marvell IC </br>
The generic adapter, maximum speed on a modern Computer is 100MB/s ATA100
i could Not reach 133MB/s using a [891U3](https://www.youtube.com/watch?v=NKpzkbOS59Y) USB3.0 to IDE "Generic" adapter, [Startech USB3SSATAIDE version](https://www.startech.com/en-us/hdd/usb3ssataide) </br>
P.D. Do Not use the 891U3 included Power Supply has +6vdc some equipment will burn, </br>
older Blue version USB2.0 to IDE had closer to +5.2vdc PSU </br>
Moderm Boards dont have IDE, but there are PCI IDE cards available, </br>
and PCI to PCIe adapters, also with different IC controllers. </br>
