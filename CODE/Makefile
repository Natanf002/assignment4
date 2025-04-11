# Makefile for Continuous Memory Allocation

# Compiler and flags
CC = gcc
CFLAGS = -Wall

# Target executable
TARGET = memory_allocator

# Source files
SRC = continuous_memory_allocator.c

# Default target
all: $(TARGET)

# Rule to build the executable
$(TARGET): $(SRC)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRC)

# Clean rule
clean:
	rm -f $(TARGET) *.o

# Phony targets
.PHONY: all clean 