
# Porte logique NAND (NON-ET)

## Définition

La fonction logique NAND est l'inverse de la fonction AND (ET).

La sortie vaut 0 uniquement lorsque les deux entrées A et B valent 1. Dans tous les autres cas, la sortie vaut 1.

## Équation logique

$$
S = \overline{A \cdot B}
$$

D'après les lois de De Morgan, cette expression peut également s'écrire :

$$
S = \overline{A} + \overline{B}
$$

## Table de vérité

| A | B | S |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

## À retenir

- La fonction NAND correspond à une fonction AND suivie d'une inversion.
- La sortie vaut 0 uniquement si toutes les entrées valent 1.
- La porte NAND est une fonction logique universelle : elle permet de réaliser les autres fonctions logiques à elle seule.
