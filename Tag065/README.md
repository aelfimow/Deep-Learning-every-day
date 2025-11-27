# Tag 65

Notizen zum Buch [Buch 1](../Buch1.md).

Ab Seite 283:
* Dropout-Technik
  - zufälliges Abschalten einiger Knoten
  - `Dropout()`

* Keras Definition einer Schicht
  - alles, was dem Modell mit `add()` hinzugefügt wird

Ab Seite 284:
* Batchnormalisierung

Ab Seite 285:
* `Batchnormalization()`

Ab Seite 289:
* Dichte Schichten
  - jeder Knoten einer Schicht ist mit allen Knoten der benachbarten Schicht verbunden
  - vollständig verbundenes neuronales Netz

Ab Seite 290:
* neuronales Faltungsnetz
  - `CNN`: Convolutional Neural Network
  - Grundoperation: Faltung

Ab Seite 291:
* `CIFAR-10`
  - Canadian Institute For Advanced Research
  - 60000 Bilder Trainingsdatensatz
  - 10000 Bilder Testdatensatz
* Tensoren
  - $(32, 32, 3)$-Tensoren
  - 32x32 Pixel `RGB`

Ab Seite 294:
* vierstufige Tensoren
  - d.h. vierdimensionale Arrays
* Faltungsschichten
* Faltung
  - Operation zwischen einem Bild und einem Filter

Ab Seite 296:
* Unterschied
  - vollständig verbundenes Netz
    - die Gewichte werden mit der Eingabe multipliziert
  - Faltungsnetz: die Gewichte sind in einem Filter angeordnet, der über die Eingabe hinwegzieht

* `CNN`
  - Convolutional Neural Network
  - Faltungsnetze

* Eigenschaft: Verschiebungsinvarianz
