For static linking, add libc.a to the src/ dir, then edit src/Makefile (not ./Makefile):
```
LIBS		= -lpcre -lncurses  -l:libc.a
```
But how can I do this on Windows? (on Mac, you can't)
Also the apt update is linux specific.

### Original
```
This is CCZE, a fast log colorizer written in C, intended to be a
drop-in replacement for colorize (http://colorize.raszi.hu).

See the NEWS file for a description of recent changes to CCZE.

See the file INSTALL for instructions on how to build and install the
CCZE data and program files. See the CCZE manual for details about
configuration. Type "man ccze" in the shell prompt.

Please visit the official CCZE web page for more information. The URL
is http://bonehunter.rulez.org/CCZE.html.
```
