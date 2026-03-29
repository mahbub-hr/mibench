CC = gcc
CFLAGS = -static -O3
LIBS = -lm

crc: crc_32.c Makefile
	$(CC) $(CFLAGS) crc_32.c -O3 -o crc 

clean:
	rm -rf crc output*
