CC = gcc
CFLAGS = -static -O3
LIBS = -lm

susan: susan.c Makefile
	$(CC) $(CFLAGS) -o susan susan.c $(LIBS)

clean:
	rm -rf susan output* *.o *.bc .*.o .*.bc
