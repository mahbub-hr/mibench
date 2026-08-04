FILE1 = qsort_small.c
FILE2 = qsort_large.c
CC = gcc
CFLAGS = -static -O3 -g -fno-vectorize -fno-slp-vectorize
LIBS = -lm

all: qsort_small.bin qsort_large.bin

qsort_small.bin: qsort_small.c Makefile
	$(CC) $(CFLAGS) qsort_small.c -o qsort_small.bin -lm
qsort_large.bin: qsort_large.c Makefile
	$(CC) $(CFLAGS) qsort_large.c -o qsort_large.bin -lm

clean:
	rm -rf qsort_small qsort_large *.patch output* *.csv *.log *.txt .*.dot .gdb* *.o *.bc .*.o .*.bc *.bin *_duplicated *_partitioned *_my_tool *_aspis
