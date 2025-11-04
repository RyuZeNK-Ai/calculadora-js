# 💻 Calculadora-js
Se hace migracion de calculadora python a javascript

## 🧠 Aprendizaje del ejercicio

1. ¿Cómo se definen funciones en JavaScript?

🔎Para definir funciones:
- JavaScript usa 'function' o arrow functions (=>)
- Python usa 'def'

🔑Llaves vs Identación:
- JavaScript usa llaves {} para delimitar el cuerpo de la función
- Python usa indentación obligatoria (espacios o tabs)

💡Uso de paréntesis:
- JavaScript siempre requiere paréntesis sumar(2, 3)
- Python también requiere paréntesis sumar(2, 3), pero si no los pones, obtienes la referencia a la función

📎Formas de definir funciones:
- JavaScript tiene 3 formas principales: 'function', 'expression', 'arrow'
- Python básicamente usa 'def' o 'lambda' para funciones cortas

2. 🤔 ¿Existe `math.sqrt()` en JavaScript?
- Mayúscula: En JavaScript es Math (con M mayúscula), en Python es math (minúscula)
- No requiere import: En JavaScript, Math está disponible globalmente, no necesitas importar nada
   
3. 🤯 ¿Cómo se controla un menú en consola si no hay `input()`?
- En JavaScript no hay un equivalente directo a input() de Python porque JavaScript fue diseñado originalmente para navegadores web, no para la consola. Entonces, la diferencia principal es que JavaScript maneja la entrada de forma asíncrona (con callbacks o promesas), mientras que Python's input() es síncrono y bloquea la ejecución hasta recibir la entrada.
  
4. 👀¿Cómo se maneja un “switch” (equivalente a `match-case`)?
- El switch es una estructura de control que permite evaluar una expresión y ejecutar diferentes bloques de código según el valor que coincida. Es especialmente útil cuando necesitas comparar una variable contra múltiples valores posibles.
- El switch evalúa una expresión una sola vez y luego compara su resultado con diferentes casos (cases). Cuando encuentra una coincidencia, ejecuta el código asociado a ese caso. Si ningún caso coincide, puede ejecutar un bloque por defecto (default).

5. 🥴 ¿Cómo evitamos errores como “división por cero”?
- A diferencia de muchos lenguajes de programación, JavaScript no lanza un error cuando divides por cero. En su lugar, devuelve valores especiales que pueden causar   problemas silenciosos en tu código:
   - 🎮 Dividir un número positivo por cero devuelve Infinity
   - 🪄 Dividir un número negativo por cero devuelve -Infinity
   - 👽 Dividir cero por cero devuelve NaN (Not a Number)
- Recomendaciones: Validación antes de la operación - Valores por defecto - Lanzar excepciones - Mensajes al usuario - Validación de entrada
