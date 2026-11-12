# Dispositivo Electrónico Lector y Transmisor de 9 Variables (Proyecto de Grado)

Sistema embebido avanzado desarrollado como **Proyecto de Grado**, diseñado para la adquisición simultánea, acondicionamiento y transmisión de datos provenientes de **9 variables físicas**. La arquitectura integra hardware electrónico de sensado con firmware optimizado para garantizar lecturas estables, sincronizadas y confiables en tiempo real.

## Características principales
* **Adquisición multicanal (9 variables):** Lectura concurrente y calibración de múltiples sensores para el monitoreo integral del entorno o proceso instrumentado.
* **Procesamiento y acondicionamiento de señales:** Filtrado digital, conversión analógica/digital y estructuración de tramas de datos para evitar pérdida de información o interferencias.
* **Transmisión de datos / Telemetría:** Envío continuo y estructurado de las 9 variables hacia una estación receptora, plataforma de monitoreo o interfaz de visualización.
* **Arquitectura embebida robusta:** Diseño modular pensado para operar de forma autónoma, estable y escalable en entornos reales.

## Arquitectura y herramientas utilizadas
* **Firmware y Programación:** C / C++ *(o Python / MicroPython, según el entorno utilizado)*
* **Hardware y Electrónica:** Microcontrolador embebido, etapa de sensado de 9 canales y módulo de comunicación
* **Control de versiones:** Git y GitHub Desktop