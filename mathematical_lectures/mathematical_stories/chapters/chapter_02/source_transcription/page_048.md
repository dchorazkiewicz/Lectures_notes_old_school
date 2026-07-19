# Strona 48

*I. Punkty i wektory w przestrzeniach kartezjańskich*

**(14.1) TWIERDZENIE.** *Aby izometria $f$ przestrzeni $C_n$ na siebie była przesunięciem, potrzeba i wystarcza, by istniała liczba $M$ taka, że*

$$
\varrho(x,f(x))<M
$$

*dla każdego $x\in C_n$.*

Dowód poprzedzimy następującym lematem:

**(14.2) LEMAT.** *Jeśli $\varphi$ jest izometrią przestrzeni $C_n$ na siebie, przy czym $\varphi(0)=0$, oraz jeśli istnieje liczba dodatnia $a$ taka, że $\varrho(x,\varphi(x))<a$ dla każdego $x\in C_n$, to $\varphi$ jest przekształceniem tożsamościowym.*

**Dowód lematu.** W przypadku $n=1$ mamy

$$
\varphi(x)^2
=
\varrho[0,\varphi(x)]^2
=
\varrho[\varphi(0),\varphi(x)]^2
=
\varrho(0,x)^2
=
x^2.
$$

A więc $\varphi(x)$ jest równe $x$ lub $-x$. Ponieważ

$$
\varrho((a),-(a))=2a>a,
$$

więc wynika stąd, że $\varphi((a))=(a)$. Gdyby teraz istniała liczba $\beta\neq0$ taka, że $\varphi((\beta))=-(\beta)$, to byłoby

$$
\varrho[\varphi((a)),\varphi((\beta))]^2
=
[\varphi((a))-\varphi((\beta))]^2
=
(a+\beta)^2
=
\varrho(a,\beta)^2
=
(a-\beta)^2,
$$

skąd $a\cdot\beta=0$ wbrew temu, że $a\neq0\neq\beta$.

Niech teraz $n>1$. Przypuśćmy, że istnieje punkt $b$ taki, że

$$
\varphi(b)=b'\neq b.
$$

Niech $L$ oznacza prostą łączącą punkty $0$ i $b$. Izometria $\varphi$ przekształca prostą $L$ na prostą łączącą $0$ i $b'=\varphi(b)$. Gdyby $b'\in L$, to izometria $\varphi$ przekształcałaby prostą $L$ na siebie, a więc w myśl rozpatrzonego już przypadku $n=1$ — byłaby tożsamością wbrew przypuszczeniu, że $\varphi(b)\neq b$. Zatem prosta $L'$, łącząca $0$ i $b'$, jest różna od $L$. Wynika stąd, że istnieje liczba dodatnia $\gamma$ taka, że

$$
\varrho(b,b')\geq\gamma
\qquad\text{oraz}\qquad
\varrho(b,-b')\geq\gamma.
$$

Punkty prostej $L$ są, w myśl twierdzenia (13.2), postaci

$$
tb+(1-t)0=tb,
$$

a punkty prostej $L'$ — postaci $tb'$. Dla każdego rzeczywistego $t$ istnieje więc taka liczba $t'$, że

$$
\varphi(tb)=t'b'.
$$

Ponieważ mamy przy tym

$$
\varrho(\varphi(tb),0)=\varrho(tb,0)=|t|\varrho(b,0)
$$

oraz

$$
\varrho(\varphi(tb),0)=\varrho(t'b',0)=|t'|\varrho(b',0)=|t'|\varrho(b,0),
$$

więc $|t|=|t'|$, czyli $t'=\varepsilon_t t$, gdzie $\varepsilon_t$ jest równe $1$ lub $-1$. Wynika stąd, że

$$
\varrho(tb,\varphi(tb))
=
\varrho(tb,t'b')
=
|t|\varrho(b,\varepsilon_t b')
\geq
|t|\gamma,
$$

co dla

$$
|t|>\frac{a}{\gamma}
$$

jest sprzeczne z założeniem, że $\varrho(x,\varphi(x))<a$ dla każdego $x\in C_n$. W ten sposób dowód lematu został zakończony.

**Dowód twierdzenia.** Jeżeli $f$ jest przesunięciem postaci

$$
f(x)=a+x,
$$

to

$$
\varrho(x,f(x))=|a|.
$$

A więc warunek jest konieczny. Pozostaje okazać jego dostateczność. Niech więc $f$ będzie przekształceniem izometrycznym