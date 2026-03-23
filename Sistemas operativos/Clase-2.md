# 🖥️ Sistemas Operativos – Historia (Clase 1.2)

## 📜 Introducción

Los sistemas operativos evolucionaron junto con las computadoras.  
Cada avance en hardware generó cambios en la forma en que se usaban las máquinas.

👉 Importante:
No es una evolución ordenada perfecta, sino con:
- avances desiguales  
- errores  
- tecnologías que se superponen  

---

## 🧠 Origen de las computadoras

La primera idea de computadora fue la **máquina analítica** de Charles Babbage.

- Era mecánica → no funcionó correctamente  
- No tenía sistema operativo  
- Ya existía la idea de **software**

👉 Dato clave:
Ada Lovelace fue la primera programadora.

---

## ⚙️ Primera generación (1945–1955): Tubos al vacío

### 📌 Características
- Computadoras muy primitivas  
- Uso de tubos al vacío  
- Programación en lenguaje máquina  
- No existían sistemas operativos  

### 💻 Funcionamiento
- Todo era manual  
- Se programaba conectando cables (plugboards)  
- Un mismo grupo hacía TODO:
  - diseñar  
  - programar  
  - operar  

### ⚠️ Problemas
- Muy lentas  
- Poco confiables  
- Mucho tiempo perdido  

### 📥 Mejora
- Aparición de **tarjetas perforadas**

---

## 🔌 Segunda generación (1955–1965): Transistores y procesamiento por lotes

### 📌 Cambios importantes
- Se reemplazan los tubos por **transistores**
- Computadoras más confiables
- Surgen los **mainframes**

### 👥 Separación de roles
- Programadores  
- Operadores  
- Técnicos  

---

### 📦 Procesamiento por lotes (Batch)

👉 Idea clave:
Agrupar varios trabajos y ejecutarlos automáticamente.

### 🔄 Cómo funcionaba
1. Programas en tarjetas perforadas  
2. Se cargaban en una cinta  
3. La computadora ejecutaba uno tras otro  

### ✔ Ventaja
- Menos tiempo perdido  
- Mayor eficiencia  

---

### 🧠 Primeros “sistemas operativos”

Eran programas básicos que:
- leían trabajos  
- los ejecutaban automáticamente  

Ejemplo:
- FMS  
- IBSYS  

---

## 🔗 Tercera generación (1965–1980): Circuitos integrados y multiprogramación

### 📌 Innovación clave
- Uso de **circuitos integrados (IC)**
- Mayor potencia y menor costo

---

### 🖥️ Familia de computadoras (IBM System/360)

👉 Idea:
Una misma arquitectura para distintas máquinas

✔ Beneficios:
- Compatibilidad de programas  
- Escalabilidad  

---

### ⚠️ Problema
- Sistemas operativos muy complejos  
- Millones de líneas de código  
- Muchos errores  

Ejemplo:
- OS/360  

---

### 🔥 Multiprogramación (LO MÁS IMPORTANTE)

👉 Concepto clave:

Permite que varios programas estén en memoria al mismo tiempo.

### ⚙️ Cómo funciona
- Si un programa espera (por ejemplo, entrada/salida)  
- Otro usa la CPU  

✔ Resultado:
- CPU casi siempre ocupada  
- Mayor eficiencia  

---

## 💻 Cuarta generación (1980–actualidad): Computadoras personales

### 📌 Cambio clave
- Aparición de microprocesadores  
- Nacen las computadoras personales (PC)

---

### 🧠 Sistemas operativos importantes

#### 🔹 CP/M
- Primer SO popular en microcomputadoras  
- Creado por Gary Kildall  

---

#### 🔹 MS-DOS
- Creado por Microsoft  
- Dominó el mercado  

👉 Clave del éxito:
Se vendía junto con las computadoras

---

#### 🔹 Windows
- Introduce interfaz gráfica (GUI)  
- Evolución:
  - Windows 95  
  - Windows 98  
  - Windows XP  

---

#### 🔹 UNIX y Linux
- Muy usados en servidores  
- Linux crece como alternativa a Windows  

---

### 🖱️ Interfaz gráfica (GUI)

- Ventanas  
- Íconos  
- Mouse  

👉 Hace las computadoras más fáciles de usar

---

## 🌐 Situación actual

Hoy existen múltiples sistemas operativos:

- Windows  
- Linux  
- macOS  

Se usan para:
- computadoras personales  
- servidores  
- redes  
- sistemas complejos  

---

## 🧠 Conclusión

Los sistemas operativos evolucionaron desde no existir hasta convertirse en sistemas complejos que:

- administran recursos  
- permiten ejecutar múltiples programas  
- hacen posible el uso cotidiano de computadoras  

---
# 🧠 Multiprogramación

La **multiprogramación** es una técnica que surge en la tercera generación de computadoras (1965–1980) con el objetivo de mejorar el uso de la CPU.

---

## ⚙️ Problema anterior

En sistemas anteriores, como los de segunda generación:

- La computadora ejecutaba un solo trabajo a la vez  
- Cuando ese trabajo necesitaba realizar una operación de entrada/salida (E/S), como leer una cinta o acceder a un dispositivo  
👉 la CPU quedaba inactiva hasta que terminara la operación  

Esto generaba un gran desperdicio de tiempo, especialmente en aplicaciones donde las operaciones de E/S podían ocupar entre el 80% y 90% del tiempo total.

---

## 🔥 Solución: multiprogramación

La multiprogramación consiste en:

👉 **Mantener varios trabajos en memoria al mismo tiempo**

De esta forma:

- Cuando un trabajo se detiene esperando una operación de E/S  
- Otro trabajo puede usar la CPU  

---

## 💻 Funcionamiento

- La memoria se divide en varias partes  
- En cada una se carga un trabajo distinto  
- El sistema operativo administra cuál se ejecuta  

Esto permite que:

✔ La CPU esté ocupada casi todo el tiempo  
✔ Se reduzcan los tiempos muertos  

---

## 🧩 Requisitos

Para poder implementar multiprogramación, el sistema necesita:

- Mecanismos de protección para que los trabajos no interfieran entre sí  
- Hardware que permita manejar varios programas en memoria  

---

## 🚀 Resultado

Gracias a la multiprogramación:

- Se mejora significativamente el rendimiento del sistema  
- Se aprovecha mejor la CPU  
- Se optimiza el uso de los recursos  

---

## 🧠 Idea clave

La multiprogramación permite que la computadora **no se detenga cuando un programa está esperando**, sino que continúe ejecutando otros trabajos.


## 📝 Actividades

1) ¿Qué es la multiprogramación?  

2) La idea de una familia de computadoras fue introducida en la década de 1960 con los mainframes IBM System/360.  
¿Está muerta ahora esta idea o sigue en pie?  

3) ¿A qué se le llama “internet de las cosas”?  
¿Conoce algún sistema operativo en la nube?  
¿Sería eso otra generación?  

1) La multiprogramacion entoces, es cuando la cpu no se encarga de una tarea y espera a que termine para ejecutar otra, sino que divide la memoria y permite ejecutar muchos programas al mismo tiempo ahorrando asi, mas tiempo y no desperdiciarlo de una tarea en una. En resumen la multiprogramación es una técnica que permite mantener varios programas en memoria al mismo tiempo, de modo que cuando uno se detiene por una operación de entrada/salida, otro pueda usar la CPU, evitando tiempos muertos y mejorando la eficiencia del sistema.

2) Sí, sigue en pie. Hoy en día existen familias de computadoras y dispositivos compatibles entre sí (por ejemplo, distintas versiones de procesadores o sistemas operativos) que permiten ejecutar los mismos programas con diferentes niveles de rendimiento, manteniendo la compatibilidad.

3) El internet de las cosas (IoT) se refiere a la conexión de objetos físicos a internet (como electrodomésticos, sensores o autos) que pueden recopilar y compartir datos.

Un ejemplo de sistema operativo en la nube es Windows Azure o sistemas basados en Linux que funcionan en servidores remotos.

Esto podría considerarse una evolución más que una nueva generación, ya que continúa el desarrollo de los sistemas operativos adaptados a nuevas tecnologías. Otro ejemplo puede ser tesla, ya que es un objeto fisico pero esta conectado a la internet, por ejemplo puede recibir actualizaciones remotas. 