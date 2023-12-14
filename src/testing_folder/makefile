CC = g++
CFLAGS = -g-std=c++11
EXECUTABLES = myprogram
HEADERS = test.h

all: $(EXECUTABLES)

myprogram: test.o driver.o 
	g++ test.o driver.o -o myprogram
test.o: test.cpp
	g++ -c test.cpp
driver.o: driver.cpp
	g++ -c driver.cpp
clean:
	rm -f *.o $(EXECUTABLES)