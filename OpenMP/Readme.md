# OpenMP

Dentro de la carpeta, se encuentran localizados los 4 archivos de la entrega de la evaluación 1:

- omp_ccn_rule.c
- ccn_rule.sbatch
- Readme.md
- output_ccn_rule.txt

## Ejecución del programa:
En Guane:
1. Usar el comando gcc -lm -fopenmp omp_ccn_rule.c -o ccn_rule. Se debe crear el ejecutable ccn_rule.
2. Usar el comando sbatch ccn_rule.sbatch.
3. Observar la salida con el comando less output_ccn_rule_%j.output, donde %j es el id de la tarea.
4. También se puede observar los errores con el comando less error_ccn_rule_%j.err, donde igualmente %j es el id de la tarea.

Nota: En local no fue posible ejecutarlo dado a que la arquitectura del procesador esta diseñada para soportar un unico núcleo y un unico hilo.

## Ejecución de la modificación de programa original:
1. Usar el comando gcc -lm ccn_rule_mod.c -o ccn_rule_mod. Se debe crear el ejecutable ccn_rule_mod.
2. Usar el comando sbatch ccn_rule_mod.sbatch.
3. Usar less ccn_rule_mod_%j.output y less ccn_rule_mod_%j.err para observar la salida y los errores respectivamente.
