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
# Diagrama de Arquitectura Hexagonal en Java

## Capas

1. **Dominio (Core)**:
   - Contiene la lógica de negocio central.
   - Implementación independiente de la infraestructura externa.
   - Oculta los detalles de implementación de las capas externas.

2. **Aplicación (Application)**:
   - Actúa como mediador entre el dominio y la infraestructura.
   - Orquesta la interacción entre las capas.
   - Define los casos de uso y servicios de aplicación.

3. **Infraestructura (Framework)**:
   - Contiene detalles de implementación para interactuar con el mundo exterior.
   - Adaptadores para comunicarse con bases de datos, servicios web, etc.

## Componentes

- **Puertos (Ports)**:
  - Puertos de entrada (Inbound Ports): Interfaces que exponen la lógica central al mundo exterior (por ejemplo, servicios REST).
  - Puertos de salida (Outbound Ports): Interfaces que facilitan la comunicación con sistemas externos (por ejemplo, repositorios).

- **Adaptadores (Adapters)**:
  - Adaptadores primarios (Primary Adapters):
    - Controladores web (por ejemplo, controladores REST).
    - Traducen las solicitudes del mundo exterior al lenguaje de la aplicación.
  - Adaptadores secundarios (Secondary Adapters):
    - Implementan puertos de salida (por ejemplo, repositorios JDBC).
    - Traducen la comunicación entre objetos externos y el núcleo de la aplicación.

## Ejemplo Ilustrativo

Supongamos que estamos diseñando una aplicación de **servicio de pasteles** utilizando **Spring Boot**. El diagrama mostraría cómo las diferentes capas interactúan a través de puertos y adaptadores.

¡Espero que este diagrama te ayude a comprender mejor la arquitectura hexagonal en Java! 🍰🎨
https://www.bing.com/images/search?view=detailV2&ccid=UorD3zxe&id=C224674984C51ACD8B0F6CC91174A41F2751C03F&thid=OIP.UorD3zxe2_RZtgkNzvLybwHaGs&mediaurl=https%3a%2f%2flh5.googleusercontent.com%2f7kTf1V74nvHNgUnk6IeXhrgOJgd9K9cdysLhMU4XTLJpy0Kfyp7EPhAKnmKz1bwXpD1xIjyaWHM7FNvK_adxZIv5TKldV8fZm29Br86mt3QJvyLhfc9YAdTo76_N3_LFevHdih98&cdnurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR.528ac3df3c5edbf459b6090dcef2f26f%3frik%3dP8BRJx%252bkdBHJbA%26pid%3dImgRaw%26r%3d0&exph=457&expw=506&q=diagrama+de+arquitectura+hexagonal+en+java&simid=608003950585137109&FORM=IRPRST&ck=F805EDD00220A8BCEC8328A3F37FC7DC&selectedIndex=0&itb=0&idpp=overlayview&ajaxhist=0&ajaxserp=0


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

- DIF
- ¡Espero que este repositorio te sea útil para aprender arquitectura hexagonal y mejores prácticas con Java y Spring Boot!

**Canal de YouTube:**

* **[https://www.youtube.com/user/canal](https://www.youtube.com/watch?v=JD_ZL3Bnaog)**



**Contribuciones:**

Se anima a la comunidad a contribuir al proyecto con mejoras, correcciones de errores y nuevos ejemplos.




**Agradecimientos:**

A la comunidad de desarrolladores por su apoyo y colaboración.

**¡Esperamos que este repositorio te sea útil para aprender sobre la Arquitectura Hexagonal!**


