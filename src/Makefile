all: shared

CFLAGS :=`pkg-config libusb-1.0 --libs`

shared:
	gcc main.c -o sample $(CFLAGS)


.PHONY: all
