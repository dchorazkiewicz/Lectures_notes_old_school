# Strona 39

## § 10. Dodawanie i odejmowanie wektorów

wektora przeciwnego ma charakter niezmienniczy. Pozwala ona określić niezmienniczo różnicę wektorów $a$ i $b$ (rys. 7) przez wzór

\[
a-b=a+[-b].
\]

Wynika stąd, że

\[
\tag{10.2}
[a_1,a_2,\ldots,a_n]-[b_1,b_2,\ldots,b_n]
=
[a_1-b_1,a_2-b_2,\ldots,a_n-b_n].
\]

Stąd otrzymujemy

\[
[a-b]+b=a.
\]

Zbiór wektorów swobodnych przestrzeni $C_n$, z dodawaniem jako operacją grupową, stanowi grupę przemienną. Z punktu widzenia teorii grup nie różni się ona od grupy punktów przestrzeni $C_n$, z dodawaniem punktów jako operacją grupową. Grupa wektorów swobodnych przestrzeni $C_n$, w przeciwieństwie do grupy punktów, określona została przez przestrzeń $C_n$ w sposób niezmienniczy. Jej własności algebraiczne są więc własnościami geometrycznymi przestrzeni $C_n$.

## Ćwiczenie

Niech $p_0,p_1,\ldots,p_k$ będą dowolnymi punktami przestrzeni $C_n$. Okazać, że kładąc

\[
a_i=[\overrightarrow{p_i p_{i+1}}]
\quad\text{dla }i=0,1,\ldots,k-1
\]

oraz

\[
a_k=[\overrightarrow{p_k p_0}]
\]

mamy

\[
a_0+a_1+\cdots+a_k=0.
\]

## § 11. Wektory równoległe i mnożenie wektora przez liczbę

Mówimy, że wektory swobodne $a$ i $b$ są **równoległe i mają jednakowy zwrot**, jeśli

\[
|a+b|=|a|+|b|,
\]

a że są **równoległe i mają zwroty przeciwne**, jeżeli

\[
|a-b|=|a|+|b|.
\]

W obu przypadkach mówimy, że wektory $a$ i $b$ są równoległe.

Jeśli

\[
a=[a_1,a_2,\ldots,a_n]
\quad\text{i}\quad
b=[b_1,b_2,\ldots,b_n],
\]

to oba przypadki równoległości wyrażają się arytmetycznie wzorem

\[
\sum_{i=1}^{n}(a_i\pm b_i)^2
=
\sum_{i=1}^{n}a_i^2+
\sum_{i=1}^{n}b_i^2+
2\sqrt{\left(\sum_{i=1}^{n}a_i^2\right)
\left(\sum_{i=1}^{n}b_i^2\right)},
\]

który równoważny jest równości

\[
\left(\sum_{i=1}^{n}a_i b_i\right)^2
=
\left(\sum_{i=1}^{n}a_i^2\right)
\left(\sum_{i=1}^{n}b_i^2\right).
\]

Okazaliśmy jednak (w § 6), że równość ta zachodzi wtedy i tylko wtedy, gdy układy liczb $[a_1,a_2,\ldots,a_n]$ i $[b_1,b_2,\ldots,b_n]$ są proporcjonalne, tj. gdy istnieją liczby $\lambda$ i $\mu$ nie znikające jednocześnie i takie, że

\[
\lambda a=\mu b.
\]

Jeżeli liczby $\lambda$ i $\mu$ są tego samego znaku, to mamy równoległość ze zwrotem jednakowym, jeśli zaś znaki ich są różne, to mamy równoległość ze zwrotem przeciwnym.

Przez **zwrot wektora** $a\neq0$ rozumiemy przy tym ogół wektorów postaci $\lambda a$, gdzie $\lambda>0$, a przez jego **kierunek** ogół wektorów postaci $\lambda a$, gdzie $\lambda\neq0$. Możemy więc wypowiedzieć następujące:
