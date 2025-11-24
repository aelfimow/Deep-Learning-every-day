# Tag 62

Notizen zum Buch [Buch 1](../Buch1.md).

Ab Seite 247:
* Aufteilung der Daten in
  - Trainingsdaten
  - Validierungsdaten
  - Testdaten
* Überanpassung vermeiden

Ab Seite 248:
* überangepasstes System
  - erinnert sich an die Daten
* Regularisierungstechniken
* Gegenteil: Unteranpassung

Ab Seite 250:
* Überanpassung
  - "zu gute Anpassung"

Ab Seite 253:
* unterangepasstes System
* überangepasstes System
  - Trainingsdaten klassifizieren: sehr gut
  - Verarbeitung der Testdaten: weniger gut

* unterangepasstes System
  - beide Aufgaben: nicht gut

* Verzerrung-Varianz-Dilemma
  - engl.: bias-variance trade-off

* Überanpassung und Unteranpassung schließen sich gegenseitig nicht aus

Ab Seite 254:
* Statistiker
  - Überanpassung: hohe Varianz
  - Unteranpassung: starke Verzerrung

* Regularisierung
  - Glättung der Modellfunktion

Ab Seite 256:
* Trainingsdaten, Validierungsdaten, Testdaten:
  - müssen dieselbe Verteilung aufweisen

Ab Seite 258:
* Regularisierung:
  - $L_{1}$
  - $L_{2}$
  - Prinzip: $L_{regularisiert} = L_{nicht-regularisiert} + \lambda \cdot \sum \lvert w_{i} \rvert$
* Hyperparameter $\lambda$
  - Stärke der Regularisierung
