LIBS:=`root-config --libs`
INCS:=`root-config --cflags`


esercizio8.0: main.o random.o
	g++ main.o random.o -o esercizio8.0 ${INCS} ${LIBS} 
main.o: main.cpp random.hpp
	g++ -c main.cpp -o main.o ${INCS} 
random.o: random.cpp random.hpp
	g++ -c random.cpp -o random.o
