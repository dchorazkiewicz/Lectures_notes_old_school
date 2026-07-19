# Strona 51

*§ 15. Iloczyn skalarny wektorów — Kąt między wektorami*

Oznaczmy przez $\theta'$ kąt (w sensie elementarno-geometrycznym, a więc spełniający warunek $0\leq\theta'\leq\pi$), leżący u wierzchołka $p$ tego trójkąta.

Kąt ten zależy jedynie od odległości $\varrho(p,q)$, $\varrho(p,r)$, $\varrho(q,r)$, a więc jest wielkością związaną niezmienniczo z wektorami $a$ i $b$.

Zależność między kątem $\theta'$ a bokami trójkąta dana jest przez znany z trygonometrii elementarnej wzór Carnota[^1] postaci

$$
\varrho(q,r)^2
=
\varrho(p,q)^2+
\varrho(p,r)^2-
2\varrho(p,q)\varrho(p,r)\cos\theta',
$$

który — jak łatwo zauważyć — stosuje się również do przypadku, gdy trójkąt jest zdegenerowany. Ponieważ

$$
\varrho(p,q)^2+
\varrho(p,r)^2-
\varrho(q,r)^2
=
a^2+b^2-(a-b)^2
=
2\sum_{i=1}^{n}a_i b_i,
$$

więc z wzoru Carnota wynika zależność

$$
\sum_{i=1}^{n}a_i b_i
=
|a|\cdot|b|\cos\theta',
$$

czyli

**(15.8)**

$$
a\cdot b=|a|\cdot|b|\cos\theta'.
$$

Wobec (15.2) oraz założenia $a\neq0\neq b$ wynika stąd, że $\cos\theta=\cos\theta'$, a ponieważ zarówno $\theta$, jak i $\theta'$ leżą między $0$ i $\pi$, otrzymujemy $\theta=\theta'$. W ten sposób widzimy, że wprowadzone tu pojęcie (kąta niezorientowanego) $\measuredangle(a,b)$ zgodne jest z pojęciem kąta w sensie elementarno-geometrycznym.

Zestawiając wzory (10.1), (10.2), (11.2) i (15.1) ze wzorami, przy których pomocy w § 7 zdefiniowane zostały działania na punktach, widzimy, że różnica polega jedynie na zmianie interpretacji układów $n$ liczb, które zamiast oznaczać punkty, oznaczają obecnie wektory swobodne. Wynika stąd, że prawa formalne działań na wektorach nie różnią się od praw formalnych odpowiednich działań na punktach przestrzeni $C_n$. Zmianie jednak uległa treść tych działań, mających w odniesieniu do punktów charakter jedynie skrótów rachunkowych, w odniesieniu zaś do wektorów — charakter operacji niezmienniczych.

W szczególności mamy

**(15.9)**

$$
a\cdot b=b\cdot a,
$$

**(15.10)**

$$
\lambda(a\cdot b)=(\lambda a)\cdot b=a\cdot(\lambda b)
\qquad\text{dla każdego }\lambda,
$$

**(15.11)**

$$
a\cdot(b\pm c)=a\cdot b\pm a\cdot c.
$$

Oznaczając iloczyn skalarny $a\cdot a$ przez $a^2$, mamy ponadto

**(15.12)**

$$
(a\pm b)^2=a^2\pm2a\cdot b+b^2,
$$

**(15.13)**

$$
(a\cdot b)^2\leq a^2b^2,
$$

przy czym równość ma miejsce jedynie wówczas, gdy wektory $a$ i $b$ są równoległe.

[^1]: L. N. M. Carnot, mąż stanu i geometra francuski (1754–1823).
