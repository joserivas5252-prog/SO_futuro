# SO_futuro

# ChronoOS: Sistema Operativo de Tiempo Real para Edge Computing Industrial

ChronoOS es un sistema operativo ficticio de tiempo real duro (Hard Real-Time) diseñado para entornos críticos de Edge Computing e Internet de las Cosas (IoT) industrial, donde la latencia y la garantía temporal son vitales. Su arquitectura, funcionalidades y mecanismos están orientados a maximizar la predictibilidad y fiabilidad en aplicaciones como control de plantas de energía, robótica quirúrgica y vehículos autónomos.

---

## Propósito

Ofrecer un sistema ultraligero y determinista que gestione redes de sensores industriales, actuadores y dispositivos con recursos limitados, garantizando que ninguna tarea crítica falle por retrasos o errores del sistema operativo.

---

## Características principales

- **Núcleo:** Microkernel estricto para minimizar latencia y riesgos de bloqueos.
- **Planificación:** Earliest Deadline First con reprogramación estática para evitar inanición.
- **Gestión Memoria:** Asignación fija y sin swapping, usando particiones físicas y aislamiento con MMU.
- **Sistema de archivos:** ChronoFS, optimizado para memoria no volátil y almacenamiento determinista.
- **Seguridad:** Autenticación PKI con hardware seguro, arranque medido y control de acceso basado en roles inmutables.
- **Interfaz de usuario:** Sistema headless, con API de telemetría determinista para integración con sistemas SCADA.

---

## Uso del repositorio

Esta carpeta contiene los archivos con la documentación y esquemas para facilitar el estudio y futura implementación de ChronoOS.
