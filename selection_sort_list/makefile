main.out: main.o selection_sort_list.o data_processing.o linked_list.o
	gcc main.o selection_sort_list.o data_processing.o linked_list.o -o main.out
main.o: main.c selection_sort_list.h ../data/data_processing.h
	gcc -c main.c
selection_sort_list.o: selection_sort_list.c selection_sort_list.h
	gcc -c selection_sort_list.c
data_processing.o: ../data/data_processing.c ../data/data_processing.h
	gcc -c ../data/data_processing.c
linked_list.o: ../linkedlist/linked_list.c ../linkedlist/linked_list.h
	gcc -c ../linkedlist/linked_list.c
clean:
	rm *.o main.out