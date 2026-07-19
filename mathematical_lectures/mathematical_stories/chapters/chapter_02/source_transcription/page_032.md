# Strona 32

*I. Punkty i wektory w przestrzeniach kartezjańskich*

rzeczywistych, zmetryzowany przez wzór Pitagorasa

**(6.1)**

$$
\varrho\big((x'_1,x'_2,\ldots,x'_n),(x''_1,x''_2,\ldots,x''_n)\big)
=
\sqrt{\sum_{i=1}^{n}(x'_i-x''_i)^2}.
$$

Okażemy przede wszystkim, że tak określona liczba $\varrho$ jest odległością w sensie ustalonym w § 1. Spełnienie dwóch pierwszych warunków jest oczywiste, pozostaje więc stwierdzenie, że $\varrho$ spełnia nierówność trójkąta. Niech $x=(x_1,x_2,\ldots,x_n)$, $y=(y_1,y_2,\ldots,y_n)$, $z=(z_1,z_2,\ldots,z_n)$. Należy okazać, że $\varrho(x,z)\leq \varrho(x,y)+\varrho(y,z)$, czyli że

$$
\sum_{i=1}^{n}(x_i-z_i)^2
\leq
\sum_{i=1}^{n}(x_i-y_i)^2
+
\sum_{i=1}^{n}(y_i-z_i)^2
+
2\sqrt{
\left[\sum_{i=1}^{n}(x_i-y_i)^2\right]
\left[\sum_{i=1}^{n}(y_i-z_i)^2\right]
}.
$$

Przyjmując $\alpha_i=x_i-y_i$ oraz $\beta_i=y_i-z_i$, nierówność tę sprowadzamy do nierówności

$$
\sum_{i=1}^{n}\alpha_i\beta_i
\leq
\sqrt{
\left(\sum_{i=1}^{n}\alpha_i^2\right)
\left(\sum_{i=1}^{n}\beta_i^2\right)
}.
$$

By udowodnić tę ostatnią nierówność, wystarczy oczywiście okazać, że dla wszystkich układów liczb rzeczywistych $\alpha_1,\alpha_2,\ldots,\alpha_n$ i $\beta_1,\beta_2,\ldots,\beta_n$ zachodzi tzw. *nierówność Schwarza-Cauchy’ego*[^2]

**(6.2)**

$$
\left(\sum_{i=1}^{n}\alpha_i\beta_i\right)^2
\leq
\left(\sum_{i=1}^{n}\alpha_i^2\right)
\left(\sum_{i=1}^{n}\beta_i^2\right).
$$

Dla dowodu nierówności (6.2) weźmy pod uwagę wyrażenie

**(6.3)**

$$
\sum_{i=1}^{n}(\alpha_i t+\beta_i)^2
=
t^2\sum_{i=1}^{n}\alpha_i^2
+2t\sum_{i=1}^{n}\alpha_i\beta_i
+\sum_{i=1}^{n}\beta_i^2.
$$

Ponieważ w przypadku znikania wszystkich liczb $\alpha_i$ nierówność Schwarza-Cauchy’ego jest spełniona, więc możemy od razu założyć, że $\sum_{i=1}^{n}\alpha_i^2>0$. Biorąc pod uwagę, że prawa strona równości (6.3) jest trójmianem kwadratowym, przyjmującym przy wszelkich wartościach zmiennej $t$ wartości nieujemne, wnosimy, że wyróżnik tego trójmianu jest niedodatni.

[^2]: H. A. Schwarz — matematyk niemiecki z XIX wieku. A. Cauchy — matematyk francuski (1789–1857).
