# Tag 77

Notizen zum Buch [Buch 4](../Buch4.md).

Ab Seite 174:
* Sigmoide
* `SE`: Squared Error
* `MSE`: Mean Squared Error
```math
E = \frac{1}{2} \sum_{i=1}^{n} (y_{i} - \hat{y}_{i})^2
```

Ab Seite 175:
* Error-Backpropagation
* $\Delta w_{ji} = -\eta \cdot \delta_{j} \cdot o_{i}$
  - Lernrate: $\eta$
  - Output des Neurons $i$: $o_{i}$
  - Wert, der anteilig für $w_{ji}$ errechnet wurde: $\delta_{j}$

* Falls Output-Neuron: $o_{j} \cdot (1 - o_{j}) \cdot (y_{j} - \hat{y}_{j})$
* Falls Hidden-Neuron: $o_{j} \cdot (1 - o_{j}) \cdot \sum_{k} \delta_{k} \cdot w_{jk}$
