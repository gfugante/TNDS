esercizio4.0: esercizio4.0.o puntomateriale.o particelle.o campovettoriale.o posizione.o
	g++ esercizio4.0.o puntomateriale.o particelle.o campovettoriale.o posizione.o -o esercizio4.0
esercizio4.0.o: esercizio4.0.cc puntomateriale.h particelle.h campovettoriale.h posizione.h
	g++ -c esercizio4.0.cc -o esercizio4.0.o
puntomateriale.o: puntomateriale.cc posizione.h particelle.h campovettoriale.h
	g++ -c puntomateriale.cc -o puntomateriale.o
particelle.o: particelle.cc particelle.h
	g++ -c particelle.cc -o particelle.o
campovettoriale.o: campovettoriale.cc particelle.h posizione.h
	g++ -c campovettoriale.cc -o campovettoriale.o
posizione.o: posizione.cc posizione.h
	g++ -c posizione.cc -o posizione.o
