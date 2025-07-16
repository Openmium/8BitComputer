# 📚 8BitComputer - Información del proyecto

## 📌 ¿Qué es este proyecto?

**8BitComputer** es un proyecto educativo y experimental para diseñar y construir un **computador de 8 bits** desde cero, utilizando exclusivamente circuitos integrados lógicos de la familia **74LS**.  
El objetivo es entender cómo funciona un procesador a nivel de hardware, simulando y luego montando cada bloque fundamental: la ALU, los registros, la unidad de control, la memoria y el bus de datos.

Inspirado en la retrocomputación, este proyecto combina electrónica digital, lógica secuencial y diseño modular.

---

## ✅ Estado actual

Hasta ahora se ha completado:

- 🔢 **Bloque aritmético:**  
  Implementado un sumador/restador en complemento a dos (**Ca2**) usando sumadores TTL.

- ⚙️ **Bloque lógico:**  
  Realiza operaciones básicas como **NOT(A)**, **XOR**, **AND** y **OR** usando multiplexores y puertas lógicas.

- ✔️ **Flag de Overflow (V):**  
  Ya implementado para detectar desbordamiento aritmético.

---

## 🚧 Próximos pasos inmediatos

Los objetivos a corto plazo son:

- ➕ Añadir un **comparador** para determinar si el resultado es **mayor, igual o menor**. \\74LS85
- 🏳️ Implementar los **flags faltantes**:
  - **Z (Zero):** indica si el resultado es cero.
  - **S (Signo):** indica el signo de la operación.
- 🔗 Unir la parte aritmética y lógica para formar la **ALU completa**.

- Preparar esquemas parciales para el acumulador y registros.
- Diseñar el primer prototipo de la **unidad de control**.
- Documentar cada módulo con diagramas y explicaciones.

---

## 🗂️ Bloques pendientes por diseñar

Después de completar la ALU, los siguientes módulos clave serán:

- 🧮 **Unidad de control:**  
  Orquestará las señales de reloj, secuencia de instrucciones y habilitación de registros.

- 🗂️ **Acumulador (Registro A)** y **Registro B:**  
  Para almacenar operandos y resultados intermedios de la ALU.

- 📝 **Registro de instrucciones:**  
  Guardará la instrucción actual a ejecutar.

- ⏱️ **Contador de programa:**  
  Indicará la dirección de la siguiente instrucción.

- 🧩 **Memoria RAM y ROM (memoria de direcciones):**  
  Para guardar datos y el programa.

- 🚌 **Bus de datos y control:**  
  Conectará todos los bloques y permitirá la transferencia de datos.




