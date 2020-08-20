# parallel-cluster
Using openmpi to speed up task on a cluster

This repository stores OpenMPI implementations, will add more
#### Pi Calculator
uses leibniz series to sum up the work done by each process.

[code](https://github.com/du00d/parallel-cluster/blob/master/picluster.cpp)

Compile with ./mpic++ picluster.cpp -o picluster

Run with ./mpirun -np 2 ./picluster
