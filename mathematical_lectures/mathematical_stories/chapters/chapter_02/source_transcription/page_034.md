# Strona 34

*I. Punkty i wektory w przestrzeniach kartezjańskich*

Niech

$$
x=(x_1,x_2,\ldots,x_n),
\qquad
y=(y_1,y_2,\ldots,y_n),
\qquad
z=(z_1,z_2,\ldots,z_n)
$$

będą punktami przestrzeni $C_n$. Określamy:

*Dodawanie punktów:*

$$
x+y=(x_1+y_1,x_2+y_2,\ldots,x_n+y_n).
$$

Wynika stąd natychmiast, że $(x+y)+z=x+(y+z)$, czyli że dodawanie jest łączne. Punkt $(0,0,\ldots,0)$ gra rolę zera (i z tego powodu oznaczać go będziemy przez $0$), gdyż $x+0=0+x=x$ dla każdego $x\in C_n$. Oznaczając więc przez $-x$ punkt $(-x_1,-x_2,\ldots,-x_n)$ mamy $x+(-x)=0$. Wynika stąd, że w zbiorze punktów przestrzeni $C_n$ dodawanie „$+$” stanowi operację spełniającą warunki $1^\circ$, $2^\circ$ i $3^\circ$ podane w § 5 definicji grupy (elementem neutralnym jest punkt $0$). Ponieważ dodawanie punktów jest przy tym przemienne, więc możemy wypowiedzieć twierdzenie następujące:

**(7.1) TWIERDZENIE.** *Przestrzeń $C_n$ stanowi grupę abelową, z dodawaniem jako operacją grupową.*

*Odejmowanie punktów:*

$$
x-y=x+(-y).
$$

*Mnożenie punktu przez liczbę:* $\alpha x$, jak również $x\alpha$, gdzie $\alpha$ jest liczbą, oznacza punkt

$$
(\alpha x_1,\alpha x_2,\ldots,\alpha x_n).
$$

*Mnożenie skalarne punktów:*

$$
x\cdot y=\sum_{i=1}^{n}x_i y_i.
$$

W szczególności

$$
x\cdot x=x^2=\sum_{i=1}^{n}x_i^2.
$$

Z definicji tych wynika, że jeśli $x,y,z$ są punktami, a $\alpha$ i $\beta$ liczbami, to mamy

$$
\alpha(x\pm y)=\alpha x\pm \alpha y,
\qquad
\alpha(x\cdot y)=(\alpha x)\cdot y,
$$

$$
(\alpha\pm\beta)x=\alpha x\pm\beta x,
\qquad
\alpha(\beta x)=(\alpha\beta)x,
$$

$$
x\cdot y=y\cdot x,
\qquad
x\cdot(y\pm z)=x\cdot y\pm x\cdot z.
$$

Nie należy jednak sądzić, że wszystkie prawa formalne zwykłego mnożenia zachowują się bez zmiany. W wyrażeniu $(x\cdot y)\cdot z$ pierwsza kropka oznacza mnożenie skalarne punktów, a druga mnożenie liczby przez punkt, tak że na ogół

$$
(x\cdot y)\cdot z\neq x\cdot(y\cdot z).
$$

Na przykład

$$
[(1,1)\cdot(2,1)]\cdot(3,1)=3(3,1)=(9,3),
$$

podczas gdy

$$
(1,1)\cdot[(2,1)\cdot(3,1)]=(1,1)7=(7,7).
$$

Iloczyn skalarny dwóch czynników różnych od zera może być równy zeru, np.

$$
(1,1)\cdot(1,-1)=0.
$$

Jasne jest natomiast, że znikanie iloczynu skalarnego dwóch równych czynników, czyli znikanie kwadratu skalarnego $x^2$, równoważne jest zależności $x=0$.
