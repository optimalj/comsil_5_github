CC = gcc
TARGET = animal.exe
OBJS = dog.o blackcow.o turtle.o main.o

$(TARGET): $(OBJS)
	$(CC) -o $(TARGET) $(OBJS)

dog.o: dog.c
	$(CC) -c dog.c

blackcow.o: blackcow.c
	$(CC) -c blackcow.c

turtle.o: turtle.c
	$(CC) -c turtle.c

main.o: main.c
	$(CC) -c main.c

.PHONY: clean

clean:
	rm -f *.o $(TARGET)
