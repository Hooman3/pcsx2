#  _____     ___ ____
#   ____|   |    ____|      PSX2 OpenSource Project
#  |     ___|   |____       (C)2002, David Ryan ( Oobles@hotmail.com )
#  ------------------------------------------------------------------------

IOP_BIN = ../../../build/LOADCORE

IOP_INCS += -I../include

IOP_OBJS = loadcore.o ../iopdebug.o ../iopelf.o ../romdir.o ../libkernel/iop_sysmem.o

all: $(IOP_BIN)

clean:
	rm -f -r $(IOP_OBJS) $(IOP_BIN)

include $(PS2SDK)/Defs.make
include $(PS2SDK)/samples/Makefile.pref
include $(PS2SDK)/samples/Makefile.iopglobal
