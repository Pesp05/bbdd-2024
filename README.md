# Bases de datos - 2023/24
Repositorio del módulo de Bases de Datos para el curso 2023-24 (DAM - Salesianos Triana)

A continuación, se detallan los proyectos que se incluyen dentro del repositorio.

- [Ejemplo 1 - PrimerProyectoDataJpa](./PrimerProyectoDataJpa/): ejemplo de creación de un proyecto desde cero que incluye Spring Data JPA y la base de datos H2. También se puede ver la creación de una entidad, un repositorio, y un ejemplo de su uso.

- [Ejemplo 2 - ManyToOne](./ManyToOne/): ejemplo que en primera instancia implementa una asociación `@ManyToOne` de forma unidireccional, y que posteriormente la completa bidireccionalmente con una asociación `@OneToMany`. 

- [Ejemplo 3 - Composición](./Composicion/): ejemplo de traslado de una asociación de composición, donde se gestiona el ciclo de vida de dos entidades a través de un único repositorio.

- [Ejemplo 4 - Servicio Base](./ServicioBase/): ejemplo de un servicio genérico que incorpora las funcionalidades CRUD más utilizadas. También se incluye en este ejemplo la importación de datos en la base de datos a través de un fichero `import.sql` y un controlador y plantilla de ejemplo.

- [Ejemplo 5 - ManyToMany](./ManyToMany/): ejemplo de manejo de una asociación  `@ManyToMany` de forma bidireccional.

- Ejemplos 6, 7 y 8 sobre herencia:
  - [Ejemplo 6 - Herencia MappedSuperclass](./HerenciaMappedSuperclass/), que aplica cuando no queremos que la clase base sea una entidad.
  - [Ejemplo 7 - Herencia Single Table ](./HerenciaSingleTable/), cuando las clases hijas no aportan casi ningún atributo y queremos dejar todo reflejado en una única tabla.
  - [Ejemplo 8 - Herencia Joined](./HerenciaJoined/) que es la más habitual, en la que para las entidades hijas se genera una tabla con una clave externa y los atributos específicos.

- [Ejemplo 9 - Identificadores compuestos](./IdentificadorCompuesto/): ejemplo de creación de un Id compuesto por varios atributos, con diferentes tipos de solución y aplicación.

- [Ejemplo 10 - Composición con identificador compuesto](./ComposicionIdComp/): mejora del [ejemplo 3](./Composicion/) para que una parte del identificador compuesto sea autogenerada. 

- [Ejemplo 11 - ManyToMany Extra](./ManyToManyExtra/): sobre cómo tratar asociaciones de esta multiplicidad que tengan atributos extra.    

- Ejemplos 12, 13 y 14 sobre seguridad:
  - [Ejemplo 12 - Seguridad en Memoria](./SeguridadEnMemoria/): primer acercamiento a Spring Security con la implementación de un mecanismo de autenticación con listado de usuarios en memoria.
  - [Ejemplo 13 - Seguridad en base de datos](./SeguridadEnUDS/): segundo acercamiento a Spring Security con la implementación de un mecanismo de autenticación con dos roles diferentes, almacenando los usuarios en base de datos a través del uso de entidades y repositorios de Spring Data JPA. 
  - [Ejemplo 14 - Login según el rol](./LoginSegunRol/): adaptación del primer ejemplo de seguridad para que al realizar el login de un usuario, se le redirija a una URL específica según su rol.

- [Ejemplo 15 - Consultas derivadas del nombre](./ConsultasDerivadas/): mecanismo ofrecido por Spring Data JPA para realizar consultas sin necesidad de saber SQL u otro lenguaje declarativo.