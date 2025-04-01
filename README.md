# funciones-y-parametros

# funciones y Parámetros en Python: ¿Para qué y por qué se utilizan?
Las funciones en Python son bloques de código reutilizables que ejecutan una tarea específica. Se usan para organizar, modularizar y optimizar el código.

" nos sirve para   organizar el codigo sierve como deficion de un pproceso de entrada y salida en la progamación
 sirve como serparador"
 al declarar la funcion yo estableso un (Scope) el scope permite proteger el contendio real de las varabiables intermnamente sin que afecten las variables externas. 

 las funciones pueden requerir  uno o muchos parametros  y eso debe afectar el scop interno de la funcion.
 

# ¿Por qué se utilizan las funciones?
 Reutilización del código: Evitan la repetición de código, haciendo los programas más eficientes.
 Modularidad: Permiten dividir un programa en partes más manejables.
 Facilitan el mantenimiento: Si hay un error, solo se corrige en la función y no en múltiples lugares.
 Claridad y organización: El código se vuelve más fácil de leer y entender.

 # ¿Para qué sirven los parámetros?
Los parámetros permiten que las funciones reciban datos externos y los utilicen dentro de su ejecución.

Ejemplo básico de una función con parámetros:

 def saludar(nombre):
    print(f"Hola, {nombre}!")

saludar("Carlos")  # Salida: Hola, Carlos!
# Tipos de parámetros en Python
1Posicionales: Se pasan en el orden en que la función los espera.


def sumar(a, b):
    return a + b

print(sumar(3, 5))  # Salida: 8

2 Por defecto (default): Tienen un valor predefinido.


def saludar(nombre="Invitado"):
    print(f"Hola, {nombre}!")

saludar()  # Salida: Hola, Invitado!



Conclusión
Las funciones y parámetros en Python son fundamentales para escribir código reutilizable, modular y eficiente.

# Ejemplo 
 -  Función para calcular valor absoluto

----def calcular_valor_absoluto(numero):
    ---valor_absoluto = abs(numero)
    ----print(f"El valor absoluto de {numero} es: {valor_absoluto}")


 # Nota explicacion ejemplo
1. Definición de la función

 def: Palabra clave para definir una función en Python.

calcular_valor_absoluto: Nombre de la función.

numero: float: Parámetro con type hint, lo que indica que numero debe ser de tipo float (aunque Python no lo obliga).

-> float: Indica que la función devolverá un float.

2Cálculo del valor absoluto


abs(numero): Usa la función incorporada abs() de Python para obtener el valor absoluto del número.

return: Devuelve el resultado, en lugar de imprimirlo directamente. Esto permite reutilizarlo en otros cálculos.


