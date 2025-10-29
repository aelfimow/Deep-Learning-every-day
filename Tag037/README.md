# Tag 37

Notizen zum Buch [Buch 1](../Buch1.md).

Ab Seite 61:
* Matrizenmultiplikation
* Transposition

Ab Seite 62:
* äußere Dimension
* innere Dimension
* Matrizenmultiplikation ist zulässig, wenn die innere Dimensionen gleich sind
  - das Ergebnis ist eine Matrix mit den äußeren Dimensionen

Ab Seite 65:
* Transposition
  - spiegeln an der Diagonale
  - Dimensionen der Matrix werden vertauscht

Ab Seite 67:
* `loadtxt`
* flexible Objekte in NumPy
  - Skalare
  - Arrays
* `shape`: welche Dimensionen weist ein Array auf
* `column_stack`
* `X[:2]`
  - die ersten beiden Zeilen
  - Abkürzung für: X[0:2]: vom Index 0 bis ausschließlich Index 2
* Rat: NumPy-Matrizen nicht mit eindimensionalen Arrays vermischen
  - Trick: `Y = y.reshape(-1, 1)`

Ab Seite 69:
* für $w$ (Gewichte) ist eine $(n,1)$-Matrix besser geeignet
* `X.shape[0]`: Zeilen
* `X.shape[1]`: Spalten

Ab Seite 70:
* Matrixmultiplikation
  - `matmul(X, w)`
* Besonderheit von NumPy
  - Broadcasting, Broadcast-Operationen
* für Skalare
  - `x.shape`: Ausgabe ist ()
