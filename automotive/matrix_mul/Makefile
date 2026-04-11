
.PHONY: all clean matrix_mul matrix_mul_dup matrix_mul_partitioned
CC = gcc
CFLAGS = -static -O0

all: matrix_mul matrix_mul_dup matrix_mul_partitioned

matrix_mul: 
	$(CC) $(CFLAGS) matrix_mul.c -o matrix_mul

matrix_mul_dup: 
	$(CC) $(CFLAGS)  matrix_mul_dup.c -o matrix_mul_dup -lm
	
matrix_mul_partitioned: 
	$(CC) $(CFLAGS)  -T layout.ld matrix_mul_partitioned.c -o matrix_mul_partitioned -lm

clean:
	rm -rf matrix_mul matrix_mul_dup matrix_mul_partitioned output*
	