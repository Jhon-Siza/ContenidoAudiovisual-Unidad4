# Sistema de Gestión de Contenidos Audiovisuales

## Descripción

Proyecto desarrollado para la asignatura de Programación Orientada a Objetos.

El sistema permite gestionar diferentes tipos de contenidos audiovisuales aplicando herencia, polimorfismo y buenas prácticas de desarrollo de software. Además, se implementaron mejoras mediante manejo de archivos, arquitectura MVC, principios SOLID y pruebas de funcionamiento.

## Funcionalidades

- Gestión de películas.
- Gestión de series de televisión.
- Gestión de documentales.
- Gestión de podcasts.
- Gestión de videos TikTok.
- Uso de herencia y polimorfismo.
- Almacenamiento de datos en archivos CSV.
- Arquitectura MVC (Modelo - Vista - Controlador).
- Aplicación de principios SOLID.
- Pruebas de funcionamiento.

## Estructura del Proyecto

### Modelo (uni1a)

- ContenidoAudiovisual
- Pelicula
- SerieDeTV
- Documental
- Podcast
- VideoTiktok
- Actor
- Investigador
- Temporada
- ArchivoManager

### Vista (vista)

- AudiovisualView

### Controlador (controlador)

- AudiovisualController

## Manejo de Archivos

Se implementó la clase `ArchivoManager`, encargada de generar el archivo:

```text
contenidos.csv
```

donde se almacena la información de los contenidos audiovisuales registrados.

## Principios SOLID Aplicados

- SRP (Single Responsibility Principle)
- OCP (Open/Closed Principle)
- LSP (Liskov Substitution Principle)
- ISP (Interface Segregation Principle)
- DIP (Dependency Inversion Principle)

## Pruebas Realizadas

Se desarrollaron pruebas para verificar el correcto funcionamiento del sistema:

- ActorTest
- PeliculaTest

Resultados:

```text
TEST ACTOR: CORRECTO
TEST PELICULA: CORRECTO
```

## Tecnologías Utilizadas

- Java
- Apache NetBeans
- GitHub
- Programación Orientada a Objetos

## Autor

Jhon Siza

## Proyecto Académico

Complementación del sistema de Contenidos Audiovisuales correspondiente a la Unidad 4, incorporando manejo de archivos, refactorización, principios SOLID, patrón MVC y pruebas del sistema.
