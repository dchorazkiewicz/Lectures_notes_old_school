# Strona 44

*I. Punkty i wektory w przestrzeniach kartezjańskich*

Przykładem hiperpłaszczyzny $k$-wymiarowej w $C_n$ (gdzie $k\leq n$) jest zbiór wszystkich punktów $(x_1,x_2,\ldots,x_n)$ takich, że $x_i=0$ dla $i>k$; zbiór ten będziemy oznaczać przez $C_{nk}$. W szczególności $C_{n0}=(0)$, a $C_{nn}=C_n$.

Z twierdzenia (12.1) wynika, że dla każdego układu $k+1$ danych punktów przestrzeni $C_n$, gdzie $k\leq n$, istnieje izometria $f$ przekształcająca $C_n$ na siebie w taki sposób, że punkty te przechodzą na punkty leżące w $C_{nk}$. Izometria odwrotna przekształca wówczas $C_{nk}$ na pewną hiperpłaszczyznę $k$-wymiarową leżącą w $C_n$ i przechodzącą przez punkty dane. W ten sposób poprzednie twierdzenie pozwala wypowiedzieć następujący:

**(13.1) WNIOSEK.** *Przez każdy układ $k+1$ punktów przestrzeni $C_n$, gdzie $k\leq n$, przechodzi co najmniej jedna hiperpłaszczyzna $k$-wymiarowa leżąca w $C_n$.*

W szczególności przez każde dwa punkty przestrzeni $C_n$, gdzie $n\geq1$, przechodzi co najmniej jedna prosta, przez trzy (gdy $n\geq2$) — płaszczyzna itd. Otrzymany wniosek nie przesądza, ile hiperpłaszczyzn można przeprowadzić przez dany układ punktów. W odniesieniu do prostej odpowiedź na to pytanie daje następujące:

**(13.2) TWIERDZENIE.** *Przez każde dwa różne punkty $a$ i $b$ w przestrzeni $C_n$ przechodzi dokładnie jedna prosta. Jest ona identyczna ze zbiorem $L$ punktów postaci*

$$
p(t)=ta+(1-t)b,
$$

*gdzie parametr $t$ przebiega wszystkie wartości rzeczywiste.*

**Dowód.** Wystarczy okazać, że:

1° Zbiór $L$ jest prostą przechodzącą przez $a$ i $b$.

2° Prosta nie przystaje do żadnego swego podzbioru właściwego.

3° Jeżeli $K\subset C_n$ jest prostą przechodzącą przez punkty $a$ i $b$, to $K\subset L$.

Aby dowieść 1°, przyjmijmy

$$
f(x)=p\left(\frac{x}{\varrho(a,b)}\right)
$$

dla każdego $(x)\in C_1$.

Otrzymujemy przekształcenie $C_1$ na $L$, które jest izometrią, bowiem

$$
\varrho[f(x),f(x')]^2
=
\left[
\frac{(x-x')a-(x-x')b}{\varrho(a,b)}
\right]^2
$$

$$
=
(x-x')^2
=
\varrho((x),(x'))^2.
$$

Zbiór $L$ jest więc prostą, przy czym wobec $p(1)=a$ oraz $p(0)=b$ prosta ta przechodzi przez $a$ i $b$.

Aby dowieść 2°, przypuśćmy, że $\varphi$ jest izometrią przekształcającą prostą $C_1$ na jej podzbiór. Zauważmy, że dla każdego $(a)\in C_1$ i każdej liczby $\alpha>0$ istnieją dokładnie dwa punkty prostej $C_1$ oddalone o $\alpha$ od $a$, gdyż równanie

$$
(x-a)^2=\alpha^2
$$

ma dokładnie dwa pierwiastki:

$$
x=a+\alpha
\qquad\text{i}\qquad
x=a-\alpha.
$$

Jeśli teraz $(x)$ jest dowolnym punktem prostej $C_1$ różnym od $\varphi(0)$, to izometria $\varphi$ musi przekształcać parę punktów $(x)-\varphi(0)$ i $\varphi(0)-(x)$ oddalonych od $0$ o $\varrho((x),\varphi(0))$ na parę punktów oddalonych od $\varphi(0)$
