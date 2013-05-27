CC?=gcc
CFLAGS?=-Wall -g -O2
TARGETS=inundator
#LIBS=

UNAME := $(shell uname)

all::	$(TARGETS) $(LIBS)

inundator: inundator.c $(LIBS)
	$(CC) -o inundator inundator.c $(LIBS) $(CFLAGS)

clean:
	rm -f *~ *.o $(TARGETS)
