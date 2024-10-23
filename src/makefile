# Variables
CC = clang         # Compiler
SRC = main.c       # Source file
BIN = main         # Executable (binary) file
CFLAGS = -Wall     # Compiler flags (for warnings, etc.)

# Build instruction
$(BIN): $(SRC)
    $(CC) $(CFLAGS) $(SRC) -o $(BIN)

# Clean rule to remove the binary
.PHONY: clean
clean:
    rm -f $(BIN)
