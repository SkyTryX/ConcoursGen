# Exercice 1
## Partie A
### 1
(2, 1)
-1
1
-1
1
### 2
Il est possible de les sauver
```
bouger("S")
bouger("O")
bouger("E")
bouger("E")
for i in range(3):
    bouger("N")
```
### 3
```
def afficherEtat(robot):
    for ligne in range(nbLignes):
        for colonne in range(nbColonnes):
        contenuCase = grille[ligne][colonne]
        if contenuCase == robot:
            return (colonne, ligne)
        if robot in robotsSauves:
            return 1
        return -1
```
Le cout de temps d'appel de cette fonction est aussi de nbLignes x nbColonnes
## Partie B
Il faut faire un dictionnaire tel que {nom_robot:{"x":x, "y":y}}
Cout de l'appel: constante 
Cout en mémoir: nbRobots
## Partie C
### 1
1010010000
Soit 512 + 128 + 16 = 656
### 2
```
def union_ensemble(ensemble_1, ensemble_2):
    return ensemble_1 | ensemble_2
```
### 3
```
def numeros_robot_ensemble(e):
    b = bin(e).split("0b")[1]
    return [b[i] for i in range(len(b))]
```
### 4
```

```

### 5
```
...
```
## Partie D
*Besoin de plonger dans la compléxité*