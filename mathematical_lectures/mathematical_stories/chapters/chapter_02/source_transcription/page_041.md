# Strona 41

## § 12. Izometrie elementarne

1. *Przesunięcia* (rys. 8) są to przekształcenia przestrzeni $C_n$ określone wzorem

$$
f(x)=a+x,
$$

gdzie $a$ jest stałym punktem przestrzeni $C_n$. Są to izometrie, gdyż

$$
\varrho[f(x),f(y)]
=
\sqrt{[f(x)-f(y)]^2}
$$

$$
=
\sqrt{[(a+x)-(a+y)]^2}
=
\sqrt{(x-y)^2}
=
\varrho(x,y).
$$

2. *Obroty płaszczyzny.* Niech $\alpha$ będzie dowolnie daną liczbą rzeczywistą. Przyjmując dla każdego punktu $x=(x_1,x_2)\in C_2$

$$
f(x)
=
(x_1\cos\alpha-x_2\sin\alpha,
 x_1\sin\alpha+x_2\cos\alpha),
$$

otrzymamy przekształcenie płaszczyzny $C_2$ na siebie zwane *obrotem o kąt $\alpha$* (rys. 9). Jest ono izometrią, jeżeli bowiem $y=(y_1,y_2)\in C_2$, to

$$
\varrho[f(x),f(y)]^2
=
[(x_1-y_1)\cos\alpha-(x_2-y_2)\sin\alpha]^2
$$

$$
+
[(x_1-y_1)\sin\alpha+(x_2-y_2)\cos\alpha]^2
$$

$$
=
(x_1-y_1)^2+(x_2-y_2)^2
=
\varrho(x,y)^2.
$$

Przy tym przekształceniu punkt $(r\cos\theta,r\sin\theta)$ przejdzie na punkt

$$
(r\cos\alpha\cos\theta-r\sin\alpha\sin\theta,
 r\sin\alpha\cos\theta+r\cos\alpha\sin\theta)
$$

$$
=
(r\cos(\alpha+\theta),r\sin(\alpha+\theta)).
$$

Jasne jest jednak, że dla każdego punktu $x=(x_1,x_2)$ istnieje liczba $\theta$ taka, że przyjmując

$$
r=\sqrt{x_1^2+x_2^2}
$$

mamy

$$
x_1=r\cos\theta,
\qquad
x_2=r\sin\theta.
$$

Obierając $\alpha=-\theta$, stwierdzamy od razu, że przy obrocie o kąt $\alpha$ punkt $x$ przejdzie na punkt $(r,0)$. A więc *dla każdego punktu płaszczyzny istnieje obrót, przy którym punkt ten przechodzi na punkt położony na odciętych* (o odciętej $\geq0$).

3. Kolejne wykonanie po sobie dwóch izometrii (czyli ich *superpozycja*) daje przekształcenie będące również izometrią.

Poza tym przekształcenie *odwrotne* względem izometrii jest oczywiście też izometrią. Biorąc to pod uwagę i korzystając z pojęcia grupy, widzimy, że *ogół izometrii danej przestrzeni na siebie stanowi grupę przekształceń*.

Warto zauważyć, że obroty płaszczyzny $C_2$ stanowią grupę zawartą w grupie wszystkich przekształceń izometrycznych płaszczyzny na siebie, a więc *podgrupę grupy izometrii płaszczyzny $C_2$*.

Podobnie, przesunięcia przestrzeni $C_n$ stanowią podgrupę wszystkich izometrii przestrzeni $C_n$ na siebie, która z kolei jest podgrupą grupy wszystkich przekształceń $C_n$ na siebie *wzajemnie jednoznacznych*, tj. takich, które różnym punktom przyporządkowują zawsze różne punkty.

Jasne jest, że część wspólna ilukolwiek podgrup danej grupy przekształceń jest zawsze też podgrupą grupy $G$.

4. *Składanie izometrii.* Niech

$$
\varphi(x_1,x_2,\ldots,x_k)
=
(\bar x_1,\bar x_2,\ldots,\bar x_k)
$$

będzie izometrią przestrzeni $C_k$ na siebie, a

$$
\psi(x_1,x_2,\ldots,x_l)
=
(\underline x_1,\underline x_2,\ldots,\underline x_l)
$$
