# ParalelaComp
##COMO COMPILAR:

# MULTIXVECTOR:
mpicc -g -o main multi.cpp
# EXEC:
mpiexec -n <NRO_PROCESOS> main

# ODDEVENSORT:
mpicc -g -o main oddevens.c
# EXEC:
mpirin -np <NRO_PROCESOS> --oversubcribe main



