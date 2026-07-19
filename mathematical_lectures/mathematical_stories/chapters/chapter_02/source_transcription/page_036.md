# Strona 36

*I. Punkty i wektory w przestrzeniach kartezjańskich*

Punkt $c$ nazywamy *środkiem pary punktów* $a$ i $b$, jeżeli

$$
\varrho(a,c)=\varrho(b,c)=\frac12\varrho(a,b).
$$

**(8.7) TWIERDZENIE.** *Dla każdej pary punktów $a,b\in C_n$ istnieje dokładnie jeden środek, a mianowicie punkt $c=\frac12(a+b)$.*

**Dowód.** Że punkt $c=\frac12(a+b)$ jest środkiem pary punktów $a,b$, wynika natychmiast z uwagi, że

$$
\varrho(a,c)
=
\left|a-\frac12(a+b)\right|
=
\frac12|a-b|
=
\frac12|b-a|
=
\left|b-\frac12(a+b)\right|
=
\varrho(b,c).
$$

Niech teraz punkt $d=c+x$ będzie też środkiem pary punktów $a,b$. Wówczas

$$
\varrho(a,d)
=
\frac12|a-b|
=
|a-d|
=
\frac12|a-b-2x|,
$$

skąd

**(8.8)**

$$
|a-b|=|a-b-2x|.
$$

Podobnie

$$
\varrho(b,d)
=
\frac12|a-b|
=
|d-b|
=
\frac12|a-b+2x|,
$$

skąd

**(8.9)**

$$
|a-b|=|a-b+2x|.
$$

Z (8.8) i (8.9) wynika

$$
(a-b)^2-4x(a-b)+4x^2
=
(a-b)^2+4x(a-b)+4x^2,
$$

skąd $x(a-b)=0$. Stąd i z uwagi na (8.9) wynika $4x^2=0$, a więc $x=0$, czyli $d=c$. W ten sposób dowód twierdzenia został zakończony.

Jasne jest, że pojęcie środka jest geometryczne, a więc przy przekształceniu izometrycznym $f$ środek pary punktów $a,b$ przechodzi na środek pary punktów $f(a),f(b)$.

## Ćwiczenia

1. Czy wzór $|x\cdot y|=|x|\cdot|y|$ zachodzi dla każdej pary punktów $x,y\in C_n$?

2. Okazać, że dla punktów $p_1,p_2,\ldots,p_m$ przestrzeni $C_n$ jest

$$
\left|\sum_{i=1}^{m}p_i\right|
\leq
\sum_{i=1}^{m}|p_i|.
$$

Kiedy ma miejsce znak równości?

## § 9. Wektory

Para punktów $p$ i $q$ przestrzeni $C_n$, z uwzględnieniem ich kolejności — czyli para uporządkowana (por. str. 31, notka 1) — nazywa się *wektorem o początku $p$ i końcu $q$*. Wektor ten oznaczamy przez $\overrightarrow{pq}$.

*Współrzędnymi* wektora $\overrightarrow{pq}$ nazywamy współrzędne różnicy $q-p$, a *długością* wektora $\overrightarrow{pq}$ — liczbę $|\overrightarrow{pq}|$ równą odległości punktów $p$ i $q$. A więc

$$
|\overrightarrow{pq}|
=
\varrho(p,q)
=
\sqrt{(p-q)^2}.
$$
