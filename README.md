# Microblaze processor module for Ghidra

Most of the critical P-CODE functionality implemented and basic very simple gcc programs can be disassembled. 

Only little endian 32bit mode tested. 

This module was inspired by earlier work of Hikaru Harasawa, Xavier McCaig, and Frank Tursi [ghidra-microblaze](https://github.com/KodaSec/ghidra-microblaze), but I took different approach to the decoding be able to support the pcode. Especially the immediate command was not that nice to model. 

