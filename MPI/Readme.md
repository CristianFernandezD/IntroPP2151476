# MPI

Dentro de la carpeta, se encuentran localizados los 5 archivos de la entrega de la evaluación 2:

- mpi_ccn_rule.c
- ccn_rule_mpi.sbatch
- Readme.md
- mpi_ccn_rule.out
- Comparacion_Tiempos.txt

## Ejecución del programa:
1. Usar el comando mpicc -lm mpi_ccn_rule.c -o mpi_ccn_rule. Se debe crear el ejecutable mpi_ccn_rule.
2. Usar el comando sbatch ccn_rule_mpi.sbatch.
3. Observar la salida con el comando less mpi_ccn_rule_%j.out, donde %j es el id de la tarea.

