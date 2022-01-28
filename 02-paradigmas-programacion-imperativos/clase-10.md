### Problemas de la concurrencia

- Carreras (critical races)
Problemas cuando debemos utilizar en cualquiera de los hilos los recursos entre uno o varios hilos


- puntos muertos
Ocurre cuando un hilo debe esperar a un evento que nuca sucederá 
se deben cumplir 4 condiciones

1. Los hilos deben tener derechos exclusivos a los recursos.
2. Los hilos deben de contener algunos recursos mientras esperan otros.
3. Los recursos no pueden eliminar de los hilos en espera.
4. Existe una cadena circular de hilos en las que cada uno contiene uno o más recursos del siguiente hilo

El problema de los filosofos 


## Componentes del monitor 

* Inicialización: contiene código s ser ejecutado
* Datos privados: procedimientos que se utilizan desde dentro del monitor
* Métodos del monitor: procedimientos que se pueden llamar desde fuera
* Cola de entrada: hilos que llaman a algún métodos del monitor pero no tienen permiso para ejecutarse aún


Lenguajes 

- JavaScript
- C#
- Golang
- Rust

