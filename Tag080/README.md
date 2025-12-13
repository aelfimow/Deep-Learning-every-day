# Tag 80

Notizen zum Buch [Buch 4](../Buch4.md).

Ab Seite 209:
* Fully Connected Network
  - vollständig verbundenes neuronales Netz
  - Eingabe: eindimensionaler Vektor
* Flatten
  - Verflachung

Ab Seite 210:
* Logits Layer
  - Softmax als Aktivierungsfunktion
```math
f(c_{j}) = \frac{e^{c_{j}}}{\sum e^{c_{i}}}
```
* Wahrscheinlichkeitsverteilung der Klassen

Ab Seite 211:
* Probleme beim Trainieren
  - explodierende Gradienten
    - engl.: exploding gradients
  - verschwindende Gradienten
    - engl.: vanishing gradients
  - Overfitting
  - Sättigung

Ab Seite 213:
* Gleichverteilung und Normalverteilung für
  - Sigmoidfunktion
  - Tangens hyperbolicus
  - ReLU

Ab Seite 214:
* Dying ReLU
* Leaky ReLU: $f(x) = max(\alpha x, x)$, $\alpha$ sehr klein
* `ELU`
  - Exponential Linear Unit
```math
f(x) = 
\begin{cases}
\alpha(e^{x} - 1), & \text{wenn } x < 0 \\
x, & \text{wenn } x \ge 0
\end{cases}
```
