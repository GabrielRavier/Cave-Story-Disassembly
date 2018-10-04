# Cave-Story-Decompilation
Decompilation of Cave Story. Can be opened with IDA Pro (freeware and pro version).

This decompilation aims to make the code easily understandable.

Also, this repo is basically dead, the recompilation is being done at https://github.com/GabrielRavier/CaveStoryRemake.

Get IDA Freeware here : https://www.hex-rays.com/products/ida/support/download_freeware.shtml

PS : You do not need the original .exe file to open the idb files.

DISCLAIMER: Any and all content presented in this repository is presented for informational and educational purposes only. Commercial usage is expressly prohibited. I claim no ownership of any code in these repositories. You assume any and all responsibility for using this content responsibly. I claim no responsibiliy or warranty.

File details :

Doukutsu.i64 : This file is the IDA database to open using IDA 7.0 freeware. This file will be updated as some point, but only the .idb file is up to date due to conversion being difficult.

Doukutsu.idb : This file is the IDA database to open using the 32-bit version of IDA.

All further files were produced by IDA :

Doukutsu Typeinfo.idc : As indicated, this file contains the typeinfo of the .i64 in the idc scripting language. For some reason, I can't get IDA to produce it, so it's not up to date.

Doukustu.idc : This file contains the entire database, dumped to the idc format. If you want, you can manually open the .exe file, then run the idc file in IDA, though the results might not look good (I did this for conversion to .i64 format). For some reason, I can't get IDA to produce it, so it's not up to date.

Doukustu.asm : This file contains the disassembly done by IDA, in a possibly re-assemblable format (might have problems)

Doukustu.c : This file contains the de-compilation done by the Hex-Rays plugin. It might possibly be re-compilable, but don't get your hopes up.

Doukustu.dif : This is a dummy file, to indicate the fact that there is no differences between the assembly contained in the .i64 file and the machine code contained in the .exe.

Doukutsu.h : This is a C header file, which contains structs information.

Doukutsu.inc : This file contains struct information in a format used by assemblers.

Doukustu.lst : This file (a listing file containing the assembly code and offsets) is probably the most useful to people who do not want to bother with installing IDA.

Doukutsu.map : This file contains information about function offsets.

Doukutsu_All.map : This file contains offsets for EVERY LABEL in the program.
