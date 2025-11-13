# Tag 51

Notizen zum Buch [Buch 1](../Buch1.md).

Ab Seite 129:
* Ziel: Zeichenerkennung mit einer Genauigkeit von 99%

Ab Seite 131:
* Neuronale Netze viel leistungsfähiger als Perzeptrone

Ab Seite 134:
* $h$: hidden
* früher: Mehrschichtiges Perzeptron
  - oder: künstliches neuronales Netz
  - heute: neuronales Netz

* Knoten
  - in Schichten angeordnet

* Drei Schichten:
  - Eingabeschicht
  - verdeckte Schicht
  - Ausgabeschicht

Ab Seite 135:
* Biasknoten werden beibehalten
* Nicht: "als Array mit zehn Elementen"
  - sondern: "als Matrix mit zehn Spalten und so vielen Zeilen wie nötig"

* Neuronen
* Aktivierungsfunktion

Ab Seite 136:
* Faustregel:
  - die Anzahl der verdeckten Knoten: irgendwo zwischen der Anzahl der Eingabe- und der Ausgabeknoten

* Gewichtsmatrix
  - so viele Zeilen wie Eingabeelemente
  - so viele Spalten wie Ausgabeelemente

Ab Seite 137:
* in der Ausgabeschicht
  - eine Softmax-Funktion

Ab Seite 138:
```math
softmax(l_{i}) = \frac{e^{l_{i}}}{\sum e^{l}}
```

* $l_{i}$: Logits
* Array als Eingabe, Array als Ausgabe
* die Summe der Ausgaben stets $1$
  - Softmax-Funktion normalisiert die Summe auf den Wert $1$
  - wie Wahrscheinlichkeiten

Ab Seite 139:
* keine Standardschreibweise für neuronale Netze
