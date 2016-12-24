---
layout: post
title: "Matrices"
tag: matrices
---

### Definición

Una matriz es un conjunto de números ordenados en filas y columnas. Diremos que una matriz $$A$$ tiene dimensión $$ n \times m $$, cuando tiene $$n$$ filas y $$m$$ columnas. En este caso lo notaremos como $$ A \in M_{m \times n} $$

Cada número ocupará un lugar determinado por la fila y columna donde se encuentre, al número que ocupa la fila $$i$$ y la columna $$j$$ se notará como $$ a_{i,j} $$, por tanto:

$$
A =
 \begin{pmatrix}
  a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
  a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
  \vdots  & \vdots  & \ddots & \vdots  \\
  a_{m,1} & a_{m,2} & \cdots & a_{m,n}
 \end{pmatrix}
$$

Donde los $$ a_{i,j} $$ son números reales $$\mathbb{R}$$ o números complejos $$\mathbb{C}$$.

### Tipos de matrices

1. **Matriz columna**: $$ A \in M_{n \times 1} $$, es decir, es de la forma: $$
 \begin{pmatrix}
  a_{1,1} \\
  \vdots  \\
  a_{n,1}
 \end{pmatrix}
$$
2. **Matriz fila**: $$ A \in M_{1 \times n} $$, es decir, de la forma: $$
 \begin{pmatrix}
  a_{1,1} & \cdots  & a_{n,1}
 \end{pmatrix}
$$
3. **Matriz nula**: todos sus elementos son ceros, es decir $$ a_{i,j} = 0$$
4. **Matriz cuadrada**: tiene el mismo número de filas que de columnas, es decir $$ A \in M_{n \times n} $$, destacamos dentro de las matrices cuadradas:
    * **Matriz diagonal**: todos los elementos de fuera de la diagonal principal son ceros.
    * **Matriz identidad**: es una matriz diagonal, cuyos elementos de la diagonal principal son unos. Lo notamos por $$I$$.
    * **Matriz triangular**: es una matriz cuyos elementos por encima de la diagonal principal son todos ceros (Triangular inferior) ó por debajo de la diagonal principal son todos ceros (Triangular superior)

### Aplicaciones de matrices

* Álgebra lineal
* Tablas de doble entrada
* Grafos
* Probabilidad y estadística, para procesos estocásticos
* Cálculo numérico
