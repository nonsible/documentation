# 02 - Modos de uso

Nonsible nos permite trabajar de tres maneras distintas, dependiendo de tus necesidades puedes preferir hacer uso de una u otra.


## Interactivo (sin argumentos)

En el modo _Interactivo_ vamos a necesitar añadir manualmente las conexiones, y podremos llamar un fichero YAML para realizar las tareas. Esta manera de ejecutar Nonsible es útil para cuando quieres ejecutar tareas de manera ocasional sin disponer de un fichero de conexiones.

```sh
nonsible
```


## Semi-Interactivo (con un argumento)

En el modo _Semi-Interactivo_ vamos a indicar solo un argumento, el fichero de conexiones. Luego, de manera interactiva, vamos a poder indicar el fichero de tareas que queremos ejecutar.

```sh
nonsible connection_file.yml
```

## Desatendido (con dos argumentos)

Esta metodología es perfecta para automatizaciones y ciclos de CI/CD. Indicaremos tanto el fichero YAML de conexiones como el fichero YAML de tareas. Nonsible se encargará de realizar las tareas en el orden indicado.

```sh
nonsible connection_file.yml task_file.yml
```

