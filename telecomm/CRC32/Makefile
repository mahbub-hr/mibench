CC = gcc
CFLAGS = -static -O0 -g
LIBS = -lm

crc.bin: crc_32.c Makefile
	$(CC) $(CFLAGS) crc_32.c -O3 -o crc.bin 

clean:
	rm -rf crc output* *.o *.bc .*.o .*.bc *.bin *.txt *.log
