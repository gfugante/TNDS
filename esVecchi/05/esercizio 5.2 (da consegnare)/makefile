
all: main

main: main.o FunzioneBase.o Solutore.o
	g++ main.o FunzioneBase.o Solutore.o -o main
	
main.o: main.C FunzioneBase.h Solutore.h
	g++ -c main.C -o main.o
	
FunzioneBase.o: FunzioneBase.C FunzioneBase.h
	g++ -c FunzioneBase.C -o FunzioneBase.o
	
Solutore.o: Solutore.C Solutore.h FunzioneBase.h
	g++ -c Solutore.C -o Solutore.o

clean:
	rm -f *.o main

