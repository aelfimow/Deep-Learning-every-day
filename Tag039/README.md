# Tag 39

Notizen zum Buch [Buch 1](../Buch1.md).

* NumPy Funktionen aus Kapitel 4 "Hyperräume"

* `column_stack`
  - `X = np.column_stack((x1, x2, x3))`
```
[[13. 26.  9.]
 [ 2. 14.  6.]
 [14. 20.  3.]
 ...]]
```
* jede Zeile addressierbar z.B.: `X[0]`
```
[13. 26.  9.]
```
* Fehlermeldung, wenn index zu groß:
  - `IndexError: index 100 is out of bounds for axis 0 with size 30`

* `X[1:1]` gibt leeres Array zurück: `[]`

* `reshape(zeilen, spalten)`
  - Fehlermeldung: `ValueError: cannot reshape array of size 30 into shape (7,5)`
  - Zeilen mal Spalten muss den Elementen im Array entsprechen
