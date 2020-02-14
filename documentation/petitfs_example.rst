Introduction
============

This example provides a base for using the Petit FAT File System library with ATtiny817. 
It provides the library files and a simple SD card interfacing example using the library.
It is not meant to be a standalone demo.


Related documents / Application notes
-------------------------------------

- AVR42776 Using the Petit FAT File System Module with AVR
- AVR42780 Temperature logger with ATtiny817 and SD Card

Supported evaluation kits
-------------------------

- ATtiny817 Xplained Mini
- ATtiny817 Xplained Pro

Using this example
------------------

1. Press Download Pack and save the .atzip file.
2. Import .atzip file into Atmel Studio 7, File->Import->Atmel Start Project.
3. Go to Project->temp_logger Properties (or Alt-F7). 
4. Under Toolchain->AVR/GNU C Compiler->Symbols->Defined Symbols click Add Item, enter the text 'F_CPU=5000000' (without inverted commas) and click OK.
5. Build the project and ensure there are no errors (disregard the left shift count warning).
6. Examine the memory usage of each component in the library by going to View->ELF Symbol Sizes.
7. Implement your application with the Petit FAT File System library included.

