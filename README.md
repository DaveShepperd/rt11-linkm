# rt11-linkm

These are the RT11 source versions 6.08 and 6.10 of the game code linker LINKM used by the Atari engineers from late 1976 until around 1984 or 1985.

Use whatever tool you have at your disposal (see the repository rtpip here) to copy one of these files (name it LINKM.MAC in the process) to an RT11 container file,
run RT11 from SIMH and I think it can be built with:

MACRO LINKM
LINK LINKM

You do not want to build it with the symbol $VAX being set to any value other than 0.

Good luck.
