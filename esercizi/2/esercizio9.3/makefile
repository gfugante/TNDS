esercizio9.3: main.o random.o Esperimentoprisma.o vettore.o vettoredati.o integrale.o
	g++ main.o random.o Esperimentoprisma.o vettore.o vettoredati.o integrale.o -o esercizio9.3
main.o: main.C random.hpp vettoredati.h vettore.h
	g++ -c main.C -o main.o 
random.o: random.cpp random.hpp
	g++ -c random.cpp -o random.o
vettore.o: vettore.cpp vettore.h
	g++ -c vettore.cpp -o vettore.o
vettoredati.o: vettoredati.cpp vettoredati.h vettore.h
	g++ -c vettoredati.cpp -o vettoredati.o
Esperimentoprisma.o: Esperimentoprisma.C Esperimentoprisma.h random.hpp
	g++ -c Esperimentoprisma.C -o Esperimentoprisma.o
integrale.o:integrale.cpp
	g++ -c integrale.cpp -o integrale.o
