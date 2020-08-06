# MPI

Dentro de la carpeta, se encuentran localizados los 5 archivos de la entrega de la evaluación 2:

- mpi_ccn_rule.c
- ccn_rule_mpi.sbatch
- Readme.md
- output_ccn_rule.txt
- Comparacion_Tiempos.txt

## Ejecución del programa:
En Guane:
1. Usar el comando gcc -lm -fopenmp omp_ccn_rule.c -o ccn_rule. Se debe crear el ejecutable ccn_rule.
2. Usar el comando sbatch ccn_rule.sbatch.
3. Observar la salida con el comando less output_ccn_rule_%j.out, donde %j es el id de la tarea.
4. También se puede observar los errores con el comando less error_ccn_rule_%j.err, donde igualmente %j es el id de la tarea.

Nota: En local no fue posible ejecutarlo dado a que la arquitectura del procesador esta diseñada para soportar un unico núcleo y un unico hilo.
