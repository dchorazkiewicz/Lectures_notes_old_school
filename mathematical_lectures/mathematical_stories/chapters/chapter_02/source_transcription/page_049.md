# Strona 49

*§ 14. Geometryczna charakteryzacja przesunięć*

przestrzeni $C_n$ na siebie, dla którego istnieje stała $M$ większa od $\varrho(x,f(x))$ przy wszelkim $x\in C_n$. Niech

$$
\varphi(x)=f(x)-f(0).
$$

Przekształcenie $\varphi$ jest izometrią, przy czym $\varphi(0)=0$, oraz dla każdego $x\in C_n$ jest

$$
\varrho(x,\varphi(x))
\leq
\varrho(x,f(x))+\varrho(f(x),\varphi(x))
<
M+\sqrt{[f(0)]^2}.
$$

Przy

$$
a=M+\sqrt{[f(0)]^2}
$$

mamy spełnione dla $\varphi$ założenia lematu, skąd wynika, że $\varphi(x)=x$, czyli

$$
f(x)=x+f(0)
$$

dla każdego $x\in C_n$. Izometria $f$ jest więc przesunięciem.

## Ćwiczenie

Okazać, że izometrie, określone analitycznie wzorem

$$
f(x)=a-x,
$$

dają się scharakteryzować geometrycznie jako przekształcenia izometryczne $f$ przestrzeni $C_n$ na siebie takie, że dla pewnego punktu stałego $b$ jest

$$
\varrho(x,f(x))=2\varrho(b,x).
$$

## § 15. Iloczyn skalarny wektorów. Kąt między wektorami

Niech będą dane w przestrzeni $C_n$ dwa wektory $\mathfrak a=[a_1,a_2,\ldots,a_n]$ i $\mathfrak b=[b_1,b_2,\ldots,b_n]$.

Wobec zależności

$$
|\mathfrak a+\mathfrak b|^2
=
\sum_{i=1}^{n}a_i^2
+2\sum_{i=1}^{n}a_i b_i
+\sum_{i=1}^{n}b_i^2,
$$

$$
|\mathfrak a-\mathfrak b|^2
=
\sum_{i=1}^{n}a_i^2
-2\sum_{i=1}^{n}a_i b_i
+\sum_{i=1}^{n}b_i^2,
$$

mamy

$$
\sum_{i=1}^{n}a_i b_i
=
\frac14\big[|\mathfrak a+\mathfrak b|^2-|\mathfrak a-\mathfrak b|^2\big].
$$

Stąd wynika, że wielkość

$$
\sum_{i=1}^{n}a_i b_i
$$

jest w sposób niezmienniczy związana z parą wektorów $\mathfrak a$ i $\mathfrak b$.

Wielkość tę nazywamy *iloczynem skalarnym wektorów $\mathfrak a$ i $\mathfrak b$* i oznaczamy przez $\mathfrak a\cdot\mathfrak b$.

Mamy więc

**(15.1)**

$$
\mathfrak a\cdot\mathfrak b
=
[a_1,a_2,\ldots,a_n]\cdot[b_1,b_2,\ldots,b_n]
=
\sum_{i=1}^{n}a_i b_i.
$$

Zauważmy, że wobec

$$
|\mathfrak a|=\sqrt{\sum_{i=1}^{n}a_i^2}
\qquad\text{i}\qquad
|\mathfrak b|=\sqrt{\sum_{i=1}^{n}b_i^2},
$$

z nierówności Schwarza-Cauchy’ego (6.2) wynika, że