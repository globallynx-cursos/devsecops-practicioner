# Módulo 3: Arquitectura y Planificación para DevSecOps 🚀

## Resumen del Módulo

El Módulo 3 se centra en la importancia de una planificación y arquitectura efectivas en un entorno DevSecOps. Abarca los siguientes conceptos clave:

### 1. **Arquitectura** 🏗️
   - **Definición**: La arquitectura en DevSecOps incluye tanto el hardware como el software que interactúan para formar un sistema.
   - **Categorías**:
     - **Diseño del Sistema**: 
       - Enfoque en el hardware del sistema.
       - Incluye servidores, redes y dispositivos de almacenamiento.
     - **Arquitectura del Conjunto de Instrucciones (ISA)**: 
       - Código embebido que dicta cómo el software se comunica con el hardware.
       - Ejemplo: Arquitecturas RISC vs. CISC.
     - **Microarquitectura**: 
       - Detalla cómo los componentes individuales del hardware se comunican y procesan datos.
       - Involucra rutas de datos, caché, y unidades de procesamiento.

### 2. **Modelos de Arquitectura** 📐
   - **Von Neumann**:
     - Almacenamiento de programas y datos en la misma memoria.
     - Proceso secuencial que puede causar cuellos de botella.
   - **Harvard**:
     - Uso de memoria separada para programas y datos.
     - Mejora la eficiencia al permitir procesamiento paralelo.
   - **Arquitectura Fusionada**:
     - Combina elementos de Von Neumann y Harvard.
     - Utiliza caché para mejorar el rendimiento y prevenir cuellos de botella.

### 3. **Monolitos vs. Microservicios** 🖥️🔗
   - **Monolitos**:
     - Aplicaciones acopladas con una única base de código.
     - Pros: Desarrollo sencillo, buen rendimiento inicial.
     - Contras: Difícil de escalar, lento en despliegue.
   - **Microservicios**:
     - Aplicaciones divididas en componentes pequeños y autónomos.
     - Pros: Escalabilidad, rápida respuesta a cambios.
     - Contras: Complejidad en el desarrollo, requiere una arquitectura de red eficiente.

### 4. **Planificación de Arquitectura** 🛠️
   - **Evaluación de Necesidades Actuales**:
     - **On-premise**: Soluciones alojadas internamente.
     - **Cloud-using**: Uso de servicios en la nube para ciertas funciones.
     - **Cloud-native**: Diseñado específicamente para entornos en la nube.
     - **Híbrido**: Combinación de soluciones on-premise y en la nube.
   - **Migración de Arquitectura**:
     - **Patrón de Estrangulamiento**: Migración gradual de monolitos a microservicios.
   - **Maturidad de la Arquitectura**:
     - Niveles: **Caos**, **Definido**, **Repetible**, **Gestionado**, **Optimizado**.

### 5. **Arquitectura basada en APIs** 🌐
   - **Definición**: APIs permiten la comunicación entre diferentes servicios o componentes de software.
   - **Ventajas**:
     - Facilitan la integración y la interoperabilidad.
     - Permiten la escalabilidad y la modularidad.
   - **Desafíos**:
     - Gestión de versiones y compatibilidad.
     - Seguridad en la exposición de APIs.

### 6. **Arquitectura Serverless** ☁️
   - **Definición**: Modelo de ejecución en el que el proveedor de la nube gestiona la infraestructura y la asignación de recursos.
   - **Ventajas**:
     - Escalado automático.
     - Pago por uso.
   - **Desafíos**:
     - Latencia en la inicialización.
     - Limitaciones en el tiempo de ejecución y el entorno.

### 7. **Arquitectura Event-Driven** ⚙️
   - **Definición**: Sistemas que reaccionan a eventos, donde un evento es cualquier cambio de estado significativo.
   - **Ventajas**:
     - Alta escalabilidad y flexibilidad.
     - Mejor manejo de datos en tiempo real.
   - **Desafíos**:
     - Complejidad en la gestión de eventos y dependencias.
     - Dificultad en la depuración y el seguimiento de eventos.

### 8. **Patrones de Migración** 🔄
   - **Patrón de Estrangulamiento**:
     - Migración gradual de un sistema monolítico a microservicios.
     - Permite la coexistencia de ambos sistemas durante la transición.
   - **Big Bang**:
     - Migración completa en un solo paso.
     - Riesgos altos debido a la gran cantidad de cambios simultáneos.

### 9. **Roles en Arquitectura y Desarrollo** 👩‍💻👨‍💻
   - **Arquitecto de Software**:
     - Enfocado en la visión general, documentación y planificación a largo plazo.
     - Habilidades de liderazgo y analíticas.
   - **Ingeniero de Software**:
     - Enfocado en soluciones inmediatas y técnicas.
     - Desarrollo y despliegue de soluciones.

## Tabla conceptos herramientas📊

| Concepto           | Descripción | Herramientas/Recursos |
|---------------------|-------------|------------------------|
| **Flujo de Trabajo** 🛠️ | Pasos desde planificación hasta despliegue. | Jira, Trello, Jenkins, Docker |
| **Planificación** 📝 | Definir requerimientos y objetivos. | Lucidchart, Draw.io |
| **Desarrollo** 💻 | Construcción y codificación de la aplicación. | GitLab CI, GitHub Actions |
| **Pruebas** ✔️ | Validación del código y sus funcionalidades. | JUnit, Selenium |
| **Despliegue** 🚀 | Implementación del producto en producción. | Kubernetes, Docker |
| **Monitoreo** 📈 | Supervisión del rendimiento y métricas. | Prometheus, Grafana |
| **Métricas Clave** 📊 | Tiempo de ciclo, frecuencia de despliegue, tasa de éxito de pruebas. | Herramientas de análisis (DORA Metrics) |

