Casey Waltrup
313 
Section 5 2:30-3:45 M/W

Descriptions
  nasm:
    -f elf32: specifies the output format, elf32 is used for 32 bit linux systems
    -g: includes debug information in the output
    -F dwarf: specifies the debugging format
    -o myProgram.o: spcifies the output object file name
    myProgram.asm: the input assembly source file

  ld:
    -m elf_i386: specifies the target architecture, elfi386 is for 32 bit x86
    -o myProgram: specifies the name of the output executable file
    myProgram.o: the input object file to be linked
