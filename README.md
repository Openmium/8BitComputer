# 📚 8BitComputer - Información del proyecto

## 📌 ¿Qué es este proyecto?

**8BitComputer** es un proyecto educativo para diseñar y construir un **computador de 8 bits** desde cero, utilizando exclusivamente circuitos integrados lógicos de la familia **74**.  
El objetivo es entender cómo funciona un procesador a nivel de hardware, simulando (en Multisim) y luego montando cada bloque hasta tener un computador funcional.

---

## ✅ Estado actual

Hasta ahora se ha completado:

- 🔢 **Bloque aritmético:**  
  Implementado un sumador/restador en complemento a dos (**Ca2**) usando sumadores TTL.
  - ✔️ **Flag de Overflow (V):**  
  Ya implementado para detectar desbordamiento aritmético.
  - ✔️ **Flag de Signo (S):**  
  Ya implementado.
  - ✔️ **Flag de Cero (Z):**  
  Ya implementado, con logica adicional para **ignorar el `Cout` en la resta**.

- ⚙️ **Bloque lógico:**  
  Realiza operaciones básicas como **NOT(A)**, **XOR**, **AND** y **OR** usando multiplexores y puertas lógicas.


---

## 🚧 Próximos pasos inmediatos

Los objetivos a corto plazo son:

- ➕ Añadir un **comparador** para determinar si el resultado es **mayor, igual o menor**. (similares a 74LS85 (quiza mas adelante se terminen usando si Multisim se sobrecarga)).
- ➡️ Implementar desplazamientos logicos para por lo menos tener multiplicaciones (y divisiones tal vez) por 2.
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




