# ParalelaComp
##COMO COMPILAR:

#MULTIXVECTOR:
mpicc -g -o main multi.cpp
mpiexec -n <NRO_PROCESOS> main

#ODDEVENSORT:
mpicc -g -o main oddevens.c
mpirin -np 2 --oversubcribe main



