all: esercizio3.3
esercizio3.3: esercizio3.3.o particelle.o elettrone.o corpo_celeste.o posizione.o
	g++ esercizio3.3.o particelle.o elettrone.o corpo_celeste.o posizione.o -o esercizio3.3
esercizio3.3.o: esercizio3.3.cc particelle.h elettrone.h corpo_celeste.h
	g++ -c esercizio3.3.cc -o esercizio3.3.o
particelle.o: particelle.cc particelle.h
	g++ -c particelle.cc -o particelle.o
corpo_celeste.o: corpo_celeste.cc posizione.h particelle.h corpo_celeste.h
	g++ -c corpo_celeste.cc -o corpo_celeste.o
elettrone.o: elettrone.cc elettrone.h particelle.h
	g++ -c elettrone.cc -o elettrone.o
posizione.o: posizione.cc posizione.h
	g++ -c posizione.cc -o posizione.o
