LIBS:=`root-config --libs`
INCS:=`root-config --cflags`

esercizio9.2: main.o random.o integrale.o trigonometric.o
	g++ main.o random.o integrale.o trigonometric.o -o esercizio9.2 ${INCS} ${LIBS}
main.o: main.C random.hpp funzionebase.h trigonometric.hpp integrale.hpp
	g++ -c main.C -o main.o ${INCS}
random.o: random.cpp random.hpp
	g++ -c random.cpp -o random.o
integrale.o: integrale.cpp integrale.hpp
	g++ -c integrale.cpp -o integrale.o
trigonometric.o: trigonometric.cpp trigonometric.hpp
	g++ -c trigonometric.cpp -o trigonometric.o
