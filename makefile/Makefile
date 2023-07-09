all: hello

hello: hello.o
	g++ -o hello hello.o

hello.o: hello.cpp
	g++ --std=c++11 -Wall -Wextra -c hello.cpp

