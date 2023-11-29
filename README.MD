# Insertion Sort Algorithm

## Description

L'algorithme "Insertion Sort" est un algorithme de tri simple qui fonctionne de la même manière que le tri des cartes à jouer dans nos mains. À chaque fois qu'une nouvelle carte est prise, elle est insérée à la bonne place dans notre main.

L'algorithme suit les instructions suivantes :

- À chaque itération, travaillez uniquement avec les premiers i-1 éléments du tableau.
- Sélectionnez l'élément arr[i] et insérez-le dans la séquence triée dans le tableau de 0 à i-1.

## Pseudocode

```plaintext
ALGORITHM InsertionSort
VAR
   n: longueur du tableau
   arr: tableau à trier
   i, j, key: entiers
BEGIN
   FOR i = 1 TO n-1
      key = arr[i]
      j = i - 1

      WHILE j >= 0 AND arr[j] > key
         arr[j + 1] = arr[j]
         j = j - 1

      arr[j + 1] = key
   END FOR
END
```
