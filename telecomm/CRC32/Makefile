CC = gcc
CFLAGS = -static -O3 -g -fno-vectorize -fno-slp-vectorize
LIBS = -lm

crc.bin: crc_32.c Makefile
	$(CC) $(CFLAGS) crc_32.c -O3 -o crc.bin 

clean:
	rm -rf crc output* *.o *.bc .*.o .*.bc *.bin *.txt *.log
