# Exercice 9

## 1. Réaliser le motif ci-dessous

![motif](img/ex8.JPG)

(ATTENTION le paper fait toujours 5 case de haut !)

Pour ce faire, il faudra obligatoirement :
+ Écrire une fonction permettant de colorier une colonne. (Penser que l'on pourrait réutiliser cette fonction à n'importe quelle colonne du paper (curseur toujours en 1ère ligne évidemment)...)
+ Écrire une fonction permettant d'espacer les colonnes.
+ Écrire le programme permettant de dessiner le motif demandé en appelant (éventuellement plusieurs fois, bien entendu) ces 2 fonctions.

## 2. Généraliser le programme à un nombre n (variable) de colonnes

Pour cette version, on garde nos fonctions telles quelles, mais il faut maintenant réécrire le programme (la fonction main) pour qu'il appelle ces fonctions correctement en boucle de manière à obtenir n colonnes coloriées. Pour cela, on utilisera une variable nommée n contenant le nombre de colonnes à dessiner.

Une variable est une zone de la mémoire qui contient des informations (des données) que l'on peut faire **varier** (d'où le nom de "variable").

Nous aurons besoin de retenir et utiliser uniquement un nombre entier dans notre variable.

Pour cela, nous pourrons déclarer une variable nommée `n` qui contiendra le nombre de colonnes à dessiner (ici, 3) :
```C
int n=3;
```

Cette variable s'écrira au-dessu de :
```C
int main()
{
    //...
}
```

! Il faudra calculer le nombre total de colonnes du Paper en fonction de cette variable `n`, pour cela on peut notamment multiplier avec le signe `*` et soustraire avec le signe `-`.

Rappel du motif (avec n=3 pour la version 2) :
![motif](img/ex8.JPG)

@[Exercice 9]({"stubs": ["main.c"],"command": "sh /project/target/run.sh", "project" : "exercices"})
