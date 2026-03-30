# Resumen: Tipos de Sistemas Operativos (Clase #3)

[cite_start]Este documento resume los nueve tipos de sistemas operativos descritos en la clase, clasificados principalmente por su capacidad de cómputo y el entorno en el que operan[cite: 2, 5].

---

## 1. Sistemas de Mainframe
* [cite_start]**Contexto:** Computadoras del tamaño de una habitación en centros de datos corporativos[cite: 7].
* [cite_start]**Fuerza:** Su enorme capacidad de Entrada/Salida (E/S)[cite: 8]. [cite_start]Pueden manejar miles de discos y millones de gigabytes[cite: 9].
* **Servicios:**
    * [cite_start]**Procesamiento por lotes:** Tareas de rutina sin usuario (ej. reclamos de seguros)[cite: 14, 15].
    * [cite_start]**Transacciones:** Muchas peticiones pequeñas (ej. cheques bancarios)[cite: 16].
    * [cite_start]**Tiempo compartido:** Varios usuarios remotos a la vez[cite: 18].
* [cite_start]**Ejemplo:** OS/390 (actualmente reemplazados a menudo por Linux)[cite: 20, 21].

## 2. Sistemas de Servidores
* [cite_start]**Función:** Dan servicio a múltiples usuarios a través de una red, permitiendo compartir hardware y software[cite: 25].
* [cite_start]**Uso común:** Servidores de archivos, de impresión o sitios Web[cite: 26].
* [cite_start]**Ejemplos:** Solaris, FreeBSD, Linux y Windows Server[cite: 28].

## 3. Sistemas de Multiprocesadores
* [cite_start]**Definición:** Sistemas que conectan varias CPU en un solo equipo para obtener más potencia[cite: 30].
* [cite_start]**Actualidad:** Los chips multinúcleo modernos han llevado esta tecnología a las PCs comunes[cite: 33].
* [cite_start]**SO:** Suelen ser variantes de sistemas de servidor con funciones especiales de comunicación y consistencia[cite: 32].

## 4. Sistemas de Computadoras Personales (PC)
* [cite_start]**Objetivo:** Proporcionar buen soporte a un solo usuario para tareas como oficina y acceso a Internet[cite: 40, 41].
* [cite_start]**Características:** Soportan multiprogramación (muchos programas abiertos al iniciar)[cite: 39].
* [cite_start]**Ejemplos:** Windows, macOS, Linux[cite: 42].

## 5. Sistemas de Computadoras de Bolsillo (Handheld)
* [cite_start]**Dispositivos:** PDAs y teléfonos celulares sofisticados[cite: 47, 48].
* [cite_start]**Características:** Tienen CPUs de 32 bits y sistemas operativos cada vez más complejos que permiten instalar apps de terceros[cite: 50, 52].
* [cite_start]**Ejemplos clásicos:** Symbian OS, Palm OS[cite: 54].

## 6. Sistemas Integrados (Embebidos)
* [cite_start]**Definición:** Operan en dispositivos que no se ven como computadoras (microondas, autos, reproductores MP3)[cite: 56, 57].
* [cite_start]**Diferencia clave:** **No aceptan software instalado por el usuario**; todo el software es confiable y está en ROM[cite: 56, 58, 59].
* [cite_start]**Ejemplos:** QNX, VxWorks[cite: 61].

## 7. Sistemas de Nodos Sensores
* [cite_start]**Estructura:** Redes de computadoras diminutas con sensores ambientales y radios integrados[cite: 66].
* [cite_start]**Restricciones:** Energía muy limitada (baterías) y memoria RAM escasa[cite: 67, 71].
* [cite_start]**Función:** Responden a eventos externos o mediciones periódicas[cite: 70].
* [cite_start]**Ejemplo:** TinyOS[cite: 74].

## 8. Sistemas en Tiempo Real
* [cite_start]**Clave:** El tiempo es el parámetro crítico[cite: 77].
* **Tipos:**
    * [cite_start]**Duro:** La acción *debe* ocurrir en un momento exacto (ej. robótica industrial, militar)[cite: 82, 83].
    * [cite_start]**Suave:** Es aceptable fallar el tiempo ocasionalmente (ej. audio digital, telefonía)[cite: 85, 87].
* [cite_start]**Ejemplo:** e-Cos[cite: 89].

## 9. Sistemas de Tarjetas Inteligentes (Smart Cards)
* [cite_start]**Escala:** Son los sistemas más pequeños; operan en un chip dentro de una tarjeta de crédito[cite: 96, 97].
* [cite_start]**Limitaciones:** Memoria y poder de procesamiento severamente restringidos[cite: 98].
* [cite_start]**Funciones:** Pagos electrónicos o funciones múltiples mediante Java Card (JVM)[cite: 100, 102].