CC = gcc
CFLAGS = -static -O0
LIBS = -lm

all:  dijkstra_large.bin dijkstra_small.bin

dijkstra_large.bin: dijkstra_large.c Makefile
	$(CC) $(CFLAGS) dijkstra_large.c -o dijkstra_large.bin

dijkstra_small.bin: dijkstra_small.c Makefile
	$(CC) $(CFLAGS) dijkstra_small.c -o dijkstra_small.bin	 

clean:
	rm -rf dijkstra_large dijkstra_small output* *.o *.bc .*.o .*.bc *.log .gdb_history *.txt *.bin *.csv *.patch *_duplicated
