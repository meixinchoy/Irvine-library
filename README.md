# Irvine-library
Irvine library for assembly language. Posting it here since the Irvine website is not working anymore (as of aug 2020)

# EDIT: the website works now. please see: https://www.asmirvine.com/

Configuration for MASM Visual Studios project and Irvine32
-------------------------------------------------------------
1.  extract the zip file to your C drive
2.  Create C++ empty project.
3.  Right-click project file name - Build dependencies - build customization- Check masm
4.  Right-click project file name- properties\
    Linker-General : Additional directory libraries - c:\Irvine\
    Linker-Input: Additional dependencies: Irvine32.lib;\
    Linker-System: Subsystem - Console\
5.  Add item, C++ file, name it as main.asm.	
6.  Include Path c:\Irvine for ASM file:   properties- Microsoft Macro Assembler-General: Include Paths - c:\Irvine\




Credits:
--------

I do not own this library. all credits goes to the author:

Assembly Language for x86 Processors, Sixth Edition.

by  KIP R. IRVINE Florida International University School of Computing and Information Sciences
