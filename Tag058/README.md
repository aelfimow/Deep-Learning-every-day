# Tag 58

Notizen zum Buch [Buch 1](../Buch1.md).

Ab Seite 187:
* Mini-Batch-Gradientenverfahren

Ab Seite 190:
* Trainingsdaten in kleinere "Batches" aufteilen

Ab Seite 191:
* Slices: `X_train[batch:batch_end]`

Ab Seite 192:
* Epoche
  - äußere Schleife
* Python-Idiom
  - `if __name__ == "__main__"`

Ab Seite 194:
* konvergiert schneller

Ab Seite 195:
* kleinstmögliche Batchgröße: 1
  - stochastischer Gradientenabstieg

Ab Seite 198:
* Vorteil: nicht die gesamte Trainingsdatenmenge im Arbeitsspeicher
  - man kann auch parallel aufteilen
* erreicht geringeren Verlust
