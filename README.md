# Bases de datos - 2019/20
Repositorio del módulo de Bases de Datos para el curso 2019-20 (DAM - Salesianos Triana)

A continuación, se detallan los proyectos que se incluyen dentro del repositorio.

## Ejemplos iniciales

* [01_PrimerEjemploSpringCore](https://github.com/lmlopezmagana/bbdd-2020/tree/master/01_PrimerEjemploSpringCore): se trata de un sencillo ejemplo de integración de Spring en un proyecto Maven. Se utiliza la configuración a través de un fichero XML.
* [02_SegundoEjemploSpringCore](https://github.com/lmlopezmagana/bbdd-2020/tree/master/02_SegundoEjemploSpringCore): este segundo ejemplo muestra como realizar la configuración de beans a través de anotaciones.
* [03_PrimerProyectoSpringBoot](https://github.com/lmlopezmagana/bbdd-2020/tree/master/03_PrimerProyectoSpringBoot): ejemplo de un primer proyecto creado con Spring Boot.
* [04_PrimerProyectoWeb](https://github.com/lmlopezmagana/bbdd-2020/tree/master/04_PrimerProyectoWeb): en este caso, se trata de un proyecto similar al anterior, pero en el que creamos un primer controlador y una plantilla.
* [05_PrimerProyectoDataJpa](https://github.com/lmlopezmagana/bbdd-2020/tree/master/05_PrimerProyectoDataJpa): ejemplo de creación de un proyecto desde cero que incluye Spring Data JPA y la base de datos H2. También se puede ver la creación de una entidad, un repositorio, y un ejemplo de su uso.

## Manejo de asociaciones

* [06_ManyToOne](https://github.com/lmlopezmagana/bbdd-2020/tree/master/06_ManyToOne): en este ejemplo se trabajan dos conceptos
    * La creación de un _servicio base_, que nos permite encapsular el repositorio, evitando así el acomplamiento (dista de ser una solución ideal, pero es un buen comienzo). Los demás servicios que sirvan para acceder a los datos pueden extender este.
    * El ejemplo de una asociación muchos-a-uno (`@ManyToOne`) que es tratada unidireccionalmente.
* [07_OneToManyBidi](https://github.com/lmlopezmagana/bbdd-2020/tree/master/07_OneToManyBidi): ejemplo que completa el anterior, para dar un tratamiento bidireccional a una asociación one-to-many <- -> many-to-one

## Soluciones a ejercicios    

Además, puedes encontrar algunos proyectos que comienzan por _EXX_, que significa que son la solución a algún ejercicio.

* [E01_EjercicioDao](https://github.com/lmlopezmagana/bbdd-2020/tree/master/E01_EjercicioDao): solución al ejercicio de elaboración de un proyecto que implementa el patrón DAO, así como un servicio que interactúa con el mismo.
* [E01_EjercicioDao_SpringBoot](https://github.com/lmlopezmagana/bbdd-2020/tree/master/E01_EjercicioDao_SpringBoot): solución al mismo ejercicio, pero esta vez usando Spring Boot.
