OBJS = main_file.o file1.o file2.o

all: hellomake

hellomake: $(OBJS)
	$(CXX) $(OBJS) -o hellomake

main_file.o: main_file.cpp file1.h file2.h
	$(CXX) -c main_file.cpp

file1.o: file1.cpp file1.h
	$(CXX) -c file1.cpp

file2.o: file2.cpp file2.h
	$(CXX) -c file2.cpp

clean:
	rm -f *.o hellomake
