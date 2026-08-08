# Amiga Guide 4000D / 4000T

"from Zero to Hero" </br>

**v0.00000010** </br>

This is a compilation / combined knowledge of many websites, </br>
Condensed as much as possible, "for Beginners". </br>

## Background History

[Amiga 4000 (1992-1994)](https://en.wikipedia.org/wiki/Amiga_4000) "Desktop" & Tower [A4000T (1994-1996)](https://en.wikipedia.org/wiki/Amiga_4000T) </br>
were the last & best Amiga made around Motorola 68K 030 040 CPU's, </br>
has optional 3rd party accelerator boards that allow CPU upgrades </br>
there are different kinds of CPU upgrades: </br>
ARM "Bare Metal SW Emulation", FPGA, Real Motorola [68060](https://en.wikipedia.org/wiki/Motorola_68060) & 604e PowerPC CPU's </br> 
[Amiga 500 (1987-1992)](https://en.wikipedia.org/wiki/Amiga_500) / [1000 (1985-1987)](https://en.wikipedia.org/wiki/Amiga_1000) / [2000 (87-91)](https://en.wikipedia.org/wiki/Amiga_2000) / [600 (92-93)](https://en.wikipedia.org/wiki/Amiga_600) / [1200 (92-96)](https://en.wikipedia.org/wiki/Amiga_1200) were much more common = most games were designed for Kickstart 1.3 ROM & 68000 CPU. </br>

There were changes over the years to accomodate New technologies "better graphics like [AGA](https://en.wikipedia.org/wiki/Amiga_Advanced_Graphics_Architecture) more Arcade custom chips </br>
Arcade machines price was 10x more vs. Commodore 64: Dual CPU's, Dedicated Sprite / Graphics accelerator, but were "1 trick pony" </br>
Amiga was inspired by Arcade machines graphic technology, but "Swiss Army Knife". </br>
Commodore 64 was a 10k to 23k Trick Pony, even few people had all titles. </br>

The Only mistake in the Amiga series, in my opinion was removing the [SID 6581](https://en.wikipedia.org/wiki/MOS_Technology_6581) Analog Audio Synth from the C64 / C128 / C65 </br>
Around same era, PC's were having Yamaha 4-Op Synths "Adlib compatible", MIDI Roland MT-32, up to 32MB Waveform GM Sampler soundcards AWE64 based on E-mu / Ensoniq technology. </br>

Motorola also did changes to the CPU's 68k [020](https://en.wikipedia.org/wiki/Motorola_68020) [030](https://en.wikipedia.org/wiki/Motorola_68030) [040](https://en.wikipedia.org/wiki/Motorola_68040) [060](https://en.wikipedia.org/wiki/Motorola_68060) to increase speed, less common instructions were removed, </br>
architectures were combined: 040 = 030 + [68882](https://en.wikipedia.org/wiki/Motorola_68881) FPU "80387" </br>
060 was redesigned for [SuperScalar](https://en.wikipedia.org/wiki/Superscalar_processor) architecture, like SGI RISC CPUs </br>
with dual pipelines "Pseudo-Parallelism / early pre-Dual Core era" </br>
transistor technology was improved with every revision </br>
many improvements were made But... 100% backward compatibility was lost. </br> 
some SW designed for Kickstart ROM v1.3 & 68K 000 CPU's  </br>
have weird issues, or don't work on newer A4000 / A1200 with AGA, 060, Kickstart ROM v3.1 </br> 
in 1993 a software called ReloKick [v1.41](https://archive.org/details/ReloKick_v1.41_1994_Geesus) & [1.4a](https://archive.org/details/ReloKick_v1.4a_1994_DCS) </br>
was made to create a soft-compatibility layer: </br>
Emulate Kickstart 1.3 ROM in RAM on Newer [Kickstart](https://en.wikipedia.org/wiki/Kickstart_(Amiga)) </br>
SW came with [CU Amiga Magazine issue 037 - March 1993](https://archive.org/details/cuamiga-magazine-037/page/n11/mode/2up) </br>
Requires minimum 1MB of FastRAM, Today thats Not a problem, most CPU accelerator boards have plenty of Fast RAM. </br>
The SW is Not available on [aminet website](https://aminet.net/) "Amiga AppStore" Pre-PPA Repository. </br>

A4000 is pre-TCP/IP, pre-SSL </br>
there are several Ethernet 100Mbps cards available for Zorro slots. </br>
but requires several SW to connect to modern internet websites like: Aminet directly. </br>
[iBrowser](https://www.ibrowse-dev.net/download.php) has CPU SSL emulation layer </br>
Newer latest generation CPU Accelerator boards like [Z3660](https://github.com/shanshe/Z3660) have SSL HW decoder + FPGA board. </br>
New ZZ9000 GPU firmware update also has planned SSL HW Accelerator / Decoder. </br>

to trasfer files from FreeDOS / MS-DOS "FAT16/32" Floppy to Amiga FastFileSystem "FFS" </br>
AmigaOS has an emulator, does Not start by default at boot. </br>
Amiga also had Bridge Boards that allow to emulate a PC XT 8088, 8086, 286, 386, 486slc </br>
2 computers in 1 Box, running simultaneusly, capable of transfering files back & forth, like a Virtual Machine but Real HW. </br>

The other ways: "writing Amiga 880k floppy directly on Mac/PC/Linux" has different options:  </br>
HW [KryoFlux Floppy emulator](https://kryoflux.com/?page=kf_features) </br>
[GreaseWeazle](https://github.com/keirf/greaseweazle).[RetroFuzion](https://www.retrofuzion.com/products/greaseweazle-deluxe-kit) </br>
SW [Amiga Explorer](https://www.amigaforever.com/ae/) machine-to-machine communication using serial port, or USB Bluetooth (RS-232) adapters. </br>
Gotek USB Floppy Emulators "STM32" with optional [HxC Firmware](https://hxc2001.com/docs/gotek-floppy-emulator-hxc-firmware/pages/firmware-update.html) &/or FlashFloppy Firmware </br>
WinUAE, FS-UAE, E-UAE "Linux" </br>

A1200 has "the same" AGA Graphics custom chip like A4000 in a compact format, </br>
like Atari Falcon 030 vs. Atari Mega or TT030 </br>
"All-In-One Keyboard" </br>

AmigaOS has a SW that allow to run macOS 8.1 designed for Motorola 68K CPU's </br>
["The fastest Mac is an Amiga"](https://odysee.com/@RMCretro:9/the-fastest-apple-mac-is-an-amiga-fact:2) </br>
Apple, Amiga & AtariST had Unix OS called: A/UX & AMIX </br>
some claim that Classic Macs were locked in ROM Bios so it cannot be upgraded to 060 CPU's </br>
because Mac was moving to PPC, did Not wanted comptetition. </br>

Early 4000D "Desktop" (1992-1993) all had battery leak that damaged the boards </br>
several Amiga enthusiasts repaired the "survivors" from land fills & recycling centers </br>
some repairs are on several YouTube channels </br>
4000D (1992-1994) has differet board revisions "was a work in progress" </br>
some repairs were not feasible "too much damage" thats how Recreation Boards were born. </br>
A4000-CR "Cost-Reduced" (1993-1994) battery was replaced with coin battery. </br>

A4000T "Tower" has a coin battery like -CR, there is only 1 Final Rev4 board, </br>
has built-in SCSI-2 NEC 53C710 controller, Desktop does Not have SCSI-2. </br>
A4000T Requires a different Rom Kickstart 3.1T with SCSI-2 drivers. </br>
A4000D has many optional 3rd party SCSI Cards available </br> 
schematics were reverse eng. and [recreation boards were made](https://scsi.me/#lineup)  </br>

Amiga 4000 series D/T have Zorro-3 Slots "faster" vs. A2000 Zorro-2 </br>
AGA video chipset like A1200 </br>
All Amigas come with a "basic" GPU, that requires special 15KHz monitor, &/or scan converter  </br>
rare DB23 connector + adapter to DB15 VGA </br>
The A/T has standard AT Power supply "low efficiency 68%"  </br>
The "D" has a different custom PSU, with different connectors. </br>

many Amiga store websites sell most parts for DIY or pre-built adapters. </br>

A3000 & A2000 have a similar story, but more advanced,  </br>
because were more common / available, easy to buy / find,  </br>
some recreated custom chips in FPGA "drop in replacements"  </br>
[A3000 (90-92)](https://en.wikipedia.org/wiki/Amiga_3000) was recreated completely again in Hardware. </br>
A4000 still require custom IC's: D has socket, T is soldered to the board. </br>
similar to C64, custom ICs were also recreated in FPGA, ARM & CPLD. </br>

When Apple transitioned to PPC, some Amiga developers also created Dual-CPU accelerator boards </br>
like Cyberstorm Mk3 with M68k 060 & PowerPC 603e or 604e </br>
AmigaOS4 was recompiled for PPC architecture, </br>
and Newer Amiga X1000 X5000 machines for PPC were launched </br>
Those PPC had a CPU similar to PowerMac G5 "64-Bit" Single/Dual-Core versions </br>
but the CPU they chosed does Not have Altivec "MMX instructions" </br>
There are Modern PPC Cpus today for embedded systems that contain Altivec "Newer" generations </br>
That was a major design flaw in my opinion of the X Amiga PPC generation. </br>

## GPU's
Older GPU's like [PicassoIV v1.2](https://amiga.resource.cx/exp/picasso4).[wiki](https://www.amigawiki.org/doku.php?id=en:expansion:av:picasso_iv).[bbah](https://bigbookofamigahardware.com/bboah/product.aspx?id=468) & [Piccolo SD64](https://www.youtube.com/watch?v=bqqmQgWlQX0).[cx](https://amiga.resource.cx/exp/piccolosd64) </br>
based on Cirrus Logic GD5446BV-HC-A/B & GD5434-HC-A/B + custom FPGA, </br> 
were very desired because didnt had the 15KHz limitation, 4MB VRAM allows Hi-Res SVGA/XVGA CRT's. </br>
called RTG graphics card "Re-Traceable Graphics" </br>
New RTG GPU's like MNT [ZZ9000](https://www.youtube.com/watch?v=NTnixC5ym-o) latest Rev. take Amiga to the Next level. </br>
some PCI upgrade Riser cards like Mediator & Prometheus allow installing Voodoo PCI cards + Warp3D drivers. </br>
There are 3D Voodoo Replica cards, and FPGA replica FuryGPU card in development. </br>

RTG GPU's require Picasso96 driver: [v2.0 "Free" (1999)](https://aminet.net/package/driver/video/Picasso96).[emu](https://aminet.net/package/driver/video/P96Emu) or latest Paid [P96 v3.6.3](https://wiki.icomp.de/wiki/P96) version </br>

## HW 68K Alternatives: 
[Minimig.ca](https://www.minimig.ca/shop-2/) 1.98itx is a hybrid FPGA custom chip emulation board, with socket for a Real 68K CPU &/or compatible accelerator boards. </br>
BFG, TF, Apollo Vampire, [Z3660](https://github.com/shanshe/Z3660) etc... </br>
[MIST 1.5/1.6](https://lotharek.pl/products.php?id=14) made by Lotharek in Poland "complete custom FPGA emulator" </br>
MISTer complete FPGA emulator based on [Terasic DE-10 Nano](https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&No=1046) dev board + custom hats "i/o boards" </br>
Apollo [Vampire V4](https://www.apollo-computer.com/v4standalone.php) custom [64-bit](http://www.apollo-core.com/index.htm?page=family&tl=7) [080](https://wiki.apollo-computer.com/doku.php?id=apollo_core:start) FPGA CPU accelerator board "060 compatible", [Super-AGA](http://www.apollo-core.com/index.htm?page=chipset) "AGA" compatible </br>
small stand alone complete FPGA emulator or A6000 "All-In-One keyboard" like A600/A1200, & CPU accelerator boards for Vintage Amigas. </br>

## SOFTWARE
There are many ABANDONEARE software titles "TOSEC", websites like [Myabandonware](https://www.myabandonware.com/browse/platform/amiga/) </br>
there is also New developers like [Geezer games](https://mcgeezer.itch.io/) & [Metro Siege](https://metrosiege.com/download/beta/) </br>
if you search youtube "New Amiga Games in 2020 / 2021 / [2022](https://www.youtube.com/watch?v=KK9zg2Vh7AI)" there are several [youtube channels](https://www.youtube.com/@retrogamingdino) with links to the developers. </br>
Some developers improve older games with AGA graphics, unlocked FPS, taking advantage of CPU accelerator boards with More FastRAM </br>
others Port old Arcade ROM games to Amiga </br>
others create Open Source OS like CaffeineOS, [AROS](http://www.aros.org/), [Vision](https://www.aros-vision.de/download.html), [T2sde-Linux](https://dl.t2sde.org/binary/2025/), etc... </br>

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
or buy a T56 / T76 Programmer "No Adapter required" </br>

1. AmigaForever 1.3 -> 3.1 ROMs
2. Hyperion 3.2.x ROMs
3. prepare Roms "Swap & Split" Non needed using UAE Emulators.
4. buy or diy a Zif-socket adapter for TL866-ii / T48 "more than 40-pins" *Not needed with T56 / T76
5. Buy 2 Roms. "if making a New machine"
6. Burn 2 Roms with TL866-II / T48 or similar Eprom Programmer.

Alternate: if UV Eraseable ROMs are "Hard to Find" or Expensive </br>
there is also the Project [OneROM](https://onerom.org/) that Emulate EPROMs based on STM32 "more than 40-pins Required" </br>

UV Eraseable Roms do Not Erase with LED UV-A flashlights </br>
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
there are CompactFlash CF to IDE adapters and SCSI-2, </br>
RaSCSI, PiSCSI, ZuluSCSI, XT-IDE </br>
there is also SSD SATA-to->IDE & [SATA-II-to->50-pin SCSI-2](http://www.acard.com/index.files/Page799.htm) [adapter.](http://www.acard.com/index.files/Page728.htm) </br>

i have an "Acme" SATA SSD-to->IDE adapter, Generic IC, </br>
Startech sell [similar](https://www.startech.com/en-us/hdd/ide2sat2) with Marvell 88SA8052 IC </br>
The generic adapter, maximum speed on a modern Computer is 100MB/s ATA100 </br>
i could Not reach 133MB/s using a [891U3](https://www.youtube.com/watch?v=NKpzkbOS59Y) USB3.0 to IDE "Generic" adapter, </br>
[Startech USB3SSATAIDE](https://www.startech.com/en-us/hdd/usb3ssataide) version </br>
P.D. Do Not use the 891U3 included PSU has +6vdc, some equipment will burn, </br>
older Blue version USB2.0 to IDE had ~5.5vdc </br>
Moderm Boards don't have IDE, but there are PCI IDE cards available, </br>
and PCI to PCIe adapters, also with different IC controllers. </br>

Fast SCSI-2 in theory can go up to 40 MB/s on 32-Bit [Zorro-3](https://en.wikipedia.org/wiki/Zorro_III) <= [USB2.0 Speeds](https://en.wikipedia.org/wiki/USB#USB_2.0) </br>
if want to know how fast or slow is,
install a modern Linux Ubuntu / Kubuntu 20.04 or 22.04 on a external USB3 SSD case, </br>
connected to a USB2.0 port, hit F11 at Boot. </br>
using Flash memory is much slower: CF, SD & microSD cards vs. SSD </br>
microSD overheat very easy & enter in Thermal Throtling with sustained R/W. </br>
Slow-to->Fast: Flash, eMMC, mSATA, SSD, M.2 SATA, M.2 NVMe PCIe v3 v4 v5 </br>
Server: SAS U.2 U.3 </br>
Smartphone: UFS 1.0 -> 5.0 </br>

## Floppy drives
There are severa lists of [compatible Floppy drives for Amiga](https://jope.fi/drives/computolio/).[PDF](http://www.pitsch.de/stuff/amiga/Amiga%20Drive%20Compatibility.pdf).[web](https://gamesx.com/wiki/doku.php?id=amiga:amiga_floppy_drive_compatibility).[links](https://amigaalive.blogspot.com/p/hardware-using.html).[HxC](https://hxc2001.com/download/floppy_drive_emulator/support.htm) </br>
and modification tutorials to convert standard PC 1.44MB drives to 880k drives, </br>
most Amigas had SD 880k drives, but A4000 have HD 1.76MB. </br>
with Gotek USB floppy emulators or similar HxC ¿is that necesary ? </br>
IF you have Original installer discs on floppy, probably yes. </br>

PC era when floppy controllers were removed from the boards, </br>
XP install.iso required an USB1.1 Floppy drive </br>
Amigas are Pre-USB era, but today there are several USB cards for Amiga, some better than others. </br>

## PowerSupply

4000D Replica boards have a "custom Amiga power connector" </br>
4000T replica boards have AT standard PSU connector "P8/P9 Black wires to the center" </br>

Many Amiga stores sell an ATX to AT converter cable + Switch for Tower </br>
because the Desktop case is smaller vs. Tower case, replacing PSU is Not as common </br>
Newer PSU's have much better [80 Plus](https://en.wikipedia.org/wiki/80_Plus#Efficiency_level_certifications) Efficiency </br>
SFF & SFF+ Power Supplys are smaller vs. Standard ATX's PSU's. </br>

Optional there is a DIY ATX2AT converter / Analyzer / Power Protection circuit. </br>

## Stores List "Unverified"
https://amigastore.eu/en/6-amiga-4000 </br>
https://www.amiga-shop.net/en/Amiga-Hardware/ </br>
https://amiga68k.com/ </br>
https://amigastore.com/ </br>
http://amiga-store.us/ </br>
https://amigastore.eu/ </br>
http://amiga-store.com/ </br>
https://wiki.icomp.de/wiki/Indivision </br>
https://amigakit.amiga.store/ </br>
https://shop.myamigashop.com/ </br>
https://myamigashop.com/ </br>
https://amigakit.com/ </br>
http://amikit.com/ </br>
https://www.amigakit.eu/ </br>
https://amigatronic.com/ </br>
https://www.retro32.com/ </br>
https://store.amigaofrochester.com/ </br>
https://www.ami64.com/ </br>
https://www.amigashop.org/index.php?language=en </br>
https://amigaofrochester.com/ </br>
https://www.retro8bitshop.com/ </br>
https://amigaonthelake.com/ </br>
https://www.retropassion.co.uk/ </br>
https://www.micromiga.com/ </br>
https://www.pureamiga.co.uk/ </br>
https://amigaspirit.com/ </br>
http://www.amiga-store.biz/ </br>
https://www.ami64.com/amiga-computers </br>

#### Hyperion Official Dealers List: </br>
https://www.hyperion-entertainment.com/index.php/where-to-buy/dealers </br>

### NEWS
https://www.lemonamiga.com/ </br>

### OS4 "PPC" Real HW or AmigaForever Win-UAE QEMU emulation
http://amistore.net/ </br>
https://www.amigaos.net/content/72/supported-hardware </br>


https://www.retro-commodore.eu/ </br>
https://wiki.amiga.org/index.php/Amiga_Stores </br>

## WHDLoad
[WHDLoad](http://www.whdload.de/) is a tool that allows disk based games/sw/demos to be installed & run from the hard drive, </br>
even if were never designed to do so. </br>
Also fixes incompatibility issues between different kickstarts & Amiga models. </br>
a more advanced version of ReloKick ? </br>

http://www.whdload.de/ </br>
https://eab.abime.net/showthread.php?t=38299 </br>
https://classicwb.abime.net/classicweb/instructionsp96.htm </br>

## HW Tests
There are several Diagnostic utilities, that does Not require Workbench, </br>
Boot Directly to Diagnostic, there are Floppy versions, and ROM versions. </br>

## CASE
A4000T is "AT compatible" in many ways, but is Not 100% ATX compatible... </br>
the Ports Module: Serial, Parallel, Mouse, Joystick daugter board, 
An Original Amiga A4000T case, has holes / cut-outs on the case, </br>
but the board does Not fit a modern ATX case back plate. </br>
Sollution is the project [ATX Ports module](https://gitlab.com/amiga-projects/atx_ports_module).[amybay](https://www.amibay.com/threads/a4000t-bom-incl-parts-list.2447556/) </br>

## CPU Boards

Original A3630 & A3620 boards, </br>
The A3630 Rev3.1 has a small Bug on the print, </br>
3 capacitors polarity is painted backwards, </br>
Replacing capacitors backwards in some cases, creating a short on the PCB. </br>
Sollution always check with a DMM the Negative polarity to GND begore installing. </br>

# BOM DIY

[Bill.Of.Materials](https://docs.google.com/spreadsheets/d/1czsNg6O3RXiB12KduvjW-nOGRPwfiWtYTnK7Xi-feMI/edit?gid=0#gid=0) </br>
Component Locator: </br>
[Main Board](https://locator.reamiga.info/index.php) </br>
[Main Board Site2](https://www.amiga4000tower.de/smf/pms/a4tlocator5.php) </br>
[Schematics](https://web.archive.org/web/20241118204624/https://sites.google.com/site/tbtorro/) </br>
