INCS:=` root-config --cflags`
LIBS:=` root-config --libs`


Esercizio: Esercizio.o random.o 
	g++ Esercizio.o random.o -o Esercizio_8.3  ${INCS} ${LIBS}

Esercizio.o: Esercizio_8.3.cpp random.h 
	g++ -c Esercizio_8.3.cpp -o Esercizio.o ${INCS}

random.o: random.cpp random.h 
	g++ -c random.cpp -o random.o 


root: 
	g++ -o disegnaROOT disegnaROOT.cpp ${INCS} ${LIBS}



