# Dijkstra-openmp
Dijkstra's Algorithm using openMP for parallelization

This program has 2 functions in it.
     -- serial_dijkstra: It is a normal execution of the code
     -- omp_dijkstra: This function uses the openMP commands to run Dijkstra into multiple threads to achieve better efficiency.

     
      where filename could be:
      -- input_file.txt : This dataset consists of 'circles' (or 'friend’s lists') from Facebook.
                                 Facebook data was collected from survey participants using this Facebook app.
                          Nodes: 4039
                          Edges: 88234
      
The first line of the each file consist of the source node which can be changed in the file.

Steps to compile and execute-
     --compilation: gcc -fopenmp omp_dijkstra.c -o dijkstra.exe
     --execute: ./dijkstra.exe thread_count input_file.txt
    
