LIBS=`root-config --libs`
INCS=`root-config --cflags`

all: esercizio9.2
esercizio9.2: esercizio9.2.o integrale.o vettoredati.o vettore.o Random.o
	g++ esercizio9.2.o integrale.o vettoredati.o vettore.o Random.o -o esercizio9.2 ${INCS} ${LIBS}
esercizio9.2.o: esercizio9.2.cc integrale.h vettoredati.h vettore.h Random.h seno.h funzioneBase.h
	g++ -c esercizio9.2.cc -o esercizio9.2.o ${INCS}
integrale.o: integrale.cc integrale.h Random.h funzioneBase.h seno.h
	g++ -c integrale.cc -o integrale.o
vettoredati.o: vettoredati.cc vettore.h vettoredati.h
	g++ -c vettoredati.cc -o vettoredati.o
vettore.o: vettore.cc vettore.h
	g++ -c vettore.cc -o vettore.o
Random.o: Random.cc Random.h
	g++ -c Random.cc -o Random.o
