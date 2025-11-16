# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Joaquin Uriona
## Actividad \#18 - Matrices doc

---
### Identificación de matrices

Matriz identidad, porque la diagonal está compuestos por solo unos y los elementos fuera de la diagonal son ceros.

$$ A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

MUESTRA

Calcula la suma de A y B

$$ A =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
9 & 10 & 11 \\
12 & 13 & 14 \\
\end{pmatrix}
$$

$$ A + B =
\begin{pmatrix}
1 + 9 & 2 + 10 & 3 + 11 \\
4 + 12 & 5 + 13 & 6 + 14 \\
\end{pmatrix}
$$

$$ A + B =
\begin{pmatrix}
10 & 12 & 14 \\
16 & 18 & 20 \\
\end{pmatrix}
$$

---
# OTRO EJERCICIO
...

------------------------------------
### Ejercicio 1:
Identificacion de matrices.

1. Primera matriz

$$ A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
= Matriz \\ de \\ Identidad
$$

2. Segunda matriz

$$ B =
\begin{pmatrix}
3 & 0 & 0 \\
0 & -2 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}
= Matriz \\ Diagonal
$$

3. Tercera matriz

$$ C =
\begin{pmatrix}
2 & 1 & 4 \\
1 & 3 & 5 \\
4 & 5 & 6 \\
\end{pmatrix}
= Matriz \\ simetrica
$$

4. Cuarta Matriz

$$ D =
\begin{pmatrix}
1 & 2 & 3 \\
0 & 4 & 5 \\
0 & 0 & 6 \\
\end{pmatrix}
= Matriz \\ triangular \\ superior
$$

------------------------------------
### Ejercicio 2:
Resolucion de problemas algebraicos con matrices.

a) Suma de A + B

$$ A =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
5 & 2 \\
-1 & 3 \\
\end{pmatrix}
$$


$$ A + B =
\begin{pmatrix}
2 + 5 & -1 + 2 \\
3 + (-1) & 4 + 3 \\
\end{pmatrix}
$$

Resultado:

$$ A + B =
\begin{pmatrix}
7 & 1 \\
2 & 7 \\
\end{pmatrix}
$$

b) Resta de 2A - B

$$ A =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
5 & 2 \\
-1 & 3 \\
\end{pmatrix}
$$

Se multiplica la matriz A por 2

$$ 2A =
\begin{pmatrix}
2 * 2 & 2 * -1 \\
2 * 3 & 2 * 4 \\
\end{pmatrix}
$$ 

$$ 2A =
\begin{pmatrix}
4 & -2 \\
6 & 8 \\
\end{pmatrix}
$$ 

Se restar 2A - B

$$ 2A - B =
\begin{pmatrix}
4 - 5 & -2 - 2 \\
6 - (-1) & 8 - 3 \\
\end{pmatrix}
$$

Resultado:

$$ 2A - B =
\begin{pmatrix}
-1 & -4 \\
7 & 5 \\
\end{pmatrix}
$$

c) AB

$$ A =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
5 & 2 \\
-1 & 3 \\
\end{pmatrix}
$$

$$ AB =
\begin{bmatrix}
2 * 5 & 2 * 2 \\
-1 * -1 & -1 * 3 \\
            \\  
3 * 5 & 3 * 2 \\
4 * -1 & 4 * 3 \\
\end{bmatrix}
$$

Resultado:

$$ AB =
\begin{pmatrix}
11 & 1 \\
11 & 18 \\
\end{pmatrix}
$$

d) BA

$$ B =
\begin{pmatrix}
5 & 2 \\
-1 & 3 \\
\end{pmatrix}
$$

$$ A =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
$$



$$ BA =
\begin{bmatrix}
5 * 2 & 5 * -1 \\
2 * 3 & 2 * 4 \\
                  \\
-1 * 2 & -1 * -1 \\
3 * 3 & 3 * 4 \\
\end{bmatrix}
$$

Resultado:

$$ BA =
\begin{pmatrix}
16 & 3 \\
7 & 13 \\
\end{pmatrix}
$$

e) A^T

$$ A =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
$$

Resultado:

$$ A^T =
\begin{pmatrix}
2 & 3 \\
-1 & 4 \\
\end{pmatrix}
$$


------------------------------------
### Ejercicio 3:
Verificacion de matrices por asociacion

Matrices base:

$$ A = 
\begin{pmatrix}
1 & 2 \\
3 & 4 \\
\end{pmatrix}
$$

$$ B = 
\begin{pmatrix}
2 & 0 \\
1 & 3 \\
\end{pmatrix}
$$

$$ C = 
\begin{pmatrix}
1 & 1 \\
0 & 2 \\
\end{pmatrix}
$$

Verificar que (AB)C = A(BC)

1. verificacion de (AB)C

Primero multiplicamos A * B

$$ AB =
\begin{pmatrix}
1(2) + 2(1) & 1(0) + 2(3) \\
3(2) + 4(1) & 3(0) + 3(4) \\
\end{pmatrix} 
$$

$$
\begin{pmatrix}
2 + 2 & 0 + 6 \\
6 + 4 & 0 + 12 \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
4 & 6 \\
10 & 12 \\
\end{pmatrix}
$$

Segundo multiplicamos (AB) * C

$$ (AB)C =
\begin{pmatrix}
4(1) + 6(0) & 4(1) + 6(2) \\
10(1) + 12(0) & 10(1) + 12(2) \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
4 + 0 & 4 + 12 \\
10 + 0 & 10 + 24 \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$

2. verificacion de A(BC)

Primero multiplicamos B * C

$$ BC =
\begin{pmatrix}
2(1) + 0(0) & 2(1) + 0(2) \\
1(1) + 3(0) & 1(1) + 3(2) \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
2 + 0 & 2 + 0 \\
1 + 0 & 1 + 6 \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
2 & 2 \\
1 & 7 \\
\end{pmatrix}
$$

Segundo multiplicamos A * (BC)

$$ A(BC) =
\begin{pmatrix}
1(2) + 2(1) & 1(2) + 2(7) \\
3(2) + 4(1) & 3(2) + 4(7) \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
2 + 2 & 2 + 14 \\
6 + 4 & 6 + 28 \\
\end{pmatrix}
$$

$$
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$

Son iguales por la propiedad asociativa

---







