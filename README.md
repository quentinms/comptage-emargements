# Comment compter les émargements de manière à réduire les erreurs et faciliter le recompte le cas échéant

Par Lison Jullien et [Quentin Mazars-Simon](https://twitter.com/quentinms)

## Motivation

Cette méthode a été développée en partant des observations suivantes :

* Après une journée de 10h+ au bureau de vote, le comptage doit être aussi simple que possible afin de minimiser les erreurs due à la fatigue.
* La partie la plus longue et sujette aux erreurs du comptage vient de fait de devoir parcourir le livre d’émargement. Pouvoir faire les additions sans avoir à retraverser la liste permet une recompte plus rapide, et inversement verifier le nombre de signature sans avoir à faire des additions permets de limiter les erreurs.

Elle se compose de deux étapes :

1. Inscrire le nombre de signatures de chaque page sur une feuille à part.
2. Additioner le nombre de signature.

## Déroulement

Il faut au moins deux personnes, mais avoir une troisième permettra de réduire les chances d’erreurs.

Matériel nécessaire : papier quadrillé (si possible), stylos, calculatrices.

### Signatures

Une première personne A tourne chaque page de la liste d’émargement en énonçant le numéro de page et le nombre de signature. La deuxième personne B vérifie le nombre de signatures et l’inscrit sur une feuille, en allant à la ligne pour chaque page. Arrivé en bas de la page, on continue sur une deuxième colonne. Si une troisième personne C est présente, elle peut vérifier le nombre de signature énoncé par A et noté par B.

Lire le numéro de page avant le nombre de signature permet de réaliser qu’une page a été sautée.

Une fois l’ensemble de la liste d’émargement traversée, vérifiez que le nombre de signatures notées correspond au nombre de pages de la liste.

Par exemple, pour une liste de 23 pages :

|       | 1-5 | 6-10 | 11-15 | 16-20 | 21-25 | Total |
|-------|:---:|:----:|:-----:|:-----:|:-----:|-------|
|       |  2  |   3  |   1   |   1   |   3   |       |
|       |  3  |   6  |   5   |   2   |   5   |       |
|       |  7  |   4  |   8   |   7   |   6   |       |
|       |  5  |   9  |   4   |   7   |   -   |       |
|       |  9  |   0  |   5   |   6   |   -   |       |
| **Total** |     |      |       |       |       |       |

### Additions

A et B additionnent les signatures ligne par ligne, puis colonne par colonne. Les totaux doivent correspondre.
Si possible indépendamment, de manières différentes (par exemple A fait les calculs à la main et B sur une calculatrice).

Avec l'exemple précédent :

|       | 1-5 | 6-10 | 11-15 | 16-20 | 21-25 | Total |
|-------|:---:|:----:|:-----:|:-----:|:-----:|-------|
|       |  2  |   3  |   1   |   1   |   3   | 10    |
|       |  3  |   6  |   5   |   2   |   5   | 21    |
|       |  7  |   4  |   8   |   7   |   6   | 32    |
|       |  5  |   9  |   4   |   7   |   -   | 25    |
|       |  9  |   0  |   5   |   6   |   -   | 20    |
| **Total** |  26 |  22  |   23  |   23  |  14   |108\108|

### En cas d’erreur

Si par malchance, le total des signatures et des enveloppes ne correspondait pas :

* Commencez par refaire les additions. C’est rapide à faire. S’il n’y a pas d’erreur, il faudra repasser toute la liste.
* B lit page par page le nombre de signatures et A vérifie que les nombres précédemment notés correspondent. Si une erreur est relevée, finir la liste et refaire les additions.

### Resources

[Imprimer cette page](javascript:window.print())

Feuilles de relevé pour liste de [100](), [200]() et [400]() pages.
