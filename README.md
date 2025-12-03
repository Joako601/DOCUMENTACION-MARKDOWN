# Tecnológico de Software
## Materia: Fundamentos de Álgebra
## Alumno: Joaquin Uriona
## Actividad #22 – Documentación Final

---

## Ejercicios

### 1. Resuelve el siguiente sistema usando todos los métodos:

Sistema:

$$
\begin{cases}
x + y + z = 6 \\
2x - y + z = 3 \\
x + 2y - z = 2
\end{cases}
$$

Matriz aumentada:

$$
\begin{pmatrix}
1 & 1 & 1 & | & 6 \\
2 & -1 & 1 & | & 3 \\
1 & 2 & -1 & | & 2
\end{pmatrix}
$$

---

# Ejercicio 1 — Resolver el sistema por todos los métodos

## Método de Gauss

Matriz aumentada:

$$
\begin{bmatrix}
1 & 1 & 1 & | & 6 \\
2 & -1 & 1 & | & 3 \\
1 & 2 & -1 & | & 2
\end{bmatrix}
$$

**Operaciones:**

1. \(F_2 \leftarrow F_2 - 2F_1\)  
2. \(F_3 \leftarrow F_3 - F_1\)  
3. \(F_3 \leftarrow F_3 + F_2\)

**Resultado:**

$$
\begin{bmatrix}
1 & 1 & 1 & | & 6 \\
0 & -3 & -1 & | & -9 \\
0 & 0 & 2 & | & 4
\end{bmatrix}
$$

Soluciones:  
- \(z = 2\)  
- \(y = 3\)  
- \(x = 1\)

---

## Método Gauss–Jordan

Partiendo de:

$$
\begin{bmatrix}
1 & 1 & 1 & | & 6 \\
0 & -3 & -1 & | & -9 \\
0 & 0 & 2 & | & 4
\end{bmatrix}
$$

**Operaciones:**

1. \(F_3 \leftarrow \tfrac{1}{2}F_3\)  
2. \(F_2 \leftarrow F_2 + F_3\)  
3. \(F_1 \leftarrow F_1 - F_3\)  
4. \(F_1 \leftarrow F_1 - F_2\)

**Resultado reducido:**

$$
\begin{bmatrix}
1 & 0 & 0 & | & 1 \\
0 & 1 & 0 & | & 3 \\
0 & 0 & 1 & | & 2
\end{bmatrix}
$$

---

## Matriz inversa

Matriz de coeficientes:

$$
A =
\begin{bmatrix}
1 & 1 & 1 \\
2 & -1 & 1 \\
1 & 2 & -1
\end{bmatrix}
$$

Vector de resultados:

$$
B = 
\begin{bmatrix}
6 \\ 3 \\ 2
\end{bmatrix}
$$

Cálculo:

$$
X = A^{-1} B =
\begin{bmatrix}
1 \\ 3 \\ 2
\end{bmatrix}
$$

---

## Regla de Cramer

Determinante:

$$
\det(A) = 6
$$

Resultados:

- \(x = 1\)  
- \(y = 3\)  
- \(z = 2\)

---

# Solución del Ejercicio 1

$$
(x, y, z) = (1, 3, 2)
$$

---

# Ejercicio 2 — Tipo de solución

### a)  
Sistema dependiente → infinitas soluciones.

### b)  
Sistema incompatible → no tiene solución.

### c)  
Sistema compatible determinado → solución única.

---

# Ejercicio 3 — Sistema 4×4

Resolver:

$$
\begin{cases}
x + y + z + w = 10 \\
2x + y - z + w = 5 \\
x - y + z - w = 1 \\
x + y - z + 2w = 8
\end{cases}
$$

Matriz aumentada:

$$
\begin{bmatrix}
1 & 1 & 1 & 1 & | & 10 \\
2 & 1 & -1 & 1 & | & 5 \\
1 & -1 & 1 & -1 & | & 1 \\
1 & 1 & -1 & 2 & | & 8
\end{bmatrix}
$$

Luego de aplicar Gauss:

$$
\begin{bmatrix}
1 & 1 & 0 & 0 & | & 3 \\
0 & 1 & 0 & 1 & | & 4 \\
0 & 0 & 1 & 1 & | & 3 \\
0 & 0 & 0 & 1 & | & 1
\end{bmatrix}
$$

**Soluciones:**

- \(w = 1\)  
- \(z = 2\)  
- \(y = 3\)  
- \(x = 0\)

---

# Ejercicio 4 — Aplicación práctica

Productos: Premium (P), Standard (S), Utilitario (U)  
Materias primas: res (R), pollo (Q), cerdo (C)

Sistema:

$$
\begin{bmatrix}
2 & 1 & 3 \\
3 & 1 & 2 \\
1 & 2 & 1
\end{bmatrix}
\begin{bmatrix}
P \\ S \\ U
\end{bmatrix}
=
\begin{bmatrix}
100 \\ 120 \\ 80
\end{bmatrix}
$$

Aplicando Gauss:
$$


**Soluciones:**

- \(U = 20\)  
- \(S = 20\)  
- \(P = 0\)

---
