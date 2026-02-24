# flopbook
A simple plaintext ebook manager for Floppinux
## Usage
./flopbook command

Commands:

help: Display this help page.

create: Create a plaintext ebook in Flopbook's home directory.

import: Import a plaintext ebook into Flopbook' home directory.

list: List the books within Flopbook's home directory.

mkhtml: Create a single page HTML version of a specified book.
### Notes
* On Floppinux only, there is no need to "chmod +x" the Flopbook script.
* If you have mounted a second floppy within Floppinux, change the FBHOME variable to point to a "fbook" subdirectory within the floppy's mount point.
* Flopbook works on practically any Linux distribution.
