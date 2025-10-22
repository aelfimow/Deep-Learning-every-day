# Tag 30

Notizen zum Buch [Buch 5](../Buch5.md).

Ab Seite 26:
* "Feature" und "Repräsentation" werden synonym verwendet

Ab Seite 27:
* Machine Learning (`ML`)
  - Traditional Machine Learning
    - lineare/logistische Regression
    - Entscheidungsbäume/Random Forest
    - Support Vector Machines
  - Representation Learning
    - Künstliche Neuronale Netze/Deep Learning

Ab Seite 29:
* benannte Objekte:
  - Orte
  - bekannte Personen
  - Unternehmensnamen
  - Produkte

Ab Seite 31:
* 1-aus-n-Kodierung
  - auch: One-Hot-Kodierung
* Wortverktoren

Ab Seite 32:
```math
\begin{pmatrix}
    && The && bat && sat && on && the && cat \\
the &&  1  &&  0  &&  0  && 0  &&  0  &&  0  \\
bat &&  0  &&  1  &&  0  && 0  &&  0  &&  0  \\
on  &&  0  &&  0  &&  0  && 1  &&  0  &&  0  \\
\end{pmatrix}
```
* dünn besetzte Matrix
  - einschränkender Faktor in Sprachanwendungen

Ab Seite 34:
* word2vec
  - arXiv: 1301.3781
  - GloVe
  - $n$-dimensionaler Vektorraum
