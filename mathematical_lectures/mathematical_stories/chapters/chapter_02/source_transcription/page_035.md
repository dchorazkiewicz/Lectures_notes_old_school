# Strona 35

*§ 7. Działania na punktach w przestrzeni $C_n$*

## Ćwiczenia

1. Określając $k$-tą potęgę punktu $x\in C_n$ dla $k$ całkowitych nieujemnych w sposób indukcyjny: $x^0=1$ oraz $x^{k+1}=x^k\cdot x$, okazać, że dla wszelkich całkowitych nieujemnych $k$ i $l$ mamy

$$
x^k\cdot x^l=x^{k+l}.
$$

2. Jeśli $x=(x_1,x_2,\ldots,x_n)$, $y=(y_1,y_2,\ldots,y_n)$ i $z=(z_1,z_2,\ldots,z_n)$, to zależność

$$
(x\cdot y)z=x(y\cdot z)
$$

ma miejsce wtedy i tylko wtedy, gdy układy $(x_1,x_2,\ldots,x_n)$ i $(z_1,z_2,\ldots,z_n)$ są proporcjonalne lub gdy $x\cdot y=y\cdot z=0$.

3. Dowieść dla $x,y\in C_n$, że $(x+y)^2=x^2+2x\cdot y+y^2$, natomiast dla $n>1$ wyrażenia $(x+y)^3$ i $x^3+3x^2y+3xy^2+y^3$ są na ogół różne.

## § 8. Działania na punktach a odległość. Środek pary punktów

Korzystając z wprowadzonego znakowania, możemy wzór Pitagorasa na odległość dwóch punktów przestrzeni $C_n$ napisać w postaci

**(8.1)**

$$
\varrho(x,y)=\sqrt{(x-y)^2}
\qquad\text{dla każdej pary punktów }x,y\in C_n.
$$

Możemy poza tym nierówności Schwarza-Cauchy’ego nadać następującą krótką formę:

**(8.2)**

$$
(x\cdot y)^2\leq x^2y^2
\qquad\text{dla każdej pary punktów }x,y\in C_n.
$$

Zależności (6.4) możemy zaś nadać formę:

**(8.3)**

$$
(x\cdot y)^2=x^2y^2
$$

wtedy i tylko wtedy, gdy istnieją liczby $\lambda$ i $\mu$ nie znikające jednocześnie i takie, że

$$
\lambda x=\mu y.
$$

Odległość $\varrho(0,x)$ oznaczać będziemy również przez $|x|$. Mamy

$$
|x|=\sqrt{\sum_{i=1}^{n}x_i^2},
$$

co wobec (8.1) daje

**(8.4)**

$$
\varrho(x,y)=|x-y|.
$$

Wynika stąd, że

$$
|x+y|=|x-(-y)|=\varrho(x,-y)\leq \varrho(x,0)+\varrho(0,-y)
$$

$$
=\varrho(0,x)+\varrho(0,y)=|x|+|y|,
$$

czyli

**(8.5)**

$$
|x+y|\leq |x|+|y|.
$$

Stąd

$$
|x|=|y+(x-y)|\leq |y|+|x-y|,
$$

a więc

**(8.6)**

$$
|x-y|\geq |x|-|y|.
$$

Mamy wreszcie dla każdej liczby $t$ oraz $x\in C_n$:

$$
|tx|=|t|\cdot|x|.
$$
