FILE = bitcnt_1.c bitcnt_2.c bitcnt_3.c bitcnt_4.c bitcnts.c bitfiles.c bitstrng.c bstr_i.c 
CC = gcc
CFLAGS = -static -O3 -DFI_DETERMINISTIC_OUTPUT
LIBS = -lm

bitcnts.bin: ${FILE} Makefile
	$(CC) $(CFLAGS) ${FILE} -o bitcnts.bin

clean:
	rm -rf bitcnts bitcnts.bin output* *.o *.bc .*.o .*.bc
