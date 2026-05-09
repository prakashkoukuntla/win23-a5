calculator: main.o addition.o subtraction.o multiplication.o division.o
	cc -o calculator main.o addition.o subtraction.o multiplication.o division.o

%.o: %.c operations.h
	cc -c $< -o $@

clean:
	rm -f *.o calculator

.PHONY: clean
