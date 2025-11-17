# Tag 55

Notizen zum Buch [Buch 1](../Buch1.md).

Ab Seite 160:
* $\sigma$: Sigmoide
* `SML`: Softmax-Funktion und die Kreuzentropie

Ab Seite 161:
* die Ableitung der Sigmoide

Ab Seite 163:
* Division mit `X.shape[0]`
  - ergibt durchschnittlichen Gradienten

Ab Seite 166:
* Gewichte initialisieren
  - niemals mit demselben Wert

Ab Seite 167:
* Zufallswerte für Gewichte
  - nie mit großen Werten
  - numerische Stabilität

Ab Seite 168:
* "Sigmoide gesättigt"
  - aus dem idealen Definitionsbereich in einen verlagert, in dem der Gradient sehr gering ist

* Dominoeffekt
  - je größer das Gewicht
  - desto kleiner der Gradient der Sigmoide
  - umso langsamer das Gradientenverfahren

* Jargon des `ML`
  - "das Gewicht wird zu einem toten Neuron"
  - bleiben für alle Zeiten auf demselben Wert
