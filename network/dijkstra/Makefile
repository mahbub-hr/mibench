CC = gcc
CFLAGS = -static -O3
LIBS = -lm

all:  dijkstra_large dijkstra_small

dijkstra_large: dijkstra_large.c Makefile
	$(CC) $(CFLAGS) dijkstra_large.c -o dijkstra_large

dijkstra_small: dijkstra_small.c Makefile
	$(CC) $(CFLAGS) dijkstra_small.c -o dijkstra_small 

clean:
	rm -rf dijkstra_large dijkstra_small output*
