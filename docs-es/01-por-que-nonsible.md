# 01 - Por qué usar nonsible

## ¿Por qué debería usar Nonsible?

Nonsible es una alternativa de Ansible desarrollada en Rust. La idea es no depender de factores como que la máquina host tenga instalado Python.

## Ventajas frente a Ansible

### Es cross platform

El proyecto está desarrollado con Rust, que nos ofrece la flexibilidad de construir el código independientemente del sistema operativo en el que nos encontremos.

### Es perfecto para tareas livianas

Este proyecto encaja perfectamente con tareas de instalar paquetería en múltiples equipos, o por ejemplo actualizar los equipos dentro de tu compañía.

### Es escalable

Los ficheros se organizan como ficheros de __connections__ y ficheros de __tasks__. Estos ficheros deben encontrarse en ficheros distintos.
Esto nos permite tener múltiples ficheros YAML que nos puedan servir para diferentes tareas y en diferentes equipos distintos.

### Se adapta a tus necesidades

Nonsible puede ser ejecutado en modo _completamente interactivo_, modo _semi-interactivo_ y modo _inatendido_. 

