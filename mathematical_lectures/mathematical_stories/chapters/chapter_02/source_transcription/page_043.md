# Strona 43

*§ 12. Izometrie elementarne*

**(12.1) TWIERDZENIE.** *W przestrzeni $C_n$ dany jest układ $k+1$ punktów $p_0,p_1,\ldots,p_k$. Istnieje izometria elementarna $f$ przekształcająca $C_n$ na siebie taka, że*

$$
f(p_i)=(a_{i1},a_{i2},\ldots,a_{in}),
$$

*gdzie $a_{ij}=0$ dla $i<j$.*

**Dowód.** Jeśli $k=0$, układ składa się z jednego punktu $p_0$ i przesunięcie

$$
f(x)=x-p_0
$$

jest izometrią żądaną. Załóżmy więc, że $k\geq1$ i że dla układu punktów $p_0,p_1,\ldots,p_{k-1}$ twierdzenie jest prawdziwe, czyli istnieje izometria $\varphi$ przekształcająca $C_n$ na siebie i taka, że dla $i=0,1,\ldots,k-1$ jest

$$
\varphi(p_i)=(a_{i1},a_{i2},\ldots,a_{in}),
$$

gdzie $a_{ij}=0$ dla $i<j$.

By dowód twierdzenia zakończyć, wystarczy znaleźć izometrię $\psi$ przestrzeni $C_n$ na siebie, przekształcającą każdy z punktów $\varphi(p_i)$, gdzie $i=0,1,\ldots,k-1$, na siebie, punkt zaś

$$
\varphi(p_k)=(a'_{k1},a'_{k2},\ldots,a'_{kn})
$$

na punkt

$$
(a_{k1},a_{k2},\ldots,a_{kn}),
$$

gdzie $a_{kj}=0$ dla $j>k$. Wówczas bowiem izometria $f=\psi\varphi$ spełniać będzie żądane warunki. Ponieważ w przypadku $k\geq n$ można za $\psi$ wziąć przekształcenie tożsamościowe, możemy więc założyć, że $k<n$. Wówczas izometrię $\psi$ o żądanej własności otrzymamy, składając tożsamość w zakresie współrzędnych $x_1,x_2,\ldots,x_{k-1}$ z izometrią (której istnienie wyżej stwierdziliśmy), przekształcającą punkt $0$ na siebie, a punkt

$$
(a'_{kk},a'_{k,k+1},\ldots,a'_{kn})
$$

na punkt postaci

$$
(a,0,\ldots,0).
$$

Istotnie, przyjmując

$$
a_{ki}=a'_{ki}
\qquad\text{dla }i=1,2,\ldots,k-1,
$$

$$
a_{kk}=a
$$

oraz

$$
a_{kj}=0
\qquad\text{dla }j>k,
$$

mamy

$$
\psi\varphi(p_k)=(a_{k1},a_{k2},\ldots,a_{kn})
$$

oraz $a_{kj}=0$ dla $j>k$.

## Ćwiczenia

1. Znaleźć izometrię $f$, przekształcającą płaszczyznę $C_2$ na siebie w taki sposób, by

$$
f(1,0)=(1,1),
\qquad
f(0,1)=(2,2).
$$

Czy izometria taka istnieje tylko jedna?

2. Oznaczając dla każdego układu punktów

$$
p_i=(a_{i1},a_{i2},\ldots,a_{in}),
\qquad i=0,1,\ldots,n,
$$

przez $V(p_0,p_1,\ldots,p_n)$ wyznacznik

$$
\begin{vmatrix}
1 & a_{01} & a_{02} & \cdots & a_{0n}\\
1 & a_{11} & a_{12} & \cdots & a_{1n}\\
\vdots & \vdots & \vdots & & \vdots\\
1 & a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix},
$$

okazać, że przy przesunięciach i obrotach nie ulega on zmianie. Wywnioskować stąd, które permutacje współrzędnych dadzą się otrzymać przez superponowanie obrotów elementarnych.

3. Podać przykład nieelementarnej izometrii przestrzeni $C_n$ na siebie.

## § 13. Proste i hiperpłaszczyzny w przestrzeniach kartezjańskich

Zbiór przestrzeni $C_n$ izometryczny z przestrzenią $C_k$ nazywać będziemy *hiperpłaszczyzną $k$-wymiarową w $C_n$*. W szczególności hiperpłaszczyzny jednowymiarowe nazywają się *liniami prostymi*, a dwuwymiarowe — *płaszczyznami*.
