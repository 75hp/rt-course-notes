
# Porte logique XNOR (NON-OU exclusif)

## Définition

La fonction logique XNOR est l'inverse de la fonction XOR.

La sortie vaut 1 lorsque les deux entrées A et B sont identiques. Elle vaut 0 lorsqu'elles sont différentes.

## Équation logique

$$
S = \overline{A \oplus B}
$$

Cette expression peut également s'écrire :

$$
S = A \cdot B + \overline{A} \cdot \overline{B}
$$

## Table de vérité

| A | B | S |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

## À retenir

- La fonction XNOR correspond à une fonction XOR suivie d'une inversion.
- La sortie vaut 1 si les entrées sont identiques.
- La sortie vaut 0 si les entrées sont différentes.
- La fonction XNOR est également appelée fonction d'équivalence logique.
