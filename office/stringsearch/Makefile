FILE1 = bmhasrch.c  bmhisrch.c  bmhsrch.c  pbmsrch_small.c 
FILE2 = bmhasrch.c  bmhisrch.c  bmhsrch.c  pbmsrch_large.c 
CC = gcc
CFLAGS = -static -O3 -Wno-error=implicit-int -Wno-error=implicit-function-declaration
LIBS = -lm

all: stringsearch_small stringsearch_large

stringsearch_small: ${FILE1} Makefile
	$(CC) $(CFLAGS) ${FILE1} -O3 -o stringsearch_small

stringsearch_large: ${FILE2} Makefile
	$(CC) $(CFLAGS) ${FILE2} -O3 -o stringsearch_large

clean:
	rm -rf stringsearch_small stringsearch_large output* *.o .*.o *.bc .*.bc