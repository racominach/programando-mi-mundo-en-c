# Fase 1: Introducción y Entorno
## Historia de C y su influencia en sistemas operativos.
### 📜 EL GÉNESIS DE LA COMPUTACIÓN MODERNA: EL LENGUAJE C
**1. Contexto Histórico: Del Caos al Control Total 🛠️**

Antes de 1972, la programación era una "Torre de Babel". Cada computadora hablaba su propio Lenguaje Ensamblador. Si escribías un programa para una máquina IBM, no funcionaba en una DEC PDP-11.
  * El Héroe: Dennis Ritchie, en los Laboratorios Bell, buscaba un lenguaje "intermedio".
  * La Innovación: C permitió que los humanos escribieran algo parecido al inglés, pero que se tradujera casi directamente a impulsos eléctricos (Código de Máquina).
  * El Big Bang: En 1973, Ritchie y Ken Thompson reescribieron el núcleo (Kernel) de UNIX usando C. Ese fue el momento en que el software se volvió inmortal.


**🏛️ 2. Influencia en los Sistemas Operativos (OS)**

C no es un lenguaje más; es el material de construcción de los cimientos digitales.

* **Portabilidad Revolucionaria:** Gracias a C, un Sistema Operativo podía ser "mudado" de una computadora a otra simplemente recompilando el código.
* **El Árbol Genealógico:**
  * UNIX: El ancestro directo de casi todo.
  * GNU/Linux: El motor de los servidores de Google, la NASA y el 100% de las Supercomputadoras. Escrito en C.
  * Windows: Aunque usa C++, sus capas más profundas (el Kernel NT) están forjadas en C.
  * macOS/iOS/Android: Sus núcleos (XNU y Linux Kernel) respiran C.

**🚀 3. ¿Por qué C domina las Industrias Críticas? (Deep Dive)**
* **🛰️ Aeroespacial (SpaceX / NASA):**
  * **Tic Informático:** En un cohete, el software debe ser determinista. C no tiene "Garbage Collector" (un proceso automático que limpia la memoria y pausa el programa). En C, tú decides cuándo se libera cada byte. Si el motor necesita apagarse en 0.001s, C lo garantiza.
* **🎮 Motores de Videojuegos (AAA):**
  * **Tic Informático:** Los sombreadores (shaders) y las físicas de colisión requieren acceso directo a los registros de la GPU. C permite hablarle al hardware sin intermediarios lentos.
* **🧠 Inteligencia Artificial:**
  * **Tic Informático:** Aunque Python es popular, es "lento". Las librerías como PyTorch o TensorFlow delegan los cálculos de matrices gigantes a funciones escritas en C/C++ para aprovechar el  paralelismo del procesador.
