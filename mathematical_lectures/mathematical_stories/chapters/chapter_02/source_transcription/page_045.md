# Strona 45

*§ 13. Proste i hiperpłaszczyzny w przestrzeniach kartezjańskich*

o $\varrho((x),\varphi(0))$, a ponieważ jednym z nich jest punkt $(x)$, więc punkt ten występuje wśród wartości izometrii $\varphi$.

Aby wreszcie dowieść 3°, rozpatrzmy izometrię $g$ przekształcającą $C_1$ na $K$. Wobec $a,b\in K$, istnieją liczby $\alpha,\beta$ takie, że $a=g(\alpha)$, $b=g(\beta)$, przy czym możemy założyć, że $\alpha<\beta$. Niech teraz $c=g(\gamma)$ będzie dowolnym punktem prostej $K$ różnym od $a$ i $b$. Zachodzi wówczas jeden z trzech przypadków:

$$
\alpha<\beta<\gamma,
\qquad\text{lub}\qquad
\alpha<\gamma<\beta,
\qquad\text{lub}\qquad
\gamma<\alpha<\beta.
$$

W pierwszym przypadku

$$
|\beta-\alpha|+|\gamma-\beta|=|\gamma-\alpha|,
$$

a ponieważ $g$ jest izometrią, więc

$$
\varrho(b,a)+\varrho(c,b)=\varrho(c,a),
$$

czyli

$$
|[a-b]|+|[b-c]|=|[a-b]+[b-c]|.
$$

A więc wektory $[a-b]$ i $[c-b]$ są równoległe, czyli (w myśl twierdzenia (11.1)) istnieje liczba rzeczywista $\lambda$ taka, że

$$
c-b=\lambda(a-b),
$$

skąd

$$
c=\lambda a+(1-\lambda)b=p(\lambda)\in L.
$$

Podobnie okazuje się, że i w pozostałych przypadkach $c\in L$, więc $K\subset L$, i dowód twierdzenia jest zakończony.

Zależność

$$
p(t)=ta+(1-t)b,
$$

wyrażająca punkty prostej przechodzącej przez $a$ i $b$ w postaci funkcji parametru $t$, nazywa się *równaniem parametrycznym tej prostej*. O prostej tej powiemy, że jest przez punkty $a$ i $b$ *wyznaczona*.

Wobec zależności

$$
p(t_1)-p(t_2)=(t_1-t_2)(a-b)
$$

mamy

$$
\varrho(p(t_1),p(t_2))
=
|t_1-t_2|\varrho(a,b),
$$

czyli odległość dwóch punktów tej prostej jest proporcjonalna do absolutnej wartości różnicy parametrów, przy czym współczynnikiem proporcjonalności jest odległość punktów $a$ i $b$.

Dla punktu

$$
p=p(t)=ta+(1-t)b
$$

mamy

$$
p-a=(t-1)(a-b),
\qquad
p-b=t(a-b).
$$

Jeśli $a\neq p\neq b$, to $0\neq t\neq1$ i mamy

$$
p-a=\frac{t-1}{t}(p-b),
$$

gdzie współczynnik

$$
\theta=\frac{t-1}{t}
$$

jest różny od $0$ i od $1$.

Współczynnik ten nazywa się *stosunkiem pojedynczego podziału punktów $a$ i $b$ przez punkt $p$*.

Ponieważ

$$
t=\frac{1}{1-\theta},
\qquad
a\quad 1-t=\frac{-\theta}{1-\theta},
$$

więc każdy punkt $p$ prostej wyznaczonej przez punkty $a,b$ i różny od tych punktów, daje się wyrazić
