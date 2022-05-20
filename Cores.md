System: Amstrad - CPC

PAK Name: CPC.pak

Core: CrocoDS `crocods_libretro.so`

ROM Folder: Amstrad - CPC (CPC)

ROM Extensions: ???

Bios: None




Important Notes: 

All bios files go into the BIOS folder located on the root of your SD unless specifically stated otherwise in the emulators list below. Bios file names and extensions are case sensitive!

Fully support cores are highlighted in :heavy_check_mark: BOLD. Experimental cores are not highlighted and are hidden behind "Expert View”. 

Emulators:

:warning: 3DO

- Emulator: lr-opera
- Rom Folder: PANASONIC
- Extensions: .iso .ISO .bin .BIN .chd .CHD .cue .CUE
- Bios: panafz1.bin or panafz10.bin or panafz10-norsa.bin or panafz10e-anvil.bin or panafz10e-anvil-norsa.bin or panafz1j.bin or panafz1j-norsa.bin or goldstar.bin or sanyotry.bin or 3do\_arcade\_saot.bin See this link for more details. <https://docs.libretro.com/library/opera/#bios>
- Notes: This will never run full speed!

:warning: Amiga

- Emulator: lr-puae, lr-uae4arm
- Rom Folder: AMIGA
- Extensions: .adf .ADF .hdf .HDF .lha .LHA .zip .ZIP
- Bios: kick33180.A500 and kick34005.A500 and kick40068.A1200 See this link for more details. <https://github.com/midwan/amiberry/wiki/Kickstart-ROMs-(BIOS)>


:warning: Amiga CD32

- Emulator: lr-uae4arm
- Rom Folder: AMIGACD
- Extensions: .cue .CUE .ccd .CCD .lha .LHA .nrg .NRG .mds .MDS .iso .ISO .m3u .M3U .chd .CHD
- Bios: kick33180.A500 and kick34005.A500 and kick40068.A1200 See this link for more details. [https://github.com/midwan/amiberry/wiki/Kickstart-ROMs-(BIOS)](https://github.com/midwan/amiberry/wiki/Kickstart-ROMs-(BIOS))


| System | PAK name | Core | Default ROM Folder | ROM Extensions | Requires BIOS? |
| ------ | ---------| ---- | ------------------ | -------------- |--------------- |
| Amstrad - CPC | CPC.pak | CrocoDS `crocods_libretro.so` | Amstrad - CPC (CPC) | ??? | No |
| Arcade - Capcom Play System 1 | CPS1.pak | FB Alpha 2012 CPS-1 `fbalpha2012_cps1_libretro.so` | Arcade - Capcom Play System 1 (CPS1) | ??? | No |
| Arcade - Capcom Play System 2 | CPS2.pak | FB Alpha 2012 CPS-2 `fbalpha2012_cps2_libretro.so` | Arcade - Capcom Play System 2 (CPS1) | ??? | No |
| Arcade - Capcom Play System 3 | CPS3.pak | FB Alpha 2012 CPS-3 `fbalpha2012_cps3_libretro.so` | Arcade - Capcom Play System 3 (CPS1) | ??? | No |
| Arcade - FinalBurn Alpha | FBA.pak | FB Alpha `fbalpha_libretro.so` | Arcade - FinalBurn Alpha (FBA)  | ??? | neogeo.zip |
| Arcade - MAME 2003+ | ARCADE.pak | MAME 2003-Plus `mame2003_plus_libretro.so` | Arcade - MAME 2003+ (ARCADE) | ??? | No |
| Atari - 2600 | ATARI.pak | Stella 2014 `stella2014_libretro.so` | Atari - 2600 (ATARI) | ??? |  |
| Atari - 5200 | FIFTYTWOHUNDRED.pak | a5200 `a5200_libretro.so` | Atari - 5200 (FIFTYTWOHUNDRED) | ??? | 5200.rom  |
| Atari - 7800 | SEVENTYEIGHTHUNDRED.pak | ProSystem `prosystem_libretro.so` | Atari - 7800 (SEVENTYEIGHTHUNDRED) | ??? | 7800 BIOS (E).rom, 7800 BIOS (U).rom |
| Atari - Lynx | LYNX.pak | Handy `handy_libretro.so` | Atari - Lynx (LYNX)  | ??? | lynxboot.img |
| Bandai - WonderSwan | WS.pak | Beetle WonderSwan `mednafen_wswan_libretro.so` | Bandai - WonderSwan (WS) | ??? | No |
| Bandai - WonderSwan Color | WSC.pak | Beetle WonderSwan `mednafen_wswan_libretro.so` | Bandai - WonderSwan Color (WSC) | ??? | No |
| Coleco - ColecoVision | COLECO.pak | blueMSX `bluemsx_libretro.so` | Coleco - ColecoVision (COLECO)  | ??? | colecovision.rom |
| Commodore - Amiga | AMIGA.pak | PUAE `puae_libretro.so` | Commodore - Amiga (AMIGA) | ???  | kick34005.A500, kick40063.A600, kick40068.A1200 |
| Doom | DOOM.pak | PrBoom `prboom_libretro.so` | Doom (DOOM) | ??? | prboom.wad |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |







:heavy_check_mark: Arcade

- Emulator: :heavy_check_mark: lr-mame2003plus, lr-fbalpha2012, lr-fbneo, lr-mame2003, lr-mame2000
- Mame required rom set version: MAME 0.78 (aka 2003plus reference set) - Required ROM Version: FBAlpha v0.2.97.29  (v0.2.97.40, v0.2.97.42, v0.2.97.43 and v0.2.97.44 may work as well). 
- Rom Folder: ARCADE (or MAME2000, MAME2003, MAME2003PLUS, FBNEO, FBALPHA)
- Extensions: .zip .ZIP .7z .7Z .cue .CUE
- Bios: pgm.zip (for PGM games only like Knights of Valour and DoDonPachi)
- To obtain the best results, search for a rom compatible with Mame2003+

:warning: Atari 800

- Emulator: lr-atari800
- Rom Folder: EIGHTHUNDRED
- Extensions: .atr .ATR .zip .ZIP .7z .7Z
- Bios: ATARIOSA.ROM and ATARIOSB.ROM and ATARIBAS.ROM

:heavy_check_mark: Atari 2600

- Emulator: :heavy_check_mark: lr-stella2014
- Rom Folder: ATARI
- Extensions: .a26 .A26 .bin .BIN .zip .ZIP .7z .7Z
- Bios: None

:warning: Atari 5200

- Emulator: lr-atari800
- Rom Folder: FIFTYTWOHUNDRED
- Extensions: .a52 .A52 .zip .ZIP .7z .7Z .Bin
- Bios: 5200.rom and ATARIBAS.ROM

:heavy_check_mark: Atari 7800

- Emulator: :heavy_check_mark: lr-prosystem
- Rom Folder: SEVENTYEIGHTHUNDRED
- Extensions: .a78 .A78 .zip .ZIP
- Bios: 7800 BIOS (U).rom

:heavy_check_mark: Atari Lynx

- Emulator: :heavy_check_mark: lr-handy, lr-mednafen\_lynx
- Rom Folder: ATARILYNX
- Extensions: .lnx .LNX .zip .ZIP
- Bios: lynxboot.img 

:heavy_check_mark: Atari ST/STE/TT/Falcon

- Emulator: :heavy_check_mark: hatari
- Rom Folder: ATARIST
- Extensions: .st .msa .zip .stx .dim .ipf
- Bios: tos.img 
_The plain ST mode only works with TOS 1.00, 1.02, 1.04, or 2.06. STE mode requires any of the TOS versions 1.xx or 2.xx. TOS 3.0x is for TT, and TOS 4.0x is for Falcon._

:warning: Cannonball (Outrun Port)

- Emulator: lr-cannonball
- Rom Folder: CANNONBALL
- Instructions: Add the OutRun Revision B ROMs into /roms/ports/cannonball/gamedata folder then launch the top file on the list.
- Notes: Thanks to djyt for creating the engine for this OutRun arcade game and thanks to Libretro for adding this as a retroarch core.

:heavy_check_mark: Colecovision

- Emulator: :heavy_check_mark: lr-bluemsx
- Rom Folder: COLECO
- Extensions: .rom .ROM .ri .RI .mx1 .MX1 .mx2 .MX2 .col .COL .dsk .DSK .cas .CAS .sg .SG .sc .SC .m3u .M3U .zip .ZIP .7z .7Z
- Bios: coleco.rom (Verified working MD5:2C66F5911E5B42B8EBE113403548EEE7)
- Notes: The blueMSX core requires the 'Databases' and 'Machines' folders from a full installation of blueMSX. These are included by default. Ensure “Machine Type” is set to Colecovision and “Mapper Type” is set to Auto.

:warning: Commodore 64/VIC-20/PET

- Emulator: lr-vice\_x64
- Rom Folder: COMMODORE
- Extensons: .d64 .D64 .zip .ZIP .7z .7Z .t64 .T64 .crt .CRT .prg .PRG .nib .NIB .tap .TAP
- Bios: None

:heavy_check_mark: CPS 1

- Emulator: :heavy_check_mark: fbalpha2012
- Required ROM Version: FBAlpha v0.2.97.29  (v0.2.97.40, v0.2.97.42, v0.2.97.43 and v0.2.97.44 may work as well). 
- Rom Folder: CPS1
- Extensions: .zip .ZIP .7z .7Z .cue .CUE
- Bios: None

:heavy_check_mark: CPS 2

- Emulator: :heavy_check_mark: fbalpha2012
- Required ROM Version: FBAlpha v0.2.97.29  (v0.2.97.40, v0.2.97.42, v0.2.97.43 and v0.2.97.44 may work as well). 
- Rom Folder: CPS2
- Extensions: .zip .ZIP .7z .7Z .cue .CUE
- Bios: None

:heavy_check_mark: CPS 3

- Emulator: :heavy_check_mark: fbalpha2012
- Required ROM Version: FBAlpha v0.2.97.29  (v0.2.97.40, v0.2.97.42, v0.2.97.43 and v0.2.97.44 may work as well). 
- Rom Folder: CPS3
- Extensions: .zip .ZIP .7z .7Z .cue .CUE
- Bios: None

:heavy_check_mark: Daphne
- Emulator: :heavy_check_mark: daphne_libretro.so
- Rom Folder: DAPHNE
https://github.com/libretro/daphne

:heavy_check_mark: Doom

- Emulator: lr-prboom
- Rom Folder: PRBOOM
- Extensions: .wad .WAD .sh .SH .doom .Doom
- Bios: None
- An amazing experience on the Miyoo Mini at a solid 60fps.

:warning: Dreamcast VMU

- Emulator: lr-vemulator
- Rom Folder: VMU
- Extensions: .vms .VMS .bin .BIN
- Bios: None

:warning: EasyRPG

- Emulator: lr-easyrpg
- Rom Folder: EASYRPG
- Extensions: .easyrpg .EASYRPG .zip .ZIP
- Bios: None
- Notes: Games must have a RPG\_RT.ini and RPG\_RT.ldb inside their respective folders.

:heavy_check_mark: Fairchild Channel F

- Emulator: :heavy_check_mark: lr-freechaf
- Rom Folder: FAIRCHILD
- Extensions: .bin .BIN .rom .ROM .chf .CHF .zip .ZIP
- Bios: sl31253.bin and sl31254.bin and sl90025.bin

:heavy_check_mark: Famicom Disk System

- Emulator: :heavy_check_mark: lr-fceumm
- Rom Folder: FDS
- Extensions: .nes .NES .unif .UNIF .unf .UNF .fds .FDS .zip .ZIP .7z .7Z
- Bios: disksys.rom

:heavy_check_mark: Game and Watch

- Emulator: :heavy_check_mark: lr-gw
- Rom Folder: GW
- Extensions: .mgw .MGW
- Bios: None

:heavy_check_mark: Game Boy

- Emulator: :heavy_check_mark: lr-gambatte, lr-gearboy, lr-tgbdual
- Rom Folder: GB, GBHACKS
- Extensions: .gb .GB .gbc .GBC .dmg .DMG .zip .ZIP .7z .7Z
- Bios: gb\_bios.bin (optional)

:heavy_check_mark: Game Boy Advance

- Emulator: :heavy_check_mark: lr-gpsp, lr-mgba, lr-meteor, lr-mednafen-gba, lr-vba\_next
- Rom Folder: GBA, GBAHACKS
- Extensions: .gb .GB .gbc .GBC .gba .GBA .zip .ZIP .7z .7Z
- Bios: gba\_bios.bin (required for lr-gpsp, optional for other cores), gb\_bios.bin (optional), gbc\_bios.bin (optional), sgb\_bios.bin (optional)

:heavy_check_mark: Game Boy Color

- Emulator: :heavy_check_mark: lr-gambatte, lr-gearboy, lr-tgbdual
- Rom Folder: GBC, GBHACKS
- Extensions: .gb .GB .gbc .GBC .dmg .DMG .zip .ZIP .7z .7Z
- Bios: gbc\_bios.bin (optional)

:heavy_check_mark: Game Gear

- Emulator: :heavy_check_mark: lr-picodrive, lr-genesis\_plus\_gx, lr-gearsystem
- Rom Folder: GG
- Extensions: .bin .BIN .gg .GG .zip .ZIP .7z .7Z
- Bios: bios.gg (optional)

:heavy_check_mark: Genesis/Megadrive

- Emulator: :heavy_check_mark: lr-picodrive, lr-genesis\_plus\_gx
- Rom Folder: MD, MDHACKS
- Extensions: .68k .68K .mdx .MDX .md .MD .sgd .SGD .smd .SMD .gen .GEN .bin .BIN .zip .ZIP .7z .7Z
- Bios: bios\_MD.bin (optional)

:heavy_check_mark: Intellivision

- Emulator: :heavy_check_mark: lr-freeintv
- Rom Folder: INTELLIVISION
- Extensions: .bin .BIN .int .INT .zip .ZIP .7z .7Z
- Bios: exec.bin, grom.bin

:heavy_check_mark: Jaguar

- Emulator: :heavy_check_mark: Virtual Jaguar
- Rom Folder: JAGUAR
- Extensions: .j64 .jag .rom .abs .cof .bin .prg
- Bios: virtualjaguar_bios
(Slow to emulate)

:heavy_check_mark: Master System

- Emulator: :heavy_check_mark: lr-picodrive, lr-genesis\_plus\_gx, lr-gearsystem
- Rom Folder: MS
- Extensions: .7z .bin .sms .zip
- Bios: bios\_E.sms (optional), bios\_U.sms (optional), bios\_J.sms (optional)

:heavy_check_mark: Mega Duck

- Emulator: :heavy_check_mark: lr-sameduck
- Rom Folder: MEGADUCK
- Extensions: .bin .BIN .zip .ZIP .7z .7Z
- Bios: None

:heavy_check_mark: MSX/MSX2

- Emulator: :heavy_check_mark: lr-bluemsx
- Rom Folder: MSX
- Extensions: .cas .CAS .dsk .DSK .mx1 .MX1 .mx2 .MX2 .rom .ROM .zip .ZIP .7z .7Z
- Notes: The blueMSX core requires the 'Databases' and 'Machines' folders from a full installation of blueMSX. These are included by default.

:heavy_check_mark: Neo Geo

- Emulator: :heavy_check_mark: lr-fbalpha2012
- Required ROM Version: FBAlpha v0.2.97.29  (v0.2.97.40, v0.2.97.42, v0.2.97.43 and v0.2.97.44 may work as well). 
- Rom Folder: NEOGEO
- Extensions: .zip
- Bios: neogeo.zip
- Notes: Because neogeo roms can come in different formats (split or non-merged), it's recommended to keep the neogeo.zip bios in the /BIOS folder and the /Roms/NEOGEO folder to ensure best compatibility.

:heavy_check_mark: Neo Geo CD

- Emulator: :heavy_check_mark: lr-neocd
- Rom Folder: NEOCD
- Extensions: .cue .CUE .chd .CHD .m3u .M3U
- Bios: (000-lo.lo or ng-lo.rom) and (neocd\_f.rom or neocd.bin or uni-bioscd.rom) placed in a folder named neocd within the bios folder

:heavy_check_mark: Neo Geo Pocket/Neo Geo Pocket Color

- Emulator: :heavy_check_mark: lr-mednafen-ngp
- Rom Folder: NGP
- Extensions: .ngp .NGP .ngc .NGC .zip .ZIP .7z .7Z
- Bios: None

:heavy_check_mark: Nintendo Entertainment System (NES)/Famicom

- Emulator: :heavy_check_mark: lr-fceumm,lr-nestopia, lr-quicknes
- Rom Folder: FC
- Extensions: .nes .NES .zip .ZIP .7z .7Z
- Bios: None

:heavy_check_mark: Odyssey2

- Emulator: :heavy_check_mark: lr-o2em
- Rom Folder: ODYSSEY
- Extensions: .bin .BIN
- Bios: o2rom.bin

:warning: OpenBOR

- Emulator: OpenBOR Standalone
- Rom Folder: /RApp/OpenBOR/paks
- Extensions: .pak .PAK
- Bios: none

:warning: PC98

- Emulator: quasi88
- Rom Folder: PCNINETYEIGHT
- Extensions: .d88 .D88 .fdi .FDI .hdi .HDI .zip .ZIP
- Bios: None

:warning: PC98

- Emulator: lr-nekop2
- Rom Folder: PCNINETYEIGHT
- Extensions: .d88 .D88 .fdi .FDI .hdi .HDI .zip .ZIP
- Bios: See this link for more details. [https://docs.libretro.com/library/neko_project_ii_kai/#bios](https://docs.libretro.com/library/neko_project_ii_kai/#bios)

:heavy_check_mark: PC

- Emulator: :heavy_check_mark: lr-dosbox\_pure
- Rom Folder: DOS
- Extensions: .dosz .DOSZ
- Bios: None

:heavy_check_mark: PC Engine/TurboGraphx-16

- Emulator: :heavy_check_mark: lr-mednafen-pce-fast
- Rom Folder: PCE
- Extensions: .pce .PCE .chd .CHD .zip .ZIP .7z .7Z
- Bios: None

:heavy_check_mark: PC Engine CD/TurboGraphx CD

- Emulator: :heavy_check_mark: lr-mednafen-pce-fast
- Rom Folder: PCECD
- Extensions: .pce .PCE .ccd .CCD .iso .ISO .img .IMG .chd .CHD .cue .CUE .chd .CHD
- Bios: syscard3.pce

:warning: PC-FX

- Emulator: lr-mednafen-pcfx
- Rom Folder: PCFX
- Extensions: .chd .CHD .zip .ZIP .cue .CUE .ccd .CCD .toc .TOC
- Bios: pcfx.rom

:heavy_check_mark: Pico-8

- Emulator: :heavy_check_mark: fake-08
- Rom Folder: PICO
- Extensions: .p8 .P8 (NOT .png!)
- Bios: None
- Notes: Compatibility is improving, but not perfect. 

:heavy_check_mark: Philips Videopac

- Emulator: :heavy_check_mark: lr-o2em
- Rom Folder: VIDEOPAC
- Extensions: .rom, .bin
- Bios: o2rom.bin, g7400.bin (maybe, c52.bin & jopac.bin)
- Notes: Games made for 7000 and 7200 machines require bios files.


:heavy_check_mark: Playstation 1 (PSX)

- Emulator: :heavy_check_mark: lr-pcsx-rearmed
- Rom Folder: PS
- Extensions: .cue .CUE .img .IMG .mdf .MDF .pbp .PBP .toc .TOC .cbn .CBN .m3u .M3U .ccd .CCD .chd .CHD .zip .ZIP .7z .7Z .iso .ISO
- Bios: psxonpsp660.bin, scph101.bin, scph7001.bin, scph5501.bin, scph1001.bin
- Note: Rewind and Fast Forward capability should be disabled while playing PSX. Performance may suffer greatly otherwise. It's been reported best performance is achieved using the psxonpsp660.bin bios. Certain games (ex. Looney Tunes Sheep Rider, Jedi Power Battles and 2xtreme/espn extreme games) need to have SMC Checks disabled or games will eventually slow down and crash in the pcsx-rearmed core. Retroarch Quick Menu > Options > (Speed Hack) Disable SMC check.

:heavy_check_mark: Pokemon Mini

- Emulator: :heavy_check_mark: lr-pokemini
- Rom Folder: POKE
- Extensions: .min .MIN .zip .ZIP
- Bios: bios.min (optional)

:heavy_check_mark: Satellaview

- Emulator: :heavy_check_mark: lr-snes9x
- Rom Folder: SATELLAVIEW
- Extensions: .bs .BS .sfc .SFC .smc .SMC .zip .ZIP .7z .7Z
- Bios: BS-X.bin

:heavy_check_mark: ScummVM

- Emulator: :heavy_check_mark: lr-scummvm
- Rom Folder: SCUMMVM
- Extensions: Unzipped ScummVM folders

:heavy_check_mark: Sega 32X

- Emulator: :heavy_check_mark: lr-picodrive
- Rom Folder: THIRTYTWOX
- Extensions: .32x .32X .7z .7Z .bin .BIN .md .MD .smd .SMD .zip .ZIP
- Bios: None

:heavy_check_mark: Sega CD

- Emulator: :heavy_check_mark: lr-picodrive, lr-genesis\_plus\_gx
- Rom Folder: SEGACD
- Extensions: .bin .BIN .chd .CHD .cue .CUE .iso .ISO
- Bios: bios\_CD\_U.bin, bios\_CD\_E.bin, bios\_CD\_J.bin

:warning: Sega Saturn

- Emulator: lr-mednafen-saturn
- Rom Folder: SATURN
- Extensions: .img .IMG .cue .CUE .chd .CHD .iso .ISO .m3u .M3U
- Bios: saturn\_bios.bin (Optional)
- Note: This will never run full speed!

:heavy_check_mark: SG 1000

- Emulator: :heavy_check_mark: lr-picodrive
- Rom Folder: SEGASGONE
- Extensions: .7z .7Z .bin .BIN .sg .SG .zip .ZIP
- Bios: None

:warning: Sharp X1

- Emulator: lr-x1
- Rom Folder: XONE
- Extensions: .dx1 .DX1 .zip .ZIP .2d .2D .2hd .2HD .tfd .TFD .d88 .D88 .88d .88D .hdm .HDM .xdf .XDF .dup .DUP .cmd .CMD
- Bios: IPLROM.X1, IPLROM.X1T (need to be placed in a folder named xmil within the bios folder)

:warning: Sharp X68000

- Emulator: lr-px68k
- Rom Folder: SHARP
- Extensions: .dim .DIM .m3u .M3U
- Bios: iplrom.dat, cgrom.dat, iplrom30.dat (optional), iplromco.dat (optional), iplromxv.dat (optional) (need to be placed in a folder named keropi within the bios folder)

:heavy_check_mark: SuFami Turbo

- Emulator: :heavy_check_mark: lr-snes9x
- Rom Folder: SUFAMI
- Extensions: .smc .SMC .zip .ZIP .7z .7Z
- Bios: STBIOS.bin
- Notes: For multi-cart Sufami Turbo games, you must first run each game individually to create sram files for them. Then the multi-link will function correctly. See Libretro’s documentation for more info.

:heavy_check_mark: Super Game Boy

- Emulator: :heavy_check_mark: lr-mgba
- Rom Folder: SGB
- Extensions: .gb .GB .gbc .GBC .dmg .DMG .zip .ZIP .7z .7Z
- Bios: sgb\_bios.bin

:heavy_check_mark: Super Grafx

- Emulator: :heavy_check_mark: lr-mednafen-supergrafx
- Rom Folder: SGFX
- Extensions: .pce .PCE .sgx .SGX .cue .CUE .ccd .CCD .chd .CHD .zip .ZIP .7z .7Z
- Bios: syscard3.pce

:heavy_check_mark: Super Nintendo Entertainment System (SNES)/Super Famicom (SFC) -- MSU1 Compatible

- Emulator: :heavy_check_mark: lr-mednafen-supafaust, snes9x_libretro.so, lr-snes9x2005PLUS lr-snes9x2010, lr-snes9x2002, lr-snes9x2005, lr-snes9x2010 
- Rom Folder: SFC
- Extensions: .sfc .SFC .smc .SMC .zip .ZIP .7z .7Z
- Bios: None

:heavy_check_mark: TIC-80

- Emulator: :heavy_check_mark: lr-tic80
- Rom Folder: tic80
- Extensions: .tic .TIC
- Bios: None

:warning: Uzebox

- Emulator: lr-uzem
- Rom Folder: UZEBOX
- Extensions: .uze .UZE
- Bios: None

:heavy_check_mark: Vectrex

- Emulator: :heavy_check_mark: lr-vecx
- Rom Folder: VECTREX
- Extensions: .vec .VEC .zip .ZIP .7z .7Z
- Bios: None

:heavy_check_mark: Virtual Boy

- Emulator: :heavy_check_mark: lr-mednafen-vb
- Rom Folder: VB
- Extensions: .vb .VB .vboy .VBOY .zip .zip .7z .7Z
- Bios: None

:heavy_check_mark: Watara Supervision

- Emulator: :heavy_check_mark: lr-potator
- Rom Folder: SUPERVISION
- Extensions: .bin .BIN .zip .ZIP .7z .7Z
- Bios: None

:heavy_check_mark: Wolfenstein

- Emulator: :heavy_check_mark: lr-ecwolf
- Rom Folder: ECWOLF
- Extensions: See below
- Bios: None
- Notes:
- Copy your Wolfenstein 3D, Spear of Destiny, or Super Noah's Ark 3D dos folder into the wolf rom folder. If while using the Retroarch ecwolf core you find you can't start Wolfenstein, make sure there's only one .exe in the Wolfenstein dos subfolder. Files like catalog.exe should be deleted from this subfolder.

:heavy_check_mark: WonderSwan/WonderSwan Color

- Emulator: :heavy_check_mark: lr-mednafen-wswan
- Rom Folder: WSC
- Extensions: .ws .WS .pc2 .PC2 .zip .ZIP .7z .7Z
- Bios: None

:warning: ZX-81

- Emulator: lr-81
- Rom Folder: ZXEIGHTYONE
- Extensions: .p .P .tzx .TZX .zip .ZIP
- Bios: None
- Notes: I was only able to successfully load .p based roms. I suggest using .p roms and .zip files with .p roms in them based on my testing.
- Many games can be started by hitting select to bring up the virtual keyboard, hit R then newline key. Otherwise, you'll need to search online on how to load these games if you're not familiar with this system.

:heavy_check_mark: ZX Spectrum

- Emulator: :heavy_check_mark: lr-fuse
- Rom Folder: ZXS
- Extensions: .sna .SNA .szx .SZX .z80 .Z80 .tap .TAP .tzx .TZX .gz .GZ .udi .UDI .mgt .MGT .img .IMG .trd .TRD .scl .SCL .dsk .DSK
- Bios: None
