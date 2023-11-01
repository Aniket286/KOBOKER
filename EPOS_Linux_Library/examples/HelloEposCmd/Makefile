CC = g++
CFLAGS = -I.
TARGET = HelloEposCmd
LIBS = -lEposCmd -lusb-1.0

all: $(TARGET)

$(TARGET): $(TARGET).cpp
	$(CC) -o $(TARGET) $(TARGET).cpp $(CFLAGS) $(LIBS)

clean:
	$(RM) $(TARGET)
