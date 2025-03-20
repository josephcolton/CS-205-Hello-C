
CC = gcc
LIBS =
OBJS =
PROGS = hello

all: $(PROGS)

hello: hello.c
	$(CC) hello.c -o hello

test: $(PROGS)
	./hello

clean:
	rm -f $(PROGS)
