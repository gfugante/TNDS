
all: main

main: main.o FunzioneBase.o Integrale.o
	g++ main.o FunzioneBase.o Integrale.o -o main
	
main.o: main.C FunzioneBase.h Integrale.h
	g++ -c main.C -o main.o
	
FunzioneBase.o: FunzioneBase.C FunzioneBase.h
	g++ -c FunzioneBase.C -o FunzioneBase.o

Integrale.o: Integrale.C Integrale.h FunzioneBase.h
	g++ -c Integrale.C -o Integrale.o	

clean:
	rm -f *.o main
