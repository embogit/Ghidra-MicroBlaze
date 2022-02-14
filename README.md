# Microblaze processor module for Ghidra

Most of the critical PCODE functionality implemented and basic gcc compiled prorams can be disassembled. 

Only little endian 32bit mode tested. 

This module was inspired by earlier work of Hikaru Harasawa, Xavier McCaig, and Frank Tursi [ghidra-microblaze](https://github.com/KodaSec/ghidra-microblaze), but I took different approach to the decoding be able to support the pcode. Especially the immediate command was not that nice to model. 

BUGS:
There is something wrong with the stack definition, maybe bug in PCODE or in other settings
