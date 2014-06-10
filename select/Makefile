CC = gcc
CFLAGS = -W -Wall -O2
LDFLAGS = -lm

all : select

select : select.c
	$(CC) $(CFLAGS) -o $@ $^ $(LDFLAGS)

clean :
	rm -rf *.o
