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
# Ejercicio 1: Determinantes 2×2
## Calcula los determinantes:

### 1. Primera matriz

$$ A =
\begin{pmatrix}
5 & 2 \\
3 & 1 \\
\end{pmatrix}
$$

1. calculamos los determinantes en diagonal
2. multiplicamos 3 x 2 x (-1) = -6
3. multiplicamos 5 x 1 x (1) = 5
4. hacemos la resta correspondiente 5 - 6 = -1
5. A = det(A)= -1

### 2. Segunda matriz

$$ B =
\begin{pmatrix}
-1 & 4 \\
2 & -8 \\
\end{pmatrix}
$$

1. calculamos los determinantes en diagonal
2. multiplicamos 2 x 4 x (-1) = -8
3. multiplicamos (-1) x (-8) x (1) = 8
4. hacemos la resta correspondiente 8 - 8 = 0
5. B = det(A)= 0

### 3. Tercera matriz

$$ C =
\begin{pmatrix}
6 & 9 \\
2 & 3 \\
\end{pmatrix}
$$

1. calculamos los determinantes en diagonal
2. multiplicamos 2 x 9 x (-1) = -18
3. multiplicamos 6 x 3 x (1) = 18
4. hacemos la resta correspondiente 18 - 18 = 0
5. C = det(A)= 0

### 4. Cuarta Matriz

$$ D =
\begin{pmatrix}
0 & 5 \\
-5 & 0 \\
\end{pmatrix}
$$

1. calculamos los determinantes en diagonal
2. multiplicamos (-5) x 5 x (-1) = 25
3. multiplicamos 0 x 0 x (1) = 0
4. hacemos la resta correspondiente 25 - 0 = 25
5. D = det(A)= 25

------------------------------------
# Ejercicio 2: Regla de Sarrus
## Usa Sarrus para calcular:

### 1. Primera matriz

$$ E =
\begin{pmatrix}
1 & 2 & 3\\
0 & 1 & 4\\
5 & 6 & 0\\
\end{pmatrix}
$$

1. colocamos una linea debajo de la matriz
2. copiamos en orden las filas 1 y 2

$$ E =
\begin{pmatrix}
1 & 2 & 3\\
0 & 1 & 4\\
5 & 6 & 0\\
\\
1 & 2 & 3\\
0 & 1 & 4\\
\end{pmatrix}
$$

3. Calculamos primero las diagonales negativas:
+ multiplicamos 0 x 2 x 0 x (-1) = 0
+ multiplicamos 1 x 6 x 4 x (-1) = -24
+ multiplicamos 5 x 1 x 3 x (-1) = -15
+ TOTAL = -39

4. Calculamos primero las diagonales positivas:
+ multiplicamos 1 x 1 x 0 x 1 = 0
+ multiplicamos 0 x 6 x 3 x 1 = 0
+ multiplicamos 5 x 2 x 4 x 1 = 40
+ TOTAL = 40

5. hacemos la resta correspondiente 40 - 39 = 1
6. E = det(A)= 1

### 2. Segunda matriz

$$ F =
\begin{pmatrix}
2 & -1 & 3\\
1 & 4 & 0\\
3 & 2 & -2\\
\end{pmatrix}
$$

1. colocamos una linea debajo de la matriz
2. copiamos en orden las filas 1 y 2

$$ F =
\begin{pmatrix}
2 & -1 & 3\\
1 & 4 & 0\\
3 & 2 & -2\\
\\
2 & -1 & 3\\
1 & 4 & 0\\
\end{pmatrix}
$$

3. Calculamos primero las diagonales negativas:
+ multiplicamos 1 x -1 x -2 x (-1) = -2
+ multiplicamos 2 x 2 x 0 x (-1) = 0
+ multiplicamos 3 x 4 x 3 x (-1) = -36
+ TOTAL = -38

4. Calculamos primero las diagonales positivas:
+ multiplicamos 2 x 4 x (-2) x 1 = -16
+ multiplicamos 1 x 2 x 3 x 1 = 6
+ multiplicamos 3 x (-1) x 0 x 1 = 0
+ TOTAL = -10

5. hacemos la resta correspondiente -38 - 10 = -48
6. F = det(A)= -48

# Ejercicio 3: Método de cofactores
## Calcula usando cofactores (expandir por la fila o columna más conveniente):

### 1. Primera matriz

$$ G =
\begin{pmatrix}
1 & 0 & 2\\
-1 & 3 & 1\\
2 & 0 & 1\\
\end{pmatrix}
$$

1. La primera columna se le agrega un signo (+)
2. Se alternan los signos para el resto de las columnas.

$$ G =
\begin{pmatrix}
1 & 0 & 2\\
-1 & 3 & 1\\
2 & 0 & 1\\
\end{pmatrix}
$$

3. Agarramos el primer numero de la fila 1 y columna 1 y agarramos los numeros de las filas 2 y 3 con las columnas 2 y 3.
```
1 | 3 1 |
  | 0 1 |
```
4. hacemos las multiplicaciones cruzadas dentro de los || y luego multiplicamos por el numero de afuera.
```
1 | 3 1 | = 1 x 3 = 3
  | 0 1 |
```
5. Agarramos el primer numero de la fila 1 y columna 2 y agarramos los numeros de las filas 2 y 3 con las columnas 1 y 3.
```
0 | -1 1 |
  | 2 1  |
```
6. hacemos las multiplicaciones cruzadas dentro de los || y luego multiplicamos por el numero de afuera.
```
0 | -1 1 | = 0 (-2 x 1) = 0
  | 2 1  |
```
7. Agarramos el primer numero de la fila 1 y columna 3 y agarramos los numeros de las filas 2 y 3 con las columnas 1 y 2.
```
2 | -1 3 |
  | 2 0  |
```
8. hacemos las multiplicaciones cruzadas dentro de los || y luego multiplicamos por el numero de afuera.
```
2 | -1 3 | = 2 x (-6) = -12
  | 2 0  |
```
8. hacemos las sumas de los tres bloques para que nos el determinanste
+ 3 + 0 - 12 = -9

9. Resultado:
+ G = det(A) = -9


# Ejercicio 4: Verificar propiedades
## Dadas y , verifica que:
+ det(AB) = det(A) x det(B)
+ det(A^T) = det(A)

$$ A =
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
1 & 2 \\
3 & 1 \\
\end{pmatrix}
$$

### 1. Primera verificacion de det(AB) = det(A) x det(B)

1. det(A) x det(B)
2. det(A):
+ calculamos los determinantes en diagonal
+ multiplicamos 1 x 1 x (-1) = -1
+ multiplicamos 2 x 3 x (1) = 6
+ hacemos la resta correspondiente 6 - 1 = 5
+ A = det(A)= 5


3. det(B):
+ calculamos los determinantes en diagonal
+ multiplicamos 3 x 2 x (-1) = -6
+ multiplicamos 1 x 1 x (1) = 1
+ hacemos la resta correspondiente 1 - 6 = -5
+ B = det(A)= -5

4. multiplicamos los determinantes de A y B
+ 5 x (-5) = -25

5. det(AB):
+ multiplicamos las columnas con sus respectivas filas

$$ AB =
\begin{bmatrix}
2 * 1 & 2 * 2 \\
1 * 3 & 1 * 1 \\
            \\  
1 * 1 & 1 * 2 \\
3 * 3 & 3 * 1 \\
\end{bmatrix}
$$

+ Resultado:

$$ AB =
\begin{pmatrix}
5 & 5 \\
10 & 5 \\
\end{pmatrix}
$$

+ calculamos los determinantes en diagonal
+ multiplicamos 10 x 5 x (-1) = -50
+ multiplicamos 5 x 5 x (1) = 25
+ hacemos la resta correspondiente 25 - 50 = -25
+ AB = det(A)= -25

6. corroboramos que det(AB) = det(A) x det(B)

### 2. Segunda verificacion de det(A^T) = det(A)

1. cambiamos el orden de las filas x columnas

$$ A^T =
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix}
$$

2. calculamos los determinantes en diagonal
+ multiplicamos 1 x 1 x (-1) = -1
+ multiplicamos 2 x 3 x (1) = 6
+ hacemos la resta correspondiente 6 - 1 = 5
+ A^T = det(A)= 5

3. corroboramos que det(A^T) = det(A)

# Ejercicio 5: Aplicación geométric
## Dados los vectores u = (3,2) y v = (1,4):
a) Calcula el área del paralelogramo que forman

b) ¿Cambia el área si intercambias los vectores?

c) ¿Qué representa el signo del determinante?

1. para hacer los incisos necesitamos convertir los vectores en una matriz:

$$ A =
\begin{pmatrix}
3 & 2 \\
1 & 4 \\
\end{pmatrix}
$$


### inciso A

1. calculamos los determinantes en diagonal
+ multiplicamos 1 x 2 x (-1) = -2
+ multiplicamos 3 x 4 x (1) = 12
+ hacemos la resta correspondiente 12 - 2 = 10
+ A = det(A)= 10

2. el area es el determinante de la matriz
+ RESULTADO: area = 10

### inciso B

1. intercambiamos los vectores

$$ A =
\begin{pmatrix}
1 & 4 \\
3 & 2 \\
\end{pmatrix}
$$

2. calculamos los determinantes en diagonal
+ multiplicamos 3 x 4 x (-1) = -12
+ multiplicamos 1 x 2 x (1) = 2
+ hacemos la resta correspondiente 2 - 12 = -10
+ A = det(A)= -10

3. RESULTADO:
+ cambia el area si intercambiamos los vectores

### inciso C

+ Es el orden en el cual ingresaron los vectores






