CC		= g++
CFLAGS	= -g
RM		= rm -f
OBJDUMP	= objdump

default: all

all: task2.cpp
	$(CC) $(CFLAGS) -o task2 task2.cpp

run: all
	./task2

dump: all
	$(OBJDUMP) -d task2

clean: all
	$(RM) task2
