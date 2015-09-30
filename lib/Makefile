OBJ = func1.o func2.o
CC = gcc
AR = ar
CFLAGS = -g -Wall
OUTPUT = libfunc.a

$(OUTPUT): $(OBJ)
	$(AR) rv $(OUTPUT) $(OBJ)
%.o: %.c
	$(CC) $(CFLAGS) -c $< -o $@
clean:
	rm *.o $(OUTPUT)

