# AdLib sound replacement for TempleOS/TinkerOS/ZealOS

This may just work for some VMware users.  For older version of QEMU use `-soundhw adlib` for newer versions use `-audiodev alsa,id=snd0 -device adlib,audiodev=snd0` substituting alsa for your desired sound backend as appropriate.

Then put Midi.HH and OPL2.HC/ZC in the same directory and run `#include "OPL2"`

