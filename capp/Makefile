CC = gcc
CFLAGS = -O2 -Wall
TARGET = main

all: $(TARGET)

$(TARGET): main.o
	$(CC) $(CFLAGS) -o $(TARGET) main.o

clean:
	rm -f $(TARGET) *.o
