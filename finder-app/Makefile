NAME = writer

CC=$(CROSS_COMPILE)gcc

all: writer

writer: writer.c
	$(CC) -g -Wall -c -o writer.o writer.c
	$(CC) -g -Wall -I/ writer.o -o writer

clean: 
	rm -f *.bin *.o writer