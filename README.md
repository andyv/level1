

This is an annotated disassembly of the TRS-80 Level 1 ROM.

Assumes some knowledge of the Z80 microprocessor.

Level 1 basic is based on the public domain Tiny Basic.  Radio Shack
customized it to the TRS-80, added graphics, cassette data storage and
floating point numbers.

The code consumes 4K of ROM space.  There are numerous places where
compaction techniques have been used, and a several places where a few
more bytes could have been shaved but didn't have to be.

level1.src contains the disassembly, memory.txt is a memory map of the
interpreter's variables.

Created in apprecation for many happy hours.


Andy Vaught
Mesa, Arizona
February 2018

