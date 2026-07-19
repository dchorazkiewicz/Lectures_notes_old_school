# Strona 33

*§ 6. Punkty przestrzeni $C_n$*

nej $t$ wartości nieujemne, wnosimy, że wyróżnik tego trójmianu jest niedodatni, czyli że

$$
\left(\sum_{i=1}^{n}\alpha_i\beta_i\right)^2
-
\left(\sum_{i=1}^{n}\alpha_i^2\right)
\left(\sum_{i=1}^{n}\beta_i^2\right)
\leq 0,
$$

co równoważne jest nierówności (6.2), o której dowód chodziło.

Zauważmy, że z przeprowadzonego dowodu wynika, że równość

**(6.4)**

$$
\left(\sum_{i=1}^{n}\alpha_i\beta_i\right)^2
=
\left(\sum_{i=1}^{n}\alpha_i^2\right)
\left(\sum_{i=1}^{n}\beta_i^2\right)
$$

zachodzi wtedy i tylko wtedy, gdy istnieje liczba $t$ spełniająca warunki

$$
\alpha_i t+\beta_i=0
\qquad\text{dla }i=1,2,\ldots,n,
$$

lub też (obejmując przypadek trywialny znikania wszystkich $\alpha_i$), gdy istnieją współczynniki $\lambda$ i $\mu$ nie znikające jednocześnie i takie, że

$$
\lambda\alpha_i=\mu\beta_i
\qquad\text{dla }i=1,2,\ldots,n.
$$

Układy liczb $(\alpha_1,\alpha_2,\ldots,\alpha_n)$ i $(\beta_1,\beta_2,\ldots,\beta_n)$, dla których takie współczynniki $\lambda$ i $\mu$ istnieją, nazywają się *proporcjonalnymi*.

W szczególności jasne jest, że para liczb $(\alpha_1,\alpha_2)$ jest proporcjonalna do pary liczb $(\beta_1,\beta_2)$ wtedy i tylko wtedy, gdy

$$
\alpha_1\beta_2-\alpha_2\beta_1=0.
$$

*Zależność (6.4) zachodzi wtedy i tylko wtedy, gdy układy $(\alpha_1,\alpha_2,\ldots,\alpha_n)$ i $(\beta_1,\beta_2,\ldots,\beta_n)$ są proporcjonalne.*

## Ćwiczenia

1. Niech

$$
\varrho^*\big((x'_1,x'_2,\ldots,x'_n),(x''_1,x''_2,\ldots,x''_n)\big)
=
\sum_{i=1}^{n}|x'_i-x''_i|.
$$

Zbadać, czy tak określona funkcja $\varrho^*$ może być uważana za odległość (w sensie ustalonym w § 1) w zbiorze wszystkich układów $n$ liczb rzeczywistych.

2. Okazać, że (dla $n=2,3,\ldots$) w przestrzeni metrycznej $C_n^*$ otrzymanej przez zastąpienie odległości $\varrho$ przez odległość $\varrho^*$, określoną w ćwiczeniu poprzednim, dla dwóch różnych punktów $a$ i $b$ istnieje na ogół (kiedy?) więcej niż jeden punkt $p$ taki, że

$$
\varrho^*(a,p)=\varrho^*(b,p)=\frac12\varrho^*(a,b).
$$

Wywnioskować stąd, że $C_n^*$ nie jest izometryczna z $C_n$.

3. Okazać, że jeśli

$$
0\leq \alpha<\sum_{i=1}^{n}|x'_i-x''_i|<\beta,
$$

to

$$
\frac{\alpha}{\sqrt n}
\leq
\varrho\big((x'_1,x'_2,\ldots,x'_n),(x''_1,x''_2,\ldots,x''_n)\big)
\leq
\beta.
$$

## § 7$^z$[^1]. Działania na punktach w przestrzeni $C_n$

Okoliczność, że punkty przestrzeni $C_n$ są układami liczb, pozwala wprowadzić pewne działania,

[^1]: Jak już wspomnieliśmy (w przedmowie), wskaźnik „$z$” oznacza, że twierdzenia i zadania z tego paragrafu zachowują się bez zmiany również w dziedzinie zespolonej.