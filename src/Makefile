CC?=gcc
CFLAGS?=-Wall -g -O2
TARGETS=niagara
#LIBS=

UNAME := $(shell uname)

all::	$(TARGETS) $(LIBS)

niagara: niagara.c $(LIBS)
	$(CC) -o niagara niagara.c $(LIBS) $(CFLAGS)

clean:
	rm -f *~ *.o $(TARGETS)
