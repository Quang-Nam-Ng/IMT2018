main : main.o extendedbinomialtree.o
	g++ -o main main.o extendedbinomialtree.o --std=c++11 -Wall
main.o : main.cpp extendedbinomialtree.hpp
	g++ -c main.cpp --std=c++11 -Wall
extendedbinomialtree.o : extendedbinomialtree.hpp extendedbinomialtree.cpp
	g++ -c extendedbinomialtree.cpp --std=c++11 -Wall

