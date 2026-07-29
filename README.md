# Amiga Guide 4000D / 4000T

"from Zero to Hero" </br>

**v0.00000001** </br>

This is a compilation / combined knowledge of many websites, </br>
Condensed as much as possible, "for Beginners". </br>

Amiga 4000 were the last & best Amiga made for Motorola 68K CPU's, </br>
has optional 3rd party accelerator boards that allow CPU upgrades </br>
there are different kinds of CPU upgrades: ARM "Bare Metal SW Emulation", FPGA, & Real Motorola 68060 CPU's </br> 
Amiga 500/1000 were much more common = most games were designed for Kickstart 1.3 ROM & 680000 CPU. </br>

There were changes over the years to accomodate New technologies "better graphics like AGA custom chips"  </br>
Motorola also did changes to the CPU's 68k 020 030 040 060 to increase speed, less common instructions were removed. </br>
architectures were combined in 040 = 030 + 68882 FPU, </br>
060 was converted to SuperScalar architecture, like SGI RISC CPUs </br>
with dual pipelines "Pseudo-Parallelism / Early Pre-Dual Core Era" </br>
transistor technology was improved with every revision </br>
many improvements were made But... 100% backward compatibility was lost. </br> 
some Software designed for Kickstart ROM v1.3 and 68K000 CPU's  </br>
behave weird, or dont work at all on newer A4000 with AGA 040 etc... </br> 
in 1993 a software called ReloKick [v1.41](https://archive.org/details/ReloKick_v1.41_1994_Geesus) & [1.4a](https://archive.org/details/ReloKick_v1.4a_1994_DCS) </br>
was made to create a soft-compatibility layer: </br>
Emulate Kickstart 1.3 ROM in RAM on Newer [Kickstart](https://en.wikipedia.org/wiki/Kickstart_(Amiga)) </br>
SW came Free on [CU Amiga Magazine issue 037 - March 1993](https://archive.org/details/cuamiga-magazine-037/page/n11/mode/2up) </br>
Requires minimum 1MB of FAST RAM, Today thats Not a problem, most CPU accelerator boards have plenty of Fast RAM. </br>
The SW is Not available on [aminet website](https://aminet.net/) "Amiga AppStore / Pre-PPA Repository" </br>

Amiga 4000 "1995" is Pre-TCP/IP era, pre-SSL era </br>
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

4000"D" Desktop, all units had battery leak that damaged the boards </br>
several Amiga enthusiasts repaired the "survivors" from land fills & recycling centers </br>
4000D has differet board revisions "was a work in progress" </br>
some repairs were not feasible "too much damaga", thats how Recreation Boards were born. </br>

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
