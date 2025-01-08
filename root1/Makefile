# Compiler and Flags
CC = gcc
CFLAGS = -Wall -g

# Source and Binary paths (relative paths)
SRC = root1/ch-1/ex-1-6/src/hello.c
BIN = root1/ch-1/ex-1-6/bin/hello

# Default target
all: $(BIN)

# Build the binary from the source
$(BIN): $(SRC)
	$(CC) $(CFLAGS) -o $(BIN) $(SRC)

# Clean up: remove the binary
clean:
	rm -f $(BIN)

