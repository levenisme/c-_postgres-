CC=g++
CFLAGS=-O3
EXTRAFLAGS=-lpq -lpqxx

all: test

test: main.cpp exerciser.h exerciser.cpp query_funcs.h query_funcs.cpp
	$(CC) $(CFLAGS) -o test main.cpp exerciser.cpp query_funcs.cpp $(EXTRAFLAGS)

clean:
	rm -f *~ *.o test

clobber:
	rm -f *~ *.o
