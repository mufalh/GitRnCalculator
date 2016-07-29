all: Roman

Roman: cutcheck.o cut-pass.o cutgen.o
	gcc cutcheck.o cut-pass.o cutgen.o -o Roman

cutcheck.o: cutcheck.c
	gcc -c cutcheck.c

cut-pass.o: cut-pass.c
	gcc -c cut-pass.c

cutgen.o: cutgen.c
	gcc -c cutgen.c

clean:
	rm -rf *o Roman
