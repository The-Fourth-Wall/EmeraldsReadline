NAME = test
CC = clang

CFLAGS = -std=c89 -Wall -Wextra -Werror -pedantic -pedantic-errors -Wpedantic

INPUT = ../src/readline/*.a $(NAME).c
OUTPUT = $(NAME)

all:
	$(CC) $(CFLAGS) -o $(OUTPUT) $(INPUT)
	./$(OUTPUT)

clean:
	$(RM) -r $(OUTPUT) $(NAME).dSYM
