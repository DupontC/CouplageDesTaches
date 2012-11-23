recherche_op:	main.o diagramme.o tache.o
	g++ -o recherche_op main.o diagramme.o tache.o -lm

main.o:	main.cpp
	gcc  -c main.cpp  

diagramme.o:	diagramme.cpp
	gcc  -c diagramme.cpp  

tache.o: tache.cpp
	gcc  -c tache.cpp

tarball: 
	tar -vcf recherche_op.tar main.cpp diagramme.cpp tache.cpp main.h diagramme.h tache.h  Makefile

clean:
	rm *.o recherche_op