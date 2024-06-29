# Resumen de Conway's Law 📜

**Conway's Law** establece que la estructura de un sistema refleja la estructura de comunicación de la organización que lo diseñó. Si la comunicación entre los desarrolladores no se alinea con el diseño del sistema, surgirán problemas.

## Ejemplos

| Tipo de Equipo                     | Descripción                                                                                      |
|------------------------------------|--------------------------------------------------------------------------------------------------|
| **Equipos Funcionales** 🖥️       | Desarrolladores de frontend trabajando juntos crean una interfaz cohesiva. Otros equipos enfrentan dificultades de comunicación. |
| **Equipos por Capas** 🏗️          | Divididos en frontend, backend y base de datos. Especialización por área, pero colaboración necesaria para interfaces.          |
| **Equipos por Ciclo de Vida** 🔄   | Desarrollo, pruebas y operaciones con comunicación a través de procesos de traspaso. La arquitectura refleja esta estructura.    |
| **Equipos Multifuncionales** 🛠️   | Equipos centrados en dominios empresariales específicos, creando una arquitectura verticalmente segmentada. Similar al DDD.     |

## Implicaciones

- **Inverse Conway Maneuver**: Para lograr una arquitectura deseada, se puede reorganizar la estructura de equipos para que coincida con esa arquitectura.
- Esto funciona bien con microservicios, donde cada equipo es responsable de sus servicios y APIs. 🔧

## Conclusión

Conway's Law es un factor a considerar al diseñar la arquitectura de software y al organizar equipos, y puede ser usado estratégicamente para fomentar la arquitectura deseada. 🚀
