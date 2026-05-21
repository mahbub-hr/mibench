
.PHONY: all clean matrix_mul.bin
CC = gcc
CFLAGS = -static -O3 -g

all: matrix_mul.bin

matrix_mul.bin: 
	$(CC) $(CFLAGS) matrix_mul.c -o matrix_mul.bin

clean:
	rm -rf matrix_mul.bin output* *.o *.bc .*.o .*.bc *.tmp *.bin *.log *csv .gdb_history
	
