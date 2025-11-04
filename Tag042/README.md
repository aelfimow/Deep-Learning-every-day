# Tag 42

Notizen zum Buch [Buch 1](../Buch1.md).

Ab Seite 85:
* lokale Minima sind ein Problem
  - globales Minimum wird gesucht

* logarithmische Verlustfunktion
```math
L = -\frac{1}{m} \sum_{i=1}^{m} (y_{i} \cdot \log(\hat{y}_{i}) + (1 - y_{i}) \cdot \log(1 - \hat{y}_{i}))
```

Ab Seite 86:
```math
\frac{\partial L}{\partial w} = \frac{1}{m} \sum_{i=1}^{m} x_{i}(\hat{y}_{i} - y_{i})
```

Ab Seite 89:
* Unterschied: Modell und Verlust des Modells
  - zwei verschiedene Funktionen
  - sind miteinander verwandt
