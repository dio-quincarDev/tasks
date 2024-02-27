# tasks
Arquitectura Hexagonal Introduccion


# Aprendiendo Arquitectura Hexagonal con Java, Spring Boot y MySQL

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)

## Descripción

Este repositorio contiene ejemplos de código para aprender a implementar la arquitectura hexagonal en una aplicación Java con Spring Boot y MySQL.

La arquitectura hexagonal, también conocida como puertos y adaptadores, separa la lógica de negocio de nuestra aplicación de los detalles de infraestructura como la base de datos, el framework web, etc. 

Esto nos permite desacoplar completamente el core de nuestra aplicación y hace que sea más fácil de probar y mantener a lo largo del tiempo.

## Diagrama

![Diagrama Arquitectura Hexagonal](hexagonal-architecture.png)

Como podemos ver en el diagrama, nuestro core contiene la lógica de negocio y los casos de uso de la aplicación. Este core se comunica con el exterior a través de puertos y adaptadores:

- **Puertos**: Interfaces que definen cómo el exterior se comunica con el core.
- **Adaptadores**: Implementaciones concretas de los puertos que se comunican con infraestructura externa como la base de datos. 

De esta forma el core sólo depende de abstracciones y no está acoplado a nada externo.

## Tecnologías

- Java 17
- Spring Boot
- MySQL
- JUnit
- Maven

## Contenido

En este repositorio encontrarás:

- Ejemplos de código para implementar capas hexagonales
- Tests unitarios con JUnit
- Configuración de Spring Boot y MySQL  

## Como usar este repositorio

1. Clona este repositorio
2. Importa el proyecto Maven en tu IDE favorito
3. Ejecuta los tests JUnit para ver ejemplos funcionando
4. Lee el código fuente para entender la implementación
5. Modifica y experimenta para aprender

## Autor

- Diogenes Quintero
- [Mi canal de YouTube](https://www.youtube.com/watch?v=JD_ZL3Bnaog) 

¡Espero que este repositorio te sea útil para aprender arquitectura hexagonal y mejores prácticas con Java y Spring Boot!

**Canal de YouTube:**

* **[https://www.youtube.com/user/canal](https://www.youtube.com/watch?v=JD_ZL3Bnaog)**



**Contribuciones:**

Se anima a la comunidad a contribuir al proyecto con mejoras, correcciones de errores y nuevos ejemplos.

**Licencia:**

Este proyecto está licenciado bajo la licencia **Apache 2.0**.

**Cómo empezar:**

1. Clonar el repositorio:

```
git clone https://github.com/NombreDeUsuario/RepositorioHexagonal.git
```

2. Importar el proyecto en tu IDE favorito.

3. Configurar la base de datos MySQL.

4. Ejecutar la aplicación:

```
mvn spring-boot:run
```

5. Acceder a la API REST:

```
http://localhost:8080/api
```



**Agradecimientos:**

A la comunidad de desarrolladores por su apoyo y colaboración.

**¡Esperamos que este repositorio te sea útil para aprender sobre la Arquitectura Hexagonal!**


