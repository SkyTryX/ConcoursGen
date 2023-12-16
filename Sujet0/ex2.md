# Exercice 2
## Partie A
### 1
Les résultats différents possibles de l'exécution de ces deux programmes sont:
- BRVV
- BVRV
- RBVV
- RVBV
## Partie B
### 1
Les résultats différents possibles de l'exécution de ces deux programmes sont:
- BVCRV
- BVRCV
- BVRVC
- RVBVC
### 2
Les résultats différents possibles de l'exécution de ces deux programmes sont:
- RVDBVVC
- RVDVBVC
- RVBVDVC
- RVBDVVC
- BVCRVDV
- BVRCVDV
- BVRVDCV
- BVRVCDV
### 3
Les programmes permettant d'avoir des résultats commençant par R et se terminent par C sont:
```
Programme E1:
ajouter("R")
produire("Rouge")
ajouter("V")
produire("Bleu")
```
```
Programme E2:
consommer("Rouge")
ajouter("B")
consommer("Bleu")
ajouter("C")
```
Il n'y a pas de jeton disponible au départ
Le programme peut renvoyer:
- RVBC
- RBVC
## Partie C
### 1
Les programmes permettant 30 résultats différents avec un nombre de 1 et de 2 indentiques sont:
```
Programme H1:
ajouter("1")
produire("Bleu")
consommer("Rouge")
```

```
Programme H2:
ajouter("2")
produire("Rouge")
consommer("Bleu")
```
Il n'y a pas de jeton disponible au départ.
Il y a 2¹⁰ résultats différents. Cela marche car pour finir l'execution de H2 ou H1, il faut impérativement q^ue l'autre ait commencé à être executer.

### 2 & 3
1 jeton de chaque disponible au départ

```
Programme I1:
consommer("Bleu")
ajouter("1")
produire("Rouge")
```

```
Programme I2:
consommer("Rouge")
ajouter("2")
produire("Bleu")
```
Il y a 4⁵ résultats différents. Cela marche car cette algorithme est fait en sorte que il ne print que 1212 2121 1221 2112 qui ne peuvent pas former un nombre tel que le nombre de 1 et de 2 dans le fichier ne diffère jamais de plus de 1 pendant l’exécution. De plus, il faut impérativement que l'autre ait commencé à être executer.

# FAIT A CORRIGE