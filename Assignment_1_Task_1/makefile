CC		= g++
CFLAGS	= -g
RM		= rm -f
OBJDUMP	= objdump

default: all

all: add_numbers.cpp
	$(CC) $(CFLAGS) -o add_numbers add_numbers.cpp

run: all
	./add_numbers

dump: all
	$(OBJDUMP) -d add_numbers

clean:
	$(RM) add_numbers
