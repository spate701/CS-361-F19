
hw1_a.o: hw1_a.c
	gcc -c hw1_a.c

hw1_b.o: hw1_b.c
	gcc -c hw1_b.c

hw1: hw1_a.o hw1_b.o
	gcc -o hw1 hw1_a.o hw1_b.o -lm

all: hw1

clean:
	rm *.o hw1
