# Tag 64

Notizen zum Buch [Buch 1](../Buch1.md).

Ab Seite 270:
* Nicht-lineare Aktivierungsfunktion unverzichtbar

Ab Seite 271:
* Sigmoide kann gesättigt werden
  - durch große positive Eingaben
  - durch große negative Eingaben
  - tote Neuronen

Ab Seite 272:
* tote Neuronen
  - langsame Backpropagation

Ab Seite 273:
* Problem: verschwindender Gradient
  - die meisten schichten lernen nichts
* Problem: explodierender Gradient

Ab Seite 274:
* `ReLU`
  - rectified linear unit
  - gleichgerichtete lineare Einheit

Ab Seite 275:
* `Dense(N, activation='relu')`

Ab Seite 276:
* tote `ReLU`
  - "undichte" `ReLU`

Ab Seite 277:
* Softplus-Funktion
* Swish-Funktion
* einfache Standardvorgehensweise
  - verwende zunächst `ReLU`s

Ab Seite 278:
* Unterschiede: Skalare vorhersagen
  - Ausgabeschicht: ein Knoten
  - keine Kreuzentropie
  - für skalare geeignete Verlustfunktion
  - keine Aktivierungsfunktion erforderlich in der Ausgabeschicht

Ab Seite 279:
* Gewichtsinitialisierung
  - Xavier
  - Glorot

Ab Seite 280:
* Prinzip:
```math
\lvert w \rvert \leq \sqrt{\frac{2}{Anzahl der Knoten}}
```
* Keras
  - `kernel_initializer`
  - `SGD`-Parameter
    - `lr`, `decay`, `momentum`

Ab Seite 281:
* abklingende Lernrate
  - learning rate decay

Ab Seite 282:
* `momentum`
  - kann das Training beschleunigen
* `RMSprop`
* `Adam`
