# Módulo 4: Creación de Infraestructura DevSecOps

## Análisis de Tráfico 🚦

- **Visibilidad a través de las Capas OSI 2-7**:
  - Tráfico norte-sur ↔️ y este-oeste ↕️
  - Uso de TAP/SPAN para monitorización 🔍

- **Identificación de Hábitos de Comunicación**:
  - Número de terminales por día 🖥️
  - Duración promedio de las llamadas 📞

- **Establecimiento de Líneas Base y Controles**:
  - Identificación de Indicadores de Compromiso (IOC) 🚨
  - Detección de fallos y problemas de mantenimiento 🛠️

- **Conversión a la Matriz MITRE ATT&CK**:
  - Mapeo de comportamientos a tácticas y técnicas conocidas 🗺️

- **Comprensión de Opciones de Remediación**:
  - Estrategias para la respuesta a incidentes basadas en el análisis del tráfico 🔧

### Requisitos para el Análisis de Tráfico de Red (NTA):
- Visibilidad amplia 👁️
- Verificación de cifrado 🔐
- Seguimiento de entidades 📊
- Línea base integral 📈
- Detección y respuesta rápidas ⚡

## Herramientas y Casos de Uso 🛠️

| **Herramienta**      | **Casos de Uso**                                      | **Ejemplos**                        |
|-----------------------|-------------------------------------------------------|-------------------------------------|
| [**Wireshark**](https://www.wireshark.org) | Análisis de paquetes, detección de anomalías          | Monitoreo de protocolos, resolución de problemas de red |
| [**Splunk**](https://www.splunk.com) | Análisis de registros, visualización de datos         | Detección de intrusiones, análisis de tráfico en tiempo real |
| [**Nagios**](https://www.nagios.com) | Monitoreo de sistemas, detección de fallos            | Alertas sobre problemas de red, seguimiento del rendimiento del servidor |
| [**Zeek (Bro)**](https://zeek.org) | Monitoreo de tráfico de red, detección de amenazas    | Análisis de patrones de tráfico, generación de alertas de seguridad |
| [**Suricata**](https://suricata.io) | IDS/IPS, análisis de tráfico en profundidad           | Detección de intrusiones, prevención de ataques |
| [**TAP/SPAN**](https://www.cisco.com/c/en/us/products/switches/what-is-tap-span.html) | Monitoreo del tráfico de red, visibilidad de red      | Captura de tráfico para análisis, detección de comportamiento sospechoso |
| [**Nmap**](https://nmap.org) | Escaneo de red, detección de hosts y servicios        | Evaluación de seguridad, identificación de puertos abiertos |

## Ejemplo de Análisis de Tráfico 📊

**Contexto**: Una organización detecta un aumento inusual en el tráfico de red durante las horas nocturnas. Utilizando herramientas de análisis de tráfico, identifican patrones sospechosos.

- **Herramienta Utilizada**: Wireshark 🛠️
- **Acciones**:
  1. **Captura de Tráfico**: Monitorizan el tráfico en las capas OSI 2-7.
  2. **Análisis de Paquetes**: Revisan paquetes específicos para identificar anomalías, como intentos de conexión a direcciones IP desconocidas.
  3. **Detección de IOC**: Utilizan la matriz MITRE ATT&CK para mapear comportamientos a posibles tácticas y técnicas de amenazas.
- **Resultado**: Descubren un intento de acceso no autorizado desde una IP externa, lo que lleva a medidas de bloqueo y revisión de la seguridad del firewall.

## Ejercicio Práctico 📝

**Objetivo**: Practicar la detección de tráfico malicioso utilizando herramientas de análisis.

1. **Configuración**:
   - Instala Wireshark en tu computadora.
   - Asegúrate de tener permisos para capturar paquetes en tu red local.

2. **Captura de Tráfico**:
   - Inicia una captura de tráfico en la interfaz de red adecuada.
   - Realiza varias actividades en tu red, como navegar por sitios web o descargar archivos.

3. **Análisis**:
   - Detén la captura después de unos minutos.
   - Utiliza filtros para aislar el tráfico HTTP y HTTPS.
   - Identifica cualquier comunicación inusual, como intentos de conexión a puertos no estándar o a IPs desconocidas.

4. **Documentación**:
   - Registra cualquier tráfico sospechoso.
   - Mapea el tráfico identificado con la matriz MITRE ATT&CK para entender posibles amenazas.

5. **Discusión**:
   - Reflexiona sobre qué medidas tomarías si se detectaran patrones sospechosos en un entorno real.
   - Considera cómo podrías establecer una línea base para detectar anomalías en el futuro.

## Conclusión 📌

El análisis de tráfico es una parte crucial de la infraestructura DevSecOps, proporcionando visibilidad y detección de amenazas en la red. La implementación de herramientas y la comprensión de patrones de tráfico ayudan a las organizaciones a mejorar su postura de seguridad y responder rápidamente a incidentes.
