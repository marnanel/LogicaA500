This is the contents of the hard disk of an Archimedes A500 belonging to Logica
in the 1980s. It's a copy of `LogicaA500 Host FS zip` on
[the Domesday86 site](https://www.domesday86.com/?page_id=936).
The extraction was done by Ian Stocks. Major kudos.

Where you have two subdirectories `B` and `C`, `B` will contain BCPL source
and `C` will contain the compiled images of that source.

The Archimedes filesystem was not case-sensitive.
The [RISC OS character
encoding](https://en.wikipedia.org/wiki/RISC_OS_character_set)
is a bit like ISO 8859-1, but has its quirks.

| dirname   | what's in it
| -------   | ------------
| ARC/BASIC | no source code
| ARC/CF    | community find
| ARC/CM    | community map
| ARC/CO    | community overlay
| ARC/CP    | community photo
| ARC/CT    | ctext, and also aatext: builds overlay
| ARC/DH    | data handler
| ARC/GH    | globals header
| ARC/GHDRS | globals headers; same code as GH, later revision
| ARC/H     | community headers
| ARC/HDRS  | community headers; same code as H, later revision
| ARC/HE    | help
| ARC/KE    | kernel
| ARC/l     | no source code
| ARC/na    | national area
| ARC/nc    | national chart
| ARC/ne    | national essay
| ARC/nf    | national find
| ARC/NM    | national maps
| ARC/NN    | also national maps; the files in here claim to be in NM instead
| ARC/np    | national photo
| ARC/nt    | national contents (but why?)
| ARC/nv    | national video
| ARC/nw    | national walk
| ARC/R     | only test stuff
| ARC/sc    | system charts (graphics library)
| ARC/si    | system inits (for most of the other directories)
| ARC/ut    | utilities (part 1)
| ARC/utils | utilities (part 2)
| ARC/vh    | video handler
| ARC/view  | just a string table
