CC = gcc
CFLAGS = -static -O3 -w -Wno-error=implicit-int
LIBS = -lm

susan.bin: susan.c Makefile
	$(CC) $(CFLAGS) -o susan.bin susan.c $(LIBS)

clean:
	rm -rf susan susan.bin output* *.o *.bc .*.o .*.bc
