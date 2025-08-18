# 📚 8BitComputer – Información del proyecto

## 📌 ¿Qué es este proyecto?

**8BitComputer** es un proyecto educativo cuyo objetivo es diseñar y construir un **computador de 8 bits** desde cero, utilizando únicamente circuitos integrados lógicos de la familia **74**.  
La idea es comprender cómo funciona un procesador a nivel **hardware**, simulando (en Multisim) cada bloque y, finalmente, montándolo físicamente hasta obtener un computador funcional.

---

## ✅ Estado actual

✔️ Hasta ahora se ha completado:

- 🔢 **Bloque aritmético**  
  - Sumador/restador en **complemento a dos (Ca2)** usando cuádruples sumadores totales.  
  - Flags de **Overflow (V)**, **Signo (S)** y **Cero (Z)**, con lógica adicional para **ignorar el `Cout` en operaciones de resta**.

- ⚙️ **Bloque lógico**  
  - Operaciones básicas: **NOT(A)**, **XOR**, **AND** y **OR**, usando multiplexores y puertas lógicas.  
  - **Desplazamiento lógico x2**.

---

## 🚧 Próximos pasos (corto plazo)

- 🔗 Unir los bloques aritmético y lógico para formar la **ALU completa**  
  _(actualmente hay problemas con el simulador al juntar ambos bloques, ya que interpreta algunas señales de forma incorrecta cuando se visualizan con LEDs)_.  
- Preparar esquemas parciales del **acumulador** y **registros**.  
- Diseñar el primer prototipo de la **unidad de control**.  
- Documentar cada módulo con diagramas y explicaciones.

---

## 🗂️ Bloques pendientes por diseñar

- 🧮 **Unidad de control** – generará señales de reloj, secuencias de instrucciones y habilitación de registros.  
- 📥 **Acumulador (Registro A)** y **Registro B** – operandos y resultados intermedios de la ALU.  
- 📝 **Registro de instrucciones** – almacena la instrucción actual.  
- ⏱️ **Contador de programa** – indica la dirección de la siguiente instrucción.  
- 🧩 **Memoria RAM / ROM** – para datos y programa.  
- 🚌 **Bus de datos y control** – conectará todos los bloques y permitirá la transferencia de datos.
