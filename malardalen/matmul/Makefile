
.PHONY: all clean matmul.bin
CC = gcc
CFLAGS = -static -O3 -g -fno-vectorize -fno-slp-vectorize

all: matmul.bin

matmul.bin: 
	$(CC) $(CFLAGS) matmul.c -o matmul.bin

clean:
	rm -rf matmul.bin output* *.o *.bc .*.o .*.bc *.tmp *.bin *.log *csv .gdb_history
	
