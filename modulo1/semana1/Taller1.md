
# Taller de Consolidación – Ruta Básica de Python

## Objetivo General
Fortalecer las bases de programación en Python aplicando variables, tipos de datos, entrada/salida, condicionales, bucles, listas y operaciones básicas sobre colecciones.  
El taller se realizará por células y cada estudiante trabajará en su propia rama de GitHub, desarrollando los ejercicios asignados.

---

## Indicaciones Generales

1. Cada célula debe tener un repositorio en GitHub (ya creado).  
2. Cada estudiante trabaja en su propia rama (`nombre_estudiante`) y hace commits por cada ejercicio resuelto.  
3. Al finalizar el taller, debe hacer un pull request hacia la rama principal (`main` o `master`).
4. Todos los ejercicios deben estar en un solo archivo llamado `taller_basico.py`, con comentarios y numerados.
5. Se deben incluir comentarios explicativos en cada parte del código.
6. Fecha de entrega: mañana al final del día.

---

## Contenido del Taller

### Nivel 1 — Fundamentos y Variables
Objetivo: Practicar tipos de datos, entrada y salida, concatenación y operaciones básicas.

1. Hola usuario: pide al usuario su nombre y edad. Luego imprime un mensaje: "Hola [nombre], tienes [edad] años."
2. Suma de dos números.
3. Área del triángulo.
4. Conversor de grados Celsius a Fahrenheit.
5. Tipo de dato: usar type() para mostrar el tipo de cada variable.
6. Edad futura: pide la edad actual y muestra cuántos años tendrá el usuario dentro de 10 años.

---

### Nivel 2 — Condicionales (Decisiones)
Objetivo: Comprender y aplicar estructuras if, elif, else.

7. Mayor de edad.
8. Número positivo, negativo o cero.
9. Par o impar.
10. Calculadora básica con +, -, *, /.
11. Clasificador de notas (Excelente, Aprobado, Reprobado).
12. Comparador de tres números: mayor y menor.

---

### Nivel 3 — Bucles y Repetición
Objetivo: Dominar for y while, control de iteraciones y sumatorias.

13. Contar del 1 al 10.
14. Sumatoria del 1 al n.
15. Tabla de multiplicar.
16. Contador regresivo con while.
17. Adivina el número (usar random).
18. Sumar hasta que el usuario escriba 0.

---

### Nivel 4 — Listas y Colecciones
Objetivo: Crear, recorrer, modificar y eliminar elementos en listas.

19. Lista de frutas.
20. Agregar y eliminar frutas.
21. Buscar un elemento en la lista.
22. Lista de números y promedio.
23. Números pares: guardar solo los pares.
24. Eliminar duplicados.

---

### Nivel 5 — Retos (Integración de todo)
Objetivo: Aplicar todos los conceptos vistos en problemas más completos.

25. Sistema de calificaciones.
26. Carrito de compras.
27. Cajero automático.
28. Gestión de estudiantes (mini base de datos).
29. Calculadora avanzada (usar funciones).
30. Agenda de contactos (lista de diccionarios).

---

## Entrega

Cada célula debe subir:
- Archivo `taller_basico.py`
- Archivo `README.md` explicando qué ejercicios hizo cada integrante.
- En su rama personal, cada estudiante debe tener:
  - Commits individuales (mínimo 3).
  - Comentarios explicando la lógica de los ejercicios.

---

## Tips para los estudiantes

- Usar input() para leer datos del usuario.  
- Usar int() o float() para convertir los datos cuando sea necesario.  
- Usar append() para agregar a listas, remove() o pop() para eliminar.  
- Probar con print() en cada paso.  
- Comentar el código con # Explicación de lo que hace este bloque.

---

## Nivel Extra (opcional)
Mini proyecto libre:  
Usando todo lo aprendido, crear un pequeño programa propio (ejemplo: calculadora de IMC, conversor de divisas, agenda de tareas, simulador de tienda).  

Debe incluir:
- Entrada de datos  
- Estructura condicional  
- Ciclo  
- Lista o diccionario

# Nivel 3 — Bucles y Repetición
# Objetivo: Dominar for y while, control de iteraciones y sumatorias.

# Contar del 1 al 10.
# Sumatoria del 1 al n. 
# Tabla de multiplicar.
# Contador regresivo con while.
# Adivina el número (usar random).
# Sumar hasta que el usuario escriba 0.


def count():  
    n = int(input("Enter the number you want to count to: "))
    for i in range(n):
        print(i + 1)



def summation():
    n = int(input("ingresa numero para detener la secuencias: "))
    sum = 0    
    for i  in range(n+1): 
        print(f"este es el numero a contar{i}")
        sum += i 
        print(sum)






nums=[1,2,3,4,5]

def show(list):
    first = list[0]
    last = list[4]

    return first, last

valor1,valor2 =show(nums)
    
print(valor1,valor2)




sapo = lambda s1,s2: s1 * s2
result = sapo(5,5)

print(f"Hay {result} sapos")








# def menu():
#     while True:
#         print("\n====== MENÚ PRINCIPAL ======")
#         print("1. Contar del 1 al 10")
#         print("2. Numero positivo, negativo o cero")
#         print("3. Par o Impar")
#         print("4. Calculadora basica")
#         print("5. Promedio")
#         print("6. Comparar 3 numeros")
#         print("7. Salir")

#         choice = input("Elige una opción (1-7): ")

#         if choice == "1":          
#            contar()
#         elif choice == "2":
#             number()
#         elif choice == "3":
#             par_impar()
#         elif choice == "4":
#             calculator()
#         elif choice == "5":
#             classifier()
#         elif choice == "6":
#             compare()
#         elif choice == "7":
#             print("¡Hasta luego!")
#             break
#         else:
#             print("Opción no válida. Intenta de nuevo.")
# menu()
