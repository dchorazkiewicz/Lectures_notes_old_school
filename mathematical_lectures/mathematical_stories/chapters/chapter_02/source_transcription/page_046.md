# Strona 46

*I. Punkty i wektory w przestrzeniach kartezjańskich*

w postaci

$$
p=\frac{a-\theta b}{1-\theta}.
$$

W szczególności dla $\theta=-1$ otrzymujemy środek pary punktów $a$ i $b$.

Oznaczając przez $\mathfrak a$ wektor $[\overrightarrow{ab}]$, a przez $\lambda$ liczbę $1-t$, możemy punkty $p$ prostej $L$ przechodzącej przez punkty $a$ i $b$ przedstawić w postaci

$$
p=a+\lambda(\mathfrak a).
$$

Jest to tzw. *wektorialna postać równania prostej*.

Prosta $L$ nie ulegnie zmianie, gdy punkt $a$ zastąpimy przez jakikolwiek inny punkt $a'\in L$, a wektor $\mathfrak a$ przez jakikolwiek wektor $\mathfrak a'\neq0$ równoległy do $\mathfrak a$. Istotnie, punkt $a'$ jest postaci

$$
a'=a+\alpha(\mathfrak a),
$$

a wektor $\mathfrak a'$ jest postaci

$$
\beta\mathfrak a,
$$

gdzie $\beta\neq0$. A więc

$$
p=a+\lambda(\mathfrak a)
=
a'+(\lambda-\alpha)(\mathfrak a)
=
a'+\frac{\lambda-\alpha}{\beta}(\mathfrak a'),
$$

gdzie $\frac{\lambda-\alpha}{\beta}$ (przy stałych $\alpha$ i $\beta$) przebiega wraz z $\lambda$ wszystkie wartości rzeczywiste. W szczególności dla

$$
\beta=\frac{1}{|\mathfrak a|}
$$

otrzymamy jako $\mathfrak a'$ pewien wersor. Każda prosta ma więc równanie wektorialne postaci

**(13.3)**

$$
p=a+\lambda(\mathfrak a),
$$

gdzie $a$ jest jednym z jej punktów, a $\mathfrak a$ jest wersorem.

Zauważmy, że jeśli równania wektorialne

$$
p=a+\lambda(\mathfrak a)
$$

i

$$
p'=a'+\lambda'(\mathfrak a')
$$

przedstawiają jedną i tę samą prostą, to wektory $\mathfrak a$ i $\mathfrak a'$ są równoległe. Istotnie, wówczas istnieje $\lambda_0$ takie, że

$$
a'=a+\lambda_0(\mathfrak a).
$$

Obierając $\lambda\neq\lambda_0$ znajdziemy takie $\lambda'$, że

$$
a+\lambda(\mathfrak a)=a'+\lambda'(\mathfrak a').
$$

Stąd

$$
(\lambda-\lambda_0)(\mathfrak a)=\lambda'(\mathfrak a'),
$$

co dowodzi równoległości wektorów $\mathfrak a$ i $\mathfrak a'$.

Dzięki temu możemy określić *kierunek prostej* $L$ jako kierunek wektora $\mathfrak a$ przy przedstawieniu $L$ przez równanie wektorialne postaci (13.3). Proste o jednakowym kierunku nazywamy *równoległymi*.

W dalszym ciągu wielokrotnie stosować będziemy oznaczenie następujące: przez $\delta_i^j$ (gdzie wskaźniki $i$ oraz $j$ przebiegają wartości całkowite) rozumieć będziemy liczbę $0$, jeśli $i\neq j$, a liczbę $1$, jeśli $i=j$, czyli

**(13.4)**

$$
\delta_i^j=
\begin{cases}
0, & \text{dla }i\neq j,\\
1, & \text{dla }i=j.
\end{cases}
$$

Wektor przestrzeni $C_n$ określony wzorem

**(13.5)**

$$
\mathfrak p_i=[\delta_1^i,\delta_2^i,\ldots,\delta_n^i]
$$
