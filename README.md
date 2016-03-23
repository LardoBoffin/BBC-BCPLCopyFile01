# BCPLCopyFile01

Use BCPL to copy a file byte by byte using hardcoded file names

This is a simple example of using BCPL to step through a file a byte at a time in order to copy its contents. Written and tested on BeebEm and a BBC Model B. I have a 6502 second processor attached as it speed sthings up somewhat.

You will need the BCPL ROM present in your BeebEm (can be downloaded from the net) or on your Beeb.

Load BCPLS into disk 0.
Load BCPLT into disk 1 (not used for this example).

Type *BCPL

On drive 0 type "BCPL COPYFL CODE" to build.
This will build into RAM. Type "SAVE CODE" to save it to disk.

Type "CODE" to run the program (it will run from RAM rather than disc as you have built it and placed it in the store).

Once completed it should show two *INFO reports to show the created file is the same size as the original.

