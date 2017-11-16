# $Id: Makefile,v 1.3 2015-11-29 04:25:13-08 - - $

all : hello

hello : main.o hello.o
	cc main.o hello.o -o hello

main.o : main.c hello.h
	cc -c main.c

hello.o : hello.c hello.h
	cc -c hello.c

ci : Makefile main.c hello.c hello.h
	cid Makefile main.c hello.c hello.h

test : hello
	./hello

clean : 
	- rm hello.o main.o

spotless : clean
	- rm hello

