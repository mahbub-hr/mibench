
.PHONY: all clean matrix_mul matrix_mul_dup matrix_mul_partitioned
CC = gcc
CFLAGS = -static -O0

all: matrix_mul matrix_mul_dup matrix_mul_partitioned

matrix_mul: 
	$(CC) $(CFLAGS) matrix_mul.c -o matrix_mul

clean:
	rm -rf matrix_mul matrix_mul_dup matrix_mul_partitioned output* *.o *.bc .*.o .*.bc
	