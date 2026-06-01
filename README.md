# Sistema de Gestión de Contenidos Audiovisuales

## Descripción

Proyecto desarrollado para la asignatura de Programación Orientada a Objetos.

El sistema permite gestionar diferentes tipos de contenidos audiovisuales aplicando herencia, polimorfismo, manejo de archivos, principios SOLID y arquitectura MVC.

## Cambios Realizados

Durante la complementación del proyecto se implementaron las siguientes mejoras:

* Manejo de archivos mediante la clase ArchivoManager.
* Generación del archivo contenidos.csv.
* Implementación del patrón MVC.
* Refactorización del código.
* Aplicación de principios SOLID.
* Creación de pruebas para validar el funcionamiento del sistema.
* Actualización de la documentación del proyecto.

## Estructura del Proyecto

### Modelo (uni1a)

* ContenidoAudiovisual
* Pelicula
* SerieDeTV
* Documental
* Podcast
* VideoTiktok
* Actor
* Investigador
* Temporada
* ArchivoManager

### Vista (vista)

* AudiovisualView

### Controlador (controlador)

* AudiovisualController

### Pruebas

* ActorTest
* PeliculaTest

## Requisitos

* Java JDK 8 o superior
* Apache NetBeans
* Maven

## Cómo Clonar el Proyecto

Ejecutar el siguiente comando:

git clone https://github.com/TU-USUARIO/TU-REPOSITORIO.git

O descargar el proyecto como archivo ZIP desde GitHub.

## Cómo Ejecutar el Proyecto

1. Abrir NetBeans.
2. Seleccionar "Open Project".
3. Elegir la carpeta ContenidoAudiovisual.
4. Ejecutar la clase:

PruebaAudiovisual.java

El sistema mostrará los contenidos audiovisuales registrados y generará automáticamente el archivo:

contenidos.csv

## Cómo Ejecutar las Pruebas

### ActorTest

1. Abrir ActorTest.java
2. Seleccionar Run File.

Resultado esperado:

TEST ACTOR: CORRECTO

### PeliculaTest

1. Abrir PeliculaTest.java
2. Seleccionar Run File.

Resultado esperado:

TEST PELICULA: CORRECTO

## Principios SOLID Aplicados

* SRP (Single Responsibility Principle)
* OCP (Open/Closed Principle)
* LSP (Liskov Substitution Principle)
* ISP (Interface Segregation Principle)
* DIP (Dependency Inversion Principle)

## Tecnologías Utilizadas

* Java
* Apache NetBeans
* Maven
* GitHub

## Autor

Jhon Siza

## Proyecto Académico

Complementación del sistema de Contenidos Audiovisuales correspondiente a la Unidad 4.
