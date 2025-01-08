#compiler
CC=gcc
CFLAGS=-Wall -g
SRC=excerises/ch-1/ex-1-6/src/hello.c
BIN=excerises/ch-1/ex-1-6/bin/hello

#target
all: $(BIN)

$(BIN):$(SRC)
	$(CC) $(CFLAGS) -o $(BIN) $(SRC)

clean:
	rm -f $(BIN) 
