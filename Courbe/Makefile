#Ex2.2
sources = carre.cpp
objets = $(sources:.cpp=.o)

CourbeCarre :$(objets) 
	g++ $^ -o $@ -lQtGui -lQtCore -lqcustomplot -L/home/mrazafima65n/Cours Genie logiciel/Courbe/qcustomplot/sharedlib/compilation #chercher les librairies

carre.o : carre.cpp
	g++ -c $^ -I/usr/include/qt4/QtGui/ -I/usr/include/qt4/ -I/usr/include/qt4/QtCore/  -I/home/mrazafima65n/Cours Genie logiciel/Courbe/qcustomplot





#Ex2.1
#sources = gui_simple.cpp
#objets = $(sources:.cpp=.o)

#GUISimple :$(objets) 
#	g++ $^ -o $@ -lQtGui -lQtCore #chercher les librairies

#gui_simple.o : gui_simple.cpp
#	g++ -c $^ -I/usr/include/qt4/QtGui/ -I/usr/include/qt4/


