# Strona 42

*I. Punkty i wektory w przestrzeniach kartezjańskich*

izometrią przestrzeni $C_l$ na siebie. Niech dalej $n=k+l$ i niech $A$ oznacza zbiór złożony z pewnych (dowolnych zresztą) $k$ spośród wskaźników $1,2,\ldots,n$ — niech to będą wskaźniki $i_1,i_2,\ldots,i_k$ — zaś $B$ zbiór $l$ wskaźników pozostałych — niech to będą $j_1,j_2,\ldots,j_l$. Niech wreszcie

$$
f(x_1,x_2,\ldots,x_n)
=
(x_1^*,x_2^*,\ldots,x_n^*),
$$

gdzie

$$
x_i^*=
\begin{cases}
\bar x_i, & \text{dla } i\in A,\\
\underline x_i, & \text{dla } i\in B.
\end{cases}
$$

Przekształcenie $f$ jest izometrią przestrzeni $C_{k+l}$ na siebie, gdyż

$$
\varrho[(x_1^*,x_2^*,\ldots,x_n^*),(y_1^*,y_2^*,\ldots,y_n^*)]^2
$$

$$
=
(\bar x_{i_1}-\bar y_{i_1})^2+\cdots+(\bar x_{i_k}-\bar y_{i_k})^2
+(\underline x_{j_1}-\underline y_{j_1})^2+\cdots+(\underline x_{j_l}-\underline y_{j_l})^2
$$

$$
=
(x_{i_1}-y_{i_1})^2+\cdots+(x_{i_k}-y_{i_k})^2
+(x_{j_1}-y_{j_1})^2+\cdots+(x_{j_l}-y_{j_l})^2
$$

$$
=
\varrho[(x_1,x_2,\ldots,x_n),(y_1,y_2,\ldots,y_n)]^2.
$$

Mówimy, że *izometria $f$ powstała przez złożenie izometrii $\varphi$ w zakresie współrzędnych $x_{i_1},x_{i_2},\ldots,x_{i_k}$ oraz izometrii $\psi$ w zakresie współrzędnych $x_{j_1},x_{j_2},\ldots,x_{j_l}$*.

W szczególności, złożenie obrotu w zakresie którychkolwiek dwóch współrzędnych z tożsamością w zakresie pozostałych współrzędnych nazywać będziemy *obrotem elementarnym w przestrzeni $C_n$*; w przypadku $n\leq1$ za obrót elementarny uważać będziemy jedynie przekształcenie tożsamościowe.

Stwierdziliśmy wyżej (str. 41), że istnieje obrót płaszczyzny $C_2$, przy którym dowolnie dany punkt $(a_1,a_2)$ przechodzi na punkt postaci $(a,0)$. Superponując odpowiednio dobrane obroty elementarne, możemy kolejno doprowadzić do znikania współrzędne $x_n,x_{n-1},\ldots,x_2$ i w rezultacie otrzymać *izometrię $f$ spełniającą warunek $f(0)=0$ i przekształcającą dany punkt $(a_1,\ldots,a_n)$ przestrzeni $C_n$ na punkt postaci $(a,0,0,\ldots,0)$*.

Niech teraz $I_n$ oznacza zbiór wszystkich przekształceń izometrycznych przestrzeni $C_n$ na siebie, a $I$ sumę wszystkich zbiorów $I_n$. Weźmy pod uwagę klasę $\mathcal C$ wszystkich zbiorów $F\subset I$ spełniających trzy następujące warunki:

1° Do zbioru $F$ należą wszystkie przesunięcia oraz wszystkie obroty elementarne.

2° Jeżeli dwa przekształcenia $\varphi,\psi\in F$ należą do jednego i tego samego zbioru $I_n$, to ich superpozycja $\varphi\psi$ należy do $F$.

3° Złożenie dwóch izometrii należących do $F$ należy zawsze do $F$.

Jasne jest, że część wspólna $\mathcal E$ wszystkich zbiorów klasy $\mathcal C$ też te warunki spełnia. Przekształcenia należące do $\mathcal E$ nazywać będziemy *izometriami elementarnymi*. Mówiąc obrazowo, są to izometrie, które można otrzymać przez superpozycję i składanie przesunięć i obrotów elementarnych.
