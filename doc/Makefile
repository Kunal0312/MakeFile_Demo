_main: main.o print.o factorial.o multiply.o
	g++ main.o print.o factorial.o multiply.o -o _main

main.o: main.cpp
	g++ -c main.cpp

print.o: print.cpp
	g++ -c print.cpp

factorial.o: factorial.cpp
	g++ -c factorial.cpp

multiply.o: multiply.cpp
	g++ -c multiply.cpp

clean:
	rm *.o _main
