# Strona 53

*§ 15. Iloczyn skalarny wektorów — Kąt między wektorami*

Ujemne. Jasne jest, że tak określona liczba $|\Delta(a,b,c)|$ jest niezmiennikiem geometrycznym trójki punktów $a,b,c\in C_n$, niezależnym od porządku tych punktów. Oznaczając przez $\mathfrak a$ i $\mathfrak b$ wektory swobodne o reprezentantach $\overrightarrow{ab}$ i $\overrightarrow{ac}$, mamy:

$$
|\Delta(a,b,c)|
=
\frac14\sqrt{
(|\mathfrak a|+|\mathfrak b|+|\mathfrak a-\mathfrak b|)
(|\mathfrak a|+|\mathfrak b|-|\mathfrak a-\mathfrak b|)
}
$$

$$
\cdot
\sqrt{
(|\mathfrak a|-|\mathfrak b|+|\mathfrak a-\mathfrak b|)
(-|\mathfrak a|+|\mathfrak b|+|\mathfrak a-\mathfrak b|)
}
$$

$$
=
\frac12\sqrt{(|\mathfrak a|\,|\mathfrak b|-\mathfrak a\cdot\mathfrak b)
(|\mathfrak a|\,|\mathfrak b|+\mathfrak a\cdot\mathfrak b)}
$$

$$
=
\frac12\sqrt{\mathfrak a^2\mathfrak b^2-(\mathfrak a\cdot\mathfrak b)^2}.
$$

Jeżeli $\theta$ oznacza kąt między wektorami $\mathfrak a$ i $\mathfrak b$, to z (15.2) wynika

$$
|\Delta(a,b,c)|
=
\frac12|\mathfrak a|\cdot|\mathfrak b|\sin\theta.
$$

Liczba $|\mathfrak a|\cdot|\mathfrak b|\sin\theta$ nazywa się *polem równoległoboku rozpiętego na wektorach $\mathfrak a$ i $\mathfrak b$*. Intuicyjny sens tej liczby jest jasny.

## Ćwiczenia

1. Niech $a_1,a_2,\ldots,a_k$ będą wektorami przestrzeni $C_n$, a $\alpha_1,\alpha_2,\ldots,\alpha_k$ liczbami. Okazać, że jeśli wektor

$$
a=\alpha_1a_1+\alpha_2a_2+\cdots+\alpha_ka_k
$$

jest prostopadły do każdego z wektorów $a_1,a_2,\ldots,a_k$, to $a=0$.

2. Znaleźć w przestrzeni $C_3$ trzy wersory, z których każdy jest prostopadły do obu pozostałych, wiedząc, że jednym z nich jest wektor

$$
\left[\frac13,\frac23,\frac23\right]
$$

oraz że pierwsza współrzędna drugiego jest zerem.

3. Zakładając, że spośród $n$ wektorów $a_1,a_2,\ldots,a_n$ każdy jest prostopadły do wszystkich pozostałych, okazać, że wyznacznik[^1]

$$
|a_{ij}|
\qquad (i,j=1,2,\ldots,n)
$$

ma wartość bezwzględną równą iloczynowi

$$
|a_1|\cdot|a_2|\cdots|a_n|.
$$

4. Niech $a,b,c$ będą różnymi punktami przestrzeni $C_n$. Okazać, że

$$
\measuredangle([\overrightarrow{ab}],[\overrightarrow{ac}])
+
\measuredangle([\overrightarrow{ba}],[\overrightarrow{bc}])
+
\measuredangle([\overrightarrow{ca}],[\overrightarrow{cb}])
=
\pi.
$$

[^1]: Przez $|a_{ij}|$ $(i,j=1,2,\ldots,n)$ oznaczać będziemy wyznacznik

    $$
    \begin{vmatrix}
    a_{11} & a_{12} & \cdots & a_{1n}\\
    a_{21} & a_{22} & \cdots & a_{2n}\\
    \vdots & \vdots & & \vdots\\
    a_{n1} & a_{n2} & \cdots & a_{nn}
    \end{vmatrix}.
    $$
