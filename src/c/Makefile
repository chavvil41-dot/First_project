CC=gcc
CFLAGS=-Wall -Wextra -std=c11
SRC=$(wildcard *.c)
TARGET=hello

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRC)

clean:
	rm -f $(TARGET) *.o
