# Tag 9

Notizen zum Buch [Buch 1](../Buch1.md).

Ab Seite 44:
* Verlustkurve
  - Steigung der Verlustkurve
  - Gradient: ein "Pfeil", der bergauf weist

Ab Seite 45:
* $\frac{\partial L}{\partial w}$
  - $L$: "Loss", Verlustfunktion
  - $w$: "weight", Gewicht, Steigung

* Gradientenverfahren
  - Verfahren des steilsten Abstiegs

* Verlustfunktion
```math
L = \frac{1}{m} \sum_{i=1}^{m} ((wx_{i} + b) - y_{i})^2
```
* Partielle Ableitung
```math
\frac{\partial L}{\partial w} = \frac{2}{m} \sum_{i=1}^{m} x_{i}((wx_{i} + b) - y_{i})^2
```
