# Amiga Guide 4000D / 4000T

"from Zero to Hero" </br>

**v0.00000100** </br>

This is a compilation / combined knowledge of many websites, </br>
Condensed as much as possible, "for Beginners". </br>

## Background History

[Amiga 4000 (1992-1994)](https://en.wikipedia.org/wiki/Amiga_4000) Desktop & Tower [A4000T (1994-1996)](https://en.wikipedia.org/wiki/Amiga_4000T) </br>
were the last & best Amiga made around Motorola 68K 030 040 CPU's, </br>
has optional 3rd party accelerator boards that allow different kinds of CPU upgrades: </br>
ARM "Bare Metal SW Emulation", FPGA, Real Motorola [68060](https://en.wikipedia.org/wiki/Motorola_68060) & 604e PowerPC CPU's </br> 
[Amiga 500 (1987-1992)](https://en.wikipedia.org/wiki/Amiga_500) / [1000 (1985-1987)](https://en.wikipedia.org/wiki/Amiga_1000) / [2000 (87-91)](https://en.wikipedia.org/wiki/Amiga_2000) / [600 (92-93)](https://en.wikipedia.org/wiki/Amiga_600) / [1200 (92-96)](https://en.wikipedia.org/wiki/Amiga_1200) were more common = most games were designed for Kickstart 1.3 ROM & 68000 CPU. </br>

There were changes over the years to accomodate New technologies "better graphics like [AGA](https://en.wikipedia.org/wiki/Amiga_Advanced_Graphics_Architecture) more Arcade custom chips </br>
Arcade machines price was 10x-32x more vs. Commodore 64: Dual CPU's, Dedicated Sprite / Graphics accelerator, 3 boards but 1 trick pony. </br>
Amiga was inspired by Arcade graphic technology, but "Swiss Army Knife". </br>
Commodore 64 was a 10k to 23k Trick Pony, even few people had all titles. </br>
in LemonAmiga Database there is [<500 titles](https://www.lemonamiga.com/games/list.php?list_hardware=AGA) for AGA chipset, because was released in (1992) vs. Original Chipset in 1987, all games for CD32 are AGA, Amiga 4000 has a floppy that allows to boot CD32 CD's. </br>
CD32 has a [Chunky Pixels](https://en.wikipedia.org/wiki/Packed_pixel) to Bit plane accelerator [AKIKO IC](https://www.youtube.com/watch?v=I-QAhxMhb5Q&t=1213s) </br>
Amiga 1200/4000 requires a fast CPU to do the conversion on CPU but A4000/T allows Zorro-3 [RTG](https://en.wikipedia.org/wiki/Retargetable_graphics) graphic cards. </br>
[AGA](https://en.wikipedia.org/wiki/Amiga_Advanced_Graphics_Architecture) is the basic on-board GPU on A1200 & A4000/T, more advanced vs. previous generations in C64, Amiga OCS 500/1000/2000 & 3000 [ECS](https://en.wikipedia.org/wiki/Amiga_Enhanced_Chip_Set) </br>

The Only mistake in the Amiga series, in my opinion was removing the [SID 6581](https://en.wikipedia.org/wiki/MOS_Technology_6581) Analog Audio Synth from the C64 / C128/D / [C65](https://en.wikipedia.org/wiki/Commodore_65) </br>
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
Requires minimum 1MB of FastRAM, Today thats Not a problem, most CPU accelerator boards have plenty of FastRAM. </br>
there are modifications to breakthrough 16MB FastRAM Limit w/o CPU Accelerator to 64MB & [112MB](https://drive.usercontent.google.com/download?id=15nFvyg4oYhQpE3a8nD3mrfQDS_BrZPch&export=download) </br>
ReloKick is Not available on [aminet website](https://aminet.net/) "Amiga AppStore" Pre-PPA Repository, Nor A-EON OS4 appstore. </br>

A4000 is pre-TCP/IP, pre-SSL </br>
there are several Ethernet 100Mbps cards available for Zorro slots, </br>
but requires several SW to connect to modern internet websites like: Aminet directly. </br>
[iBrowser](https://www.ibrowse-dev.net/download.php) has CPU SSL emulation layer </br>
Newer generation CPU Accelerator boards like [Z3660](https://github.com/shanshe/Z3660) have SSL HW decoder + FPGA board. </br>
New ZZ9000 GPU firmware update also has planned SSL HW Accelerator / Decoder. </br>

to trasfer files from FreeDOS / MS-DOS "FAT16/32" Floppy to Amiga FastFileSystem "FFS" </br>
AmigaOS has an emulator, does Not start by default at boot. </br>
Amiga also had Bridge Boards that allow to emulate a PC XT 8088, 8086, 286, 386, 486slc </br>
2 computers in 1 Box, running simultaneusly, capable of transfering files back & forth, like a Virtual Machine but Real HW. </br>

Amiga Floppy were 880k vs. [IBM PC](https://en.wikipedia.org/wiki/List_of_floppy_disk_formats#Logical_formats) 740KB because: </br>
Amiga does Not have Sectors inside each track, only 1 at Start & End of each Track, writting a cotinious track. </br>

Other ways: "writing Amiga 880k floppy directly on Mac/PC/Linux" has different options:  </br>
HW [KryoFlux Floppy emulator](https://kryoflux.com/?page=kf_features) </br>
[GreaseWeazle](https://github.com/keirf/greaseweazle).[RetroFuzion](https://www.retrofuzion.com/products/greaseweazle-deluxe-kit), ArduinoBridge & others. </br>
SW: [Amiga Explorer](https://www.amigaforever.com/ae/) machine-to-machine communication using serial port, or USB Bluetooth (RS-232) adapters, </br>
DrawBridge, FloppyBridge for WinUAE, </br>
Gotek USB Floppy Emulators "STM32" with optional [HxC Firmware](https://hxc2001.com/docs/gotek-floppy-emulator-hxc-firmware/pages/firmware-update.html) &/or FlashFloppy Firmware, converting files to .adf image format, using Xcopy or similar Amiga SW, Reading on PC: [Disk2FDI](http://www.oldskool.org/disk2fdi/trial.html) </br>
WinUAE, FS-UAE, E-UAE "Linux" </br>

A1200 has "the same" AGA Graphics custom chip like A4000 in a compact format, </br>
like Atari Falcon 030 vs. Atari Mega or TT030 </br>
"All-In-One Keyboard" </br>

Amiga has a SW called ShapeShifter that allows to run macOS 7.1 to 8.1 for Motorola 68K CPU's </br> 
["The fastest Mac is an Amiga"](https://odysee.com/@RMCretro:9/the-fastest-apple-mac-is-an-amiga-fact:2) </br>
Apple, Amiga & AtariST had Unix OS called: A/UX & AMIX </br>
some claim Classic Macs were locked in ROM so it cannot be upgraded to 060 CPU's </br>
because Mac was moving to PPC, did Not wanted comptetition. </br>

Early 4000D "Desktop" (1992-1993) all had a battery that leak & damaged the boards </br>
several Amiga enthusiasts repaired the "survivors" from land fills & recycling centers </br>
some repairs are on several YouTube channels </br>
4000D (1992-1994) has different board revisions "was a work in progress" </br>
some repairs were not feasible "too much damage" thats how Recreation Boards were born. </br>
A4000-CR "Cost-Reduced" (1993-1994) leak battery was replaced with coin battery, No-leak. </br>

A4000T "Tower" has coin battery like -CR, there is only 1 Final Rev4 board, </br>
has built-in SCSI-2 NEC 53C710 controller, Desktop does Not have SCSI-2. </br>
A4000T Requires a different Rom Kickstart 3.1T with SCSI-2 drivers. </br>
A4000D has many optional 3rd party SCSI Cards available </br> 
schematics were reverse eng. and [recreation boards were made](https://scsi.me/#lineup)  </br>

Amiga 4000 / 3000 series have Zorro-3 Slots "faster" vs. A2000 Zorro-2 </br>
AGA video chipset like A1200 </br>
All Amigas come with a "basic" GPU, that requires special 15KHz monitor, &/or scan converter + </br>
Rare DB23 adapter to DB15 VGA </br>
The A4000/T has standard AT Power supply "Efficiency 68%"  </br>
The "D" has a different PSU, different connectors. </br>

many Amiga store websites sell most parts for DIY or pre-built adapters, </br>
to adapt a Newer ATX >2.1 PSU to A4000/T boards for example. </br>

A3000 & A2000 have a similar story, </br>
were more common, easy to buy / find,  </br>
some recreated all custom chips in FPGA "drop in replacements"  </br>
[A3000 (90-92)](https://en.wikipedia.org/wiki/Amiga_3000) was recreated completely again in Hardware. </br>
A4000 still require custom IC's: D has socket, T is soldered to board. </br>
similar to C64 story, custom ICs were recreated in FPGA, ARM & CPLD like SID, GAL, PLD, Memory. </br>

When Apple transitioned to PPC, some Amiga developers also created Dual-CPU accelerator boards </br>
like Cyberstorm Mk3 with M68k 060 & PowerPC 604e </br>
AmigaOS4 was recompiled for PPC architecture, </br>
Newer Amiga X1000 X5000 machines for PowerPC were launched </br>
Those PPC had a CPU similar to PowerMac G5 "64-Bit" Single/Dual-Core versions </br>
but the CPU they chosed does Not have Altivec "MMX instructions" </br>
That was a major design flaw in my opinion of the X Amiga PPC generation. </br>
There are Modern PPC Cpus for embedded systems that contain Altivec. </br>

## GPU's
Older GPU's like [PicassoIV v1.2](https://amiga.resource.cx/exp/picasso4).[wiki](https://www.amigawiki.org/doku.php?id=en:expansion:av:picasso_iv).[bbah](https://bigbookofamigahardware.com/bboah/product.aspx?id=468) & [Piccolo SD64](https://www.youtube.com/watch?v=bqqmQgWlQX0).[cx](https://amiga.resource.cx/exp/piccolosd64) </br>
based on Cirrus Logic GD5446BV-HC-A/B & GD5434-HC-A/B + custom FPGA, </br> 
were very desired because didnt had the 15KHz limitation, 4MB VRAM allows Hi-Res SVGA/XVGA Monitors. </br>
called [RTG](https://en.wikipedia.org/wiki/Retargetable_graphics) graphics card "Re-Traceable Graphics" </br>
New [RTG](https://en.wikipedia.org/wiki/Retargetable_graphics) GPU's like MNT [ZZ9000](https://www.youtube.com/watch?v=NTnixC5ym-o) latest Rev. take Amiga to the Next level. </br>
some PCI upgrade Riser cards like Mediator & Prometheus allow installing Voodoo PCI cards </br>
There are 3D Voodoo Replica cards, and FPGA replica FuryGPU card in development. </br>

[RTG](https://en.wikipedia.org/wiki/Retargetable_graphics) GPU's require Picasso96 driver: [v2.0 "Free" (1999)](https://aminet.net/package/driver/video/Picasso96).[emu](https://aminet.net/package/driver/video/P96Emu) or latest Paid [P96 v3.6.3](https://wiki.icomp.de/wiki/P96) version </br>
or... [CGX](https://en.wikipedia.org/wiki/Retargetable_graphics#CyberGraphX) CyberGraphX [v4 drivers](https://aminet.net/package/driver/video/CyberGraphX_4.3rc4) or [v3](https://aminet.net/package/driver/video/CyberGraphX3) or [old CD](https://archive.org/details/cu-amiga-super-cd-rom-19) </br>

RTG intercepts AGA signals from Zorro-3 video slot, and bypass the weird DB23 VGA output in most situations, </br>
but some AGA games can be "forced" to run in Native RTG "[CGX](https://en.wikipedia.org/wiki/Retargetable_graphics#CyberGraphX)" mode, installing: [NewMode v3.9](https://aminet.net/package/util/cdity/NewMode_V39.lha) </br>

Colonization, MegaBall 4, [SimAnt](https://web.archive.org/web/20010419000629/http://www.mcs.net/~kanep/www/simant.html), SimEarth.

Basically Amiga Chipset: </br>
OCS -> ECS "A3000" -> AGA "A1200 & A4000/T" -> RTG Zorro-2/3 -> "CGX" </br>
Original Chipset -> Enhanced Chipset -> Advanced Chipset -> [Retraceable Graphics](https://everything.explained.today/Retargetable_graphics/) -> CyberGraphX </br>
3rd Party: Apollo Vampire V4 68k 080 -> SuperAGA </br>

#### Links: </br>
[CGX Dev Docs](https://github.com/FraBro1/CybergraphX-4-Dev/tree/main) from [old domain source](https://web.archive.org/web/20040609133957/http://home.earthlink.net/~mike.sherman/) </br>
[old Picasso96 website](https://web.archive.org/web/20040611233517/http://www.picasso96.cogito.de/) </br>
[old files](https://web.archive.org/web/20010410091511/http://www.mcs.net/~kanep/www/cgx.html) </br>
[old vgr.com CyberGraphX](https://web.archive.org/web/20040603055157/http://www.vgr.com/cybergfx/)
[old Zorro cards list](https://web.archive.org/web/20040616074402/http://www.vgr.com/cybergfx/boardtable.html) </br>

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
Some developers improve older games with AGA graphics, unlocked FPS, taking advantage of CPU accelerator boards, RTG, More FastRAM </br>
others Port old Arcade ROM games to Amiga, like Atari Tetris version. </br>
others create Open Source OS like CaffeineOS, [AROS](http://www.aros.org/), [Vision](https://www.aros-vision.de/download.html), [T2sde-Linux](https://dl.t2sde.org/binary/2025/), Debian 9, 10, 12 for 68K, etc... </br>

## DIY
If you buy a Replica board from one of the many Amiga sellers / stores, </br>
to replace the old damaged board "transplant components", to create a New machine or to Repair. </br>

[Parts List](https://docs.google.com/spreadsheets/d/1czsNg6O3RXiB12KduvjW-nOGRPwfiWtYTnK7Xi-feMI/edit?gid=0#gid=0) </br>

### New HW machine or use Software Emulators: </br>

Anyway Requires purchasing Legal Kickstart ROM's 1.3 to 3.1 from [AmigaForever Plus .iso](https://www.amigaforever.com/plus/) "Cloanto" </br>
ROMs 3.X with CAPITAL X, is "10" 3.10 ROM but that was an early jump. </br>
Later Hyperion created ROM's: 3.1.4 in (2018) </br>
Roms 3.2 in 2020 as Physical Purchase & <br>
ROMs 3.2.x as [Digital Download](https://www.hyperion-entertainment.com/index.php/where-to-buy/direct-downloads/327-amigaos-32) in (2026) </br>

IF you buy the Digital Downloads, and you are making a New machine, </br>
you need prepare the ROMs before Burning with a TL866-II or similar T48 Eprom Programmer </br>
Compatilble ROM's UV Eresable Am27C400 or similar faster than <200ns access time. </br>
need to Change from Little.Endian "x86_64 PC" to Big.Endian "68K" / "Swap the Bytes Order" </br>
and Splt Single ROM images from the Digital Download to fit 2x EPROMS </br>
because machines are 32-Bit and Roms are configured 16-Bit each. </br>
also needs a Zif-Socket adapter board, because TL866-II plus & T48 programmers only have 40-pins, </br>
or buy a T56 / T76 Programmer "No Adapter required" </br>

1. [AmigaForeverPlus 1.3 -> 3.1 ROMs](https://www.amigaforever.com/plus/)
2. [Hyperion 3.2.x ROMs](https://www.hyperion-entertainment.com/index.php/where-to-buy/direct-downloads/327-amigaos-32)
3. prepare Roms: "Swap Bytes & Split" Not needed using UAE Emulators or T56 & T76 programmers.
4. buy or diy a Zif-socket adapter for TL866-ii / T48 "more than 40-pins" *Not needed with T56 / T76
5. Buy 2 Roms. "if making a New machine"
6. Burn 2 Roms with TL866-II / T48 or similar Eprom Programmer.

Alternate: if UV Eraseable ROMs are "Hard to Find" or Expensive </br>
there is also the Project [OneROM](https://onerom.org/) that Emulate EPROMs based on STM32 "more than 40-pins Required" for A4000T </br>
there are modifications to A4000/T that allow to use Bigger than >512KB ROM's "easy to find" like 27C400, 27C800, 27C160 </br>
ther are other adapters that allow dual or multiple ROMs at Boot, similar to C64U or Easy Flash 3 Cartridge for C64 </br>

UV Eraseable Roms do Not Erase with LED UV-A flashlights </br>
Some Chinese sellers have a Proper UV-Eraser Plastic Box, IF buy USED UV Eproms </br>
UV Eraseable Eproms are designed to last much more than Flash ROMs, does Not have the problem of "Write Times" nor "Temperature", nor Static </br>

The Proper UV-Eraser contains a 6" Pure Quartz vacuum tube "like CFL lamps" with 2 or 3 Mercury 3mm BallBearings's inside. </br>
High Voltage "120v" Evaporate Mercury, Mercury Glow like Neon signs, generates a >200nm Peak UV-C </br>
Human Eyes cannot see 200nm, but also generates Harmonics / Resonances around 450nm "Cyan Blue" Visible, </br>
Requires only ~10 minutes. </br>
Using the Sun requires much more time becasue Ozone Layer Blocks UV-C </br>
cannot be Erased indors because Normal Glass also Blocks UV-C </br>
Placing a Black Tape over the [Quartz UV Window](https://en.wikipedia.org/wiki/EPROM#Gallery) = moving the tab on a Floppy to say ["Write Protect"](https://en.wikipedia.org/wiki/Write_protection#Examples) </br>

## IDE vs. SCSI-2

Mechanical IDE or SCSI HDD's are most gone / damaged, but.. </br>
there are CompactFlash CF to IDE adapters and SCSI-2, </br>
RaSCSI, PiSCSI, ZuluSCSI, XT-IDE "8-bit", AT-IDE "16-bit" </br>
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

Original A3630 & A3640 boards: </br>
The A3640 Rev3.1 has a small Bug on the silkscreen print, </br>
3 capacitors polarity is painted backwards, </br>
Replacing capacitors backwards in some cases, creating a short on the PCB. </br>
Sollution always check with a DMM the Negative polarity to GND before installing. </br>

Accelerators based on Software emulations like Z3660 + FPGA board or PiStorm32 based on Pi4B, or Amibery, on Synthetic Benchmarks like: </br>
[Amiga Sysinfo 4.x](https://sysinfo.d0.se/) & [xSysinfo](http://aminet.net/package/util/moni/xSysInfo) Benchmarks give very Large [Dhrystones](https://en.wikipedia.org/wiki/Dhrystone) "Integer Test" up to 1.5Million on Pi4B, but... </br>
Some SW use more Floating point math [Whetsones](https://en.wikipedia.org/wiki/Whetstone_(benchmark)) like 3D CPU Rendering, </br>
those SW are faster on a Real 030 040 060 with 68882 FPU even Integer benchmark is much slower. </br>
Vampire V4 FPGA Unknown how fast is on a 3D Render Test. </br>
Dhrystones & Whetstone Not only measure Machine Integer & Floating performance, also compiler optimizations "cheating", </br>
depends how was [compiled](https://github.com/Keith-S-Thompson/dhrystone/tree/master) from [source](https://github.com/varigit/arm_benchmarks/blob/master/whetstone/whetstone.c).[1](https://www.netlib.org/benchmark/index.html).[2](https://www.netlib.org/benchmark/dhry-c).[3](https://www.netlib.org/benchmark/whetstone.c).[4](https://www.netlib.org/benchmark/whetstonec).[5](http://www.roylongbottom.org.uk/whets.c).[6](https://git.ti.com/cgit/apps/arm_benchmarks/plain/whetstone/whetstone.c) results may vary. </br>
[MIPS test](https://en.wikipedia.org/wiki/Whetstone_(benchmark)#The_first_1_MIPS_minicomputer:_VAX-11/780,_and_VAX_MIPS) was used by DEC to compare different Alpha machines PDP-11, VAX-11, 8800 </br>

## BOM DIY

[Bill.Of.Materials](https://docs.google.com/spreadsheets/d/1czsNg6O3RXiB12KduvjW-nOGRPwfiWtYTnK7Xi-feMI/edit?gid=0#gid=0).[amybay](https://www.amibay.com/threads/a4000t-rev-4-4-1-part-locators-if-you-need-the-links.120082/) </br>
Component Locator: </br>
[Main Board](https://locator.reamiga.info/locator.php?project=A4000T) </br>
[Main Board Site2](https://www.amiga4000tower.de/smf/pms/a4tlocator5.php) </br>
[Daughter Boards site1](https://locator.reamiga.info/locator.php?project=A4000T-DBs) </br>
[Daughter Boards site2](https://www.amiga4000tower.de/smf/pmsa/a4tlocator5a.php) </br>
[Site3](http://amigapcb.org/) </br>

[Schematics](https://web.archive.org/web/20241118204624/https://sites.google.com/site/tbtorro/) </br>
6 layer boards identical in functionality to the A4000T Rev 4 motherboard PCB </br>
[SCH Site2](https://www.amiga4000tower.de/smf/index.php?action=articles;sa=view;article=36) </br>
[Vector SCH](https://www.amigawiki.de/doku.php?id=en:service:schematics) </br>

## Programming 

for AmigaOS & Workbench | Amiga "DOS" & "Windows" </br>
there are different compilers for C, C++, Asembler & other languajes, </br>
Amiga Assembler compiler, </br>
Lattice C was advertized as a Cross-Compiler + Native Compiler </br>
lattest Native version for Amiga was v5.x </br>
some Developers used Faster machines like IBM System/xx mainframes "room size" MVS / Miniframes "refrigerator size" VMS, Unix, </br>
maybe DEC PDP-11 & VAX-11, 8800 </br>
to compile Amiga software, some machines were runing upto 300MHz while Amiga 1000 & 500 were 8MHz. </br>
similar did Microsoft when designing DOS & Windows with Emulated / Virtualized x86 </br>
using faster machines "Server" to compile software for Consumer / Home / Office machines, </br> 
running emulations/VM's is still a common practice. </br>
Most Notorious modern example is Windows8.1 Update, that works Ok on VirtualBox 6.x, </br>
but does Not update on a Real X58 Machine, unless 3 Service Packs are manually downloaded & installed. </br>

Apollo-Core has [Programming Tutorials](http://www.apollo-core.com/index.htm?page=coding&tl=1) for their Vampire V4 68K 080 CPU & SuperAGA FPGA. </br>

Lattice C was purchased by Microsoft, Renamed Microsoft C Compiler 1.0 & 2.0 after version 3 code was re-written, Unknown if v3 Cross-compile. </br>
Other Native 68k compilers for Amiga: Aztek C, SBS </br>
posix Linux gcc tools port to Amiga called GeekGadgets v1 v1.5 v2. </br>
Amiga Developer CD v1.1 v2.1 </br>
Devpac for Amiga </br>
Smaller / independent developers without access to University MainFrames MVS/VMS had to compile Native. </br>

### Examples: 

[OUTRUN (1986)](https://en.wikipedia.org/wiki/OutRun) for AMIGA 1200 / 4000 AGA Chipset: 
[Part1](https://www.youtube.com/watch?v=5PpR-Dm3-nU), [Part2](https://www.youtube.com/watch?v=I-QAhxMhb5Q) & [Updates](https://www.youtube.com/@reassembler68k/search?query=OUTRUN%20amiga) -> [Blog & Source Files](https://reassembler68k.itch.io/outrun-amiga-edition/devlog/1029155/the-making-of-outrun-chapter-1-the-long-road) </br>
[Original ROM's](https://www.myabandonware.com/game/outrun-q6#download) </br>
[MAME C++ SRC](https://github.com/mamedev/mame/blob/master/src/mame/sega/segaorun.cpp) </br>

similar: 
[Power Drift (1988)](https://en.wikipedia.org/wiki/Power_Drift) </br>
[Original ROM's](https://www.myabandonware.com/game/power-drift-ze#download) </br>

## Mouse & Joystick DB9
The Original Amiga "Tank Mouse", had different revisions 1351, and No name, </br>
Made in Japan and Malaysia, </br>
some claim some mouse were "analog" and others "digital", but the reality, is that  </br>
all are "almost the same design" with minor changes </br>
the original buttons were a "DIY" metalic dome that made contact with the PCB. </br>
those "DIY" push switches were replaced with common push micro switches. </br>
The circuit design is "the same" based on a Quad comparator. </br>
but Early Designs had IR LEDs that Drift with Age / Time / Use / Temperature </br>
and the original pull-down resistors for the output of the IR Receiver LED were calculated too low. </br>
Resistor values should be near 880K-1K ohm. </br>
Newer designs 1352 & No name made other physical changes to the mouse ball door, </br>
older had a vertical snap on design, the later had a rotary design. </br>

with a few modifications all revisions with different countries of origin, cold be "the same" </br>

There are [Modern / New Recreations](https://tank-mouse.com/) also DIY Resin 3D Print models. </br>
IF you like the Original Tank mouse model / design. </br>
Amiga and other 3rd party manufacturers released compatible models, depends on the pin-out of the DB9 connector. </br>
AtariST "Tank Mouse" bottom part was "very similar" to Early Amiga "Tank Mouse" bottom plastic part, </br>
PCB circuit also similar, but has a different manufacturer. </br>
To recreate that PCB design is very simple, the only problem would be the Giant Metallic Ball Bearing covered in micro rugerized rubber. </br> 
similar to PlayStation5 controllers, have micro PlayStation Logos /\ [_] (O) texture. </br>
Some Chinese Balls that sound like "Triangles inside", could work but size could be different, </br>
because the weight does Not seem a Solid Metallic / Iron / Steinless Steel Ball Bearing. </br> 

There were other Mouse Designs, but Tank Mouse was the most common. </br>
