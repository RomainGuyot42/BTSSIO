# Les Boucles 

Les boucles sont utilisées pour effectuer plusieurs fois la même opération dans un programme 

Il existe deux types de boucles :

- les boucles bornées
Utilisé quand on sait combien de fois la répétition vas avoir lieu.

-les boucles non bornées
Utilisé quand on ne sait pas combien de fois la répétition vas avoir lieu.


### les boucles bornées `for`

Pour les boucles bornées on utilise l'instruction `for`.
On l'utilise dans un bloc d'insctruction cela veut dire qu'un `for` aura la même syntaxe qu'un `if`

Exemple 3
````python
for i in range(4):
    print("i a pour valeur", i)
````

##### range()

`range` est une fonction en python qui sert à générer une suite de nombre entier (int) : 

Exemple 
````
range(4)
````
vas générer une suite de 4 entiers de 0 à 3

### les boucles non bornées `while`

Le mot-clé `while` signifie tant que en anglais, le bloc d'instruction sera effectuer tant que la condition est vrai

Syntaxe :
````
while condition:
    Instruction A
````

Exemple 4
````python
x = 1
while x < 10:
    print("x a pour valeur", x)
    x = x * 2
print("Fin")
````
