output: debug.o
	gcc debug.o -o debug

debug.o: debug.c user.h types.h
	gcc -c debug.c

debug.d: debug.c user.h types.h
	gcc -c debug.c