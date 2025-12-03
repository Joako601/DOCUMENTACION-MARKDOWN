# Tecnológico de Software
## Materia: Fundamentos de Álgebra
## Alumno: Joaquin Uriona
## Actividad #22 – Documentación Final

---

# Ejercicios

# Ejercicio 1: Resolver con todos los métodos:
## Resuelve el siguiente sistema usando:

$$
\begin{cases}
x + y + z = 6 \\
2x - y + z = 3 \\
x + 2y - z = 2
\end{cases}
$$

+ Matriz aumentada:

$$
\begin{pmatrix}
1 & 1 & 1 & | & 6 \\
2 & -1 & 1 & | & 3 \\
1 & 2 & -1 & | & 2
\end{pmatrix}
$$

## Método de Gauss:

Matriz aumentada:

$$
\begin{pmatrix}
1 & 1 & 1 & | & 6 \\
2 & -1 & 1 & | & 3 \\
1 & 2 & -1 & | & 2
\end{pmatrix}
$$

**Operaciones:**

1. (F2 ---> F2 - 2.F1)  
2. (F3 ---> F3 - F1)  
3. (F3 ---> F3 + F2)

Resultado:

$$
\begin{pmatrix}
1 & 1 & 1 & | & 6 \\
0 & -3 & -1 & | & -9 \\
0 & 0 & 2 & | & 4
\end{pmatrix}
$$

Soluciones:  
+ (z = 2)  
+ (y = 3)  
+ (x = 1)

## Método Gauss–Jordan:

Partiendo de:

$$
\begin{pmatrix}
1 & 1 & 1 & | & 6 \\
0 & -3 & -1 & | & -9 \\
0 & 0 & 2 & | & 4
\end{pmatrix}
$$

**Operaciones:**

1. (F3 ---> 1/2.F_3)  
2. (F2 ---> F2 + F3)  
3. (F1 ---> F1 - F3)  
4. (F1 ---> F1 - F2)

Resultado reducido:

$$
\begin{pmatrix}
1 & 0 & 0 & | & 1 \\
0 & 1 & 0 & | & 3 \\
0 & 0 & 1 & | & 2
\end{pmatrix}
$$

## Matriz inversa:

Matriz de coeficientes:

$$
A =
\begin{pmatrix}
1 & 1 & 1 \\
2 & -1 & 1 \\
1 & 2 & -1
\end{pmatrix}
$$

Vector de resultados:

$$
B = 
\begin{pmatrix}
6 \\ 3 \\ 2
\end{pmatrix}
$$

Cálculo:

$$
X = A^{-1} B =
\begin{pmatrix}
1 \\ 3 \\ 2
\end{pmatrix}
$$

## Cramer:

Determinante:

$$
\det(A) = 6
$$

Resultados:

+ (x = 1)  
+ (y = 3)  
+ (z = 2)

## Solución del Ejercicio 1


$$
(x, y, z) = (1, 3, 2)
$$

---

# Ejercicio 2: Identificar tipo de solución
## Determina si cada sistema tiene solución única, infinitas o ninguna:

+ ## a) Sistema dependiente → infinitas soluciones.

+ ## b) Sistema incompatible → no tiene solución.

+ ## c) Sistema compatible determinado → solución única.

---

# Ejercicio 3 — Sistema 4×4
## Resuelve usando el método más eficiente:

$$
\begin{cases}
x + y + z + w = 10 \\
2x + y - z + w = 5 \\
x - y + z - w = 1 \\
x + y - z + 2w = 8
\end{cases}
$$

## Matriz aumentada:

$$
\begin{pmatrix}
1 & 1 & 1 & 1 & | & 10 \\
2 & 1 & -1 & 1 & | & 5 \\
1 & -1 & 1 & -1 & | & 1 \\
1 & 1 & -1 & 2 & | & 8
\end{pmatrix}
$$

+ Luego de aplicar Gauss:

$$
\begin{pmatrix}
1 & 1 & 0 & 0 & | & 3 \\
0 & 1 & 0 & 1 & | & 4 \\
0 & 0 & 1 & 1 & | & 3 \\
0 & 0 & 0 & 1 & | & 1
\end{pmatrix}
$$

Soluciones:

+ (w = 1)  
+ (z = 2)  
+ (y = 3)  
+ (x = 0)

---

# Ejercicio 4 — Aplicación práctica

+ Productos: Premium (P), Standard (S), Utilitario (U)  
+ Materias primas: res (R), pollo (Q), cerdo (C)

$`\begin{pmatrix}
2 & 1 & 3 & | & P \\
3 & 1 & 2 & | & S \\
1 & 2 & 1 & | & U
\end{pmatrix}`$

Aplicando Gauss:

$`\begin{pmatrix}
1 & 0 & 1 & | & 20 \\
0 & 1 & 1 & | & 40 \\
0 & 0 & 1 & | & 20
\end{pmatrix}`$

Soluciones:

+ (U = 20)
+ (S = 20)  
+ (P = 0)


