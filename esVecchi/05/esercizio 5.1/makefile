
all: main

main: main.o FunzioneBase.o
	g++ main.o FunzioneBase.o -o main
	
main.o: main.C FunzioneBase.h
	g++ -c main.C -o main.o
	
FunzioneBase.o: FunzioneBase.C FunzioneBase.h
	g++ -c FunzioneBase.C -o FunzioneBase.o
	


