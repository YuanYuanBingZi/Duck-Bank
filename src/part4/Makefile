all: bank

bank: bank.c string_parser.c string_parser.h
	gcc -g -o bank bank.c string_parser.c

clean:
	rm -f core *.o bank