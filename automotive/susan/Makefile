CC = gcc
CFLAGS = -static -O3 -w -Wno-error=implicit-int
LIBS = -lm

susan: susan.c Makefile
	$(CC) $(CFLAGS) -o susan susan.c $(LIBS)

clean:
	rm -rf susan output* *.o *.bc .*.o .*.bc
