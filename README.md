# gstm

source: http://sourceforge.net/projects/gstm/

patched to compile and work on Fedora 21


Turned out that ./configure will overwrite the Makefile

so a note here

after run ./configure
modify the Makefile 
INTLLIBS = 
to 
INTLLIBS = -lxml2 -lX11
