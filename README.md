# Introducción a NumPy: De Listas a Arreglos en Python

Este repositorio es una pequeña práctica para entender cómo pasar de las listas básicas de Python a trabajar con vectores y matrices en NumPy.

# ¿De qué trata este proyecto?

Si intentas sumar dos listas en Python usando el signo +, la máquina no hace la suma matemática, sino que pega una lista al lado de la otra. 

La idea de este código es mostrar justo ese problema y arreglarlo usando la librería NumPy. Veremos cómo los arreglos (np.array) convierten las listas en objetos matemáticos de verdad para hacer operaciones directas sin dar tantas vueltas.

# ¿Qué hace el código paso a paso?

1. Tipos de datos básicos: Un repaso rápido de cómo maneja Python los enteros (int), decimales (float) y texto (str).
2. El problema con las listas: Muestra por qué el símbolo + solo junta las listas y por qué no se pueden multiplicar directo por decimales.
3. Indexación: Cómo acceder a los elementos por su posición, recordando que siempre empezamos a contar desde el 0.
4. Sumar a mano con bucles: La forma tradicional (y más tardada) de sumar listas elemento por elemento usando ciclos for.
5. La solución con NumPy: Pasar las listas a arreglos (np.array) para hacer sumas y multiplicaciones de un solo golpe.
6. Cambiar la forma (reshape): Agarra un vector de 20 números y lo acomoda en matrices de varias dimensiones (como 5 filas por 4 columnas).

# Puntos clave

- Listas vs Arreglos: Las listas guardan de todo un poco, mientras que los arreglos de NumPy están pensados para hacer cuentas matemáticas.
- Vectorización: Aplicar operaciones a todo un bloque de datos al mismo tiempo ahorra código y hace que todo corra más rápido.
- Redimensionar datos: Se puede cambiar la forma de un arreglo con .reshape() siempre y cuando la cantidad total de números sea la misma.

# ¿Cómo correrlo?

1. Sube el archivo .ipynb a Google Colab.
2. Corre las celdas en orden. No hace falta instalar nada porque Colab ya trae NumPy listo para usar.
