all : simpleloop matmul blocked clean
 
simpleloop :
	gcc -Wall -g -o simpleloop simpleloop.c

matmul : matmul.c timer.h
	gcc -Wall -g -o matmul matmul.c

blocked : blocked.c timer.h
	gcc -Wall -g -o blocked blocked.c

clean :
	rm -fr *.dSYM
