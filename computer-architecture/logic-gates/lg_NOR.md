
# Porte logique NOR (NON-OU)

## Définition

La fonction logique NOR est l'inverse de la fonction OR (OU).

La sortie vaut 1 uniquement lorsque les deux entrées A et B valent 0. Dès qu'au moins une entrée vaut 1, la sortie vaut 0.

## Équation logique

$$
S = \overline{A + B}
$$

D'après les lois de De Morgan, cette expression peut également s'écrire :

$$
S = \overline{A} \cdot \overline{B}
$$

## Table de vérité

| A | B | S |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |

## À retenir

- La fonction NOR correspond à une fonction OR suivie d'une inversion.
- La sortie vaut 1 uniquement si toutes les entrées valent 0.
- La porte NOR est une fonction logique universelle : elle permet de réaliser les autres fonctions logiques à elle seule.
