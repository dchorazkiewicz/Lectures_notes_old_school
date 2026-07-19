# Strona 52

*I. Punkty i wektory w przestrzeniach kartezjańskich*

przy czym równość ma miejsce jedynie wówczas, gdy wektory $a$ i $b$ są równoległe.

Biorąc pod uwagę, że równość $\cos\theta=0$ jest równoważna warunkowi

$$
\theta=\frac12\pi
\qquad (0\leq\theta\leq\pi),
$$

wnosimy z zależności (15.2), że wektory $a$ i $b$ różne od zera tworzą kąt prosty, czyli że są *ortogonalne*, tj. *prostopadłe* wtedy i tylko wtedy, gdy ich iloczyn skalarny znika.

Pojęcie kąta między wektorami traci swój sens, gdy co najmniej jeden z nich znika. Na ogół wygodnie jest jednak i takie wektory uważać za prostopadłe. A więc:

**(15.14)** *Wektory $a$ i $b$ są prostopadłe wtedy i tylko wtedy, gdy $a\cdot b=0$.*

Jeżeli wektory $a'$ i $b'$ są odpowiednio równoległe do wektorów prostopadłych $a$ i $b$ (nie zerowych), to są one też prostopadłe. Prostopadłość jest więc własnością kierunku; *kierunki wektorów prostopadłych nazywają się prostopadłymi*.

Ze wzoru (15.9) wynika dalej, że jeśli wektor $b$ jest prostopadły do każdego z wektorów $a_1,a_2,\ldots,a_k$, to jest również prostopadły do każdej *kombinacji liniowej* tych wektorów, tj. do każdego wektora postaci

$$
t_1a_1+t_2a_2+\cdots+t_ka_k,
$$

gdzie $t_1,t_2,\ldots,t_k$ są współczynnikami liczbowymi.

Ze wzoru (15.8) wynika, że cosinus kąta wektora

$$
a=[a_1,a_2,\ldots,a_n]\neq0
$$

z wersorem $\mathfrak p_i$ jest równy $a_i/|a|$. Liczby

$$
\frac{a_i}{|a|},
\qquad i=1,2,\ldots,n,
$$

nazywają się *cosinusami kierunkowymi wektora $a$*. Są one jednoznacznie określone dla każdego wektora $a\neq0$, a suma ich kwadratów jest równa $1$.

Dwa wektory

$$
a=[a_1,a_2,\ldots,a_n]
$$

i

$$
a'=[a'_1,a'_2,\ldots,a'_n]
$$

mają jednakowe cosinusy kierunkowe wtedy i tylko wtedy, gdy

$$
\frac{a'_i}{|a'|}=\frac{a_i}{|a|}
\qquad\text{dla }i=1,2,\ldots,n,
$$

czyli gdy

$$
|a|a'=|a'|a,
$$

tj. gdy są równoległe i mają jednakowe zwroty. A więc:

*Cosinusy kierunkowe wyznaczają kierunek i zwrot wektora. Cosinusy kierunkowe wektorów równoległych mających zwroty przeciwne mają znaki przeciwne.*

Iloczyn skalarny pozwala w prosty sposób wyrazić niezmiennik geometryczny zwany *polem trójkąta* o wierzchołkach $a,b,c\in C_n$. Rozumiemy przez to liczbę nieujemną $|\Delta(a,b,c)|$ daną przez następujący wzór Herona[^1]:

$$
|\Delta(a,b,c)|
=
\frac14\sqrt{s[s-2\varrho(b,c)][s-2\varrho(a,c)][s-2\varrho(a,b)]},
$$

gdzie $s$ oznacza sumę

$$
\varrho(b,c)+\varrho(a,c)+\varrho(a,b),
$$

zwaną *obwodem trójkąta*. Z uwagi na nierówność trójkąta, wyrażenie podpierwiastkowe jest nieujemne.

[^1]: Heron z Aleksandrii, matematyk i mechanik z pierwszego wieku p.n.e.
