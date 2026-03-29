FILE = bitcnt_1.c bitcnt_2.c bitcnt_3.c bitcnt_4.c bitcnts.c bitfiles.c bitstrng.c bstr_i.c 
CC = gcc
CFLAGS = -static -O3
LIBS = -lm

bitcnts: ${FILE} Makefile
	$(CC) $(CFLAGS) ${FILE} -o bitcnts

clean:
	rm -rf bitcnts output* *.o *.bc .*.o .*.bc
