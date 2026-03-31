CC = gcc
CFLAGS = -static -O3 -w #-Wno-error=implicit-int -Wno-error=implicit-function-declaration -Wno-implicit-int -Wno-deprecated-non-prototype -Wno-return-type
LIBS = -lm

susan: susan.c Makefile
	$(CC) $(CFLAGS) -o susan susan.c $(LIBS)

clean:
	rm -rf susan output* *.o *.bc .*.o .*.bc
