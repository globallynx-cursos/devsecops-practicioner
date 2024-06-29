# Módulo 3: Arquitectura y Planificación para DevSecOps

## Resumen del Módulo

El Módulo 3 se centra en la importancia de una planificación y arquitectura efectivas en un entorno DevSecOps. Abarca los siguientes conceptos clave:

### 1. **Arquitectura**
   - **Definición**: La arquitectura en DevSecOps incluye tanto el hardware como el software que interactúan para formar un sistema.
   - **Categorías**:
     - **Diseño del Sistema**: Enfoque en el hardware.
     - **Arquitectura del Conjunto de Instrucciones (ISA)**: Código embebido.
     - **Microarquitectura**: Rutas de datos, procesamiento y almacenamiento.

### 2. **Modelos de Arquitectura**
   - **Von Neumann**: Almacenamiento de programas en memoria antes de la ejecución.
   - **Harvard**: Dos núcleos de memoria separados para programa y datos.
   - **Arquitectura Fusionada**: Previene cuellos de botella mediante cachés.

### 3. **Monolitos vs. Microservicios**
   - **Monolitos**: Aplicaciones acopladas, desarrollo sencillo pero lentas en despliegue.
   - **Microservicios**: Componentes pequeños y desacoplados, permiten escalabilidad y respuesta rápida.

### 4. **Planificación de Arquitectura**
   - **Evaluación de Necesidades Actuales**:
     - On-premise, Cloud-using, Cloud-native, Híbrido.
   - **Migración de Arquitectura**:
     - Ejemplo: Patrón de Estrangulamiento para migrar monolitos a microservicios.
   - **Maturidad de la Arquitectura**:
     - Niveles: Caos, Definido, Repetible, Gestionado, Optimizado.

### 5. **Roles en Arquitectura y Desarrollo**
   - **Arquitecto de Software**:
     - Enfocado en la visión general y la documentación.
     - Liderazgo y habilidades analíticas.
   - **Ingeniero de Software**:
     - Enfocado en soluciones inmediatas y técnicas.
     - Desarrollo y despliegue de soluciones.

## Tabla de Apoyo para el Ejercicio

| Concepto           | Descripción | Herramientas/Recursos |
|---------------------|-------------|------------------------|
| **Flujo de Trabajo** | Pasos desde planificación hasta despliegue. | Jira, Trello, Jenkins, Docker |
| **Planificación** | Definir requerimientos y objetivos. | Lucidchart, Draw.io |
| **Desarrollo** | Construcción y codificación de la aplicación. | GitLab CI, GitHub Actions |
| **Pruebas** | Validación del código y sus funcionalidades. | JUnit, Selenium |
| **Despliegue** | Implementación del producto en producción. | Kubernetes, Docker |
| **Monitoreo** | Supervisión del rendimiento y métricas. | Prometheus, Grafana |
| **Métricas Clave** | Tiempo de ciclo, frecuencia de despliegue, tasa de éxito de pruebas. | Herramientas de análisis (DORA Metrics) |

## Resultados Esperados del Ejercicio
- Identificación de cuellos de botella y dependencias.
- Propuestas para mejorar la automatización.
- Plan de "runway" a largo plazo para el desarrollo del producto.
- Selección de métricas clave para medir el rendimiento y la eficiencia.

---

Este resumen proporciona una base teórica sólida para que los estudiantes comprendan los conceptos y cómo aplicarlos en el ejercicio práctico.
