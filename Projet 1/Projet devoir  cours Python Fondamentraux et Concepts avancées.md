## Projet devoir : cours Python Fondamentraux et Concepts avancées 

- Prof : Mr SY 

- Classe : Master 1 DSIA 

- School : Institut Supérieure Informatique 

  



### Assignment

Les élèves de l'école primaire arrangent  souvent les problèmes d'arithmétique verticalement pour les rendre plus faciles à résoudre. Par exemple, "235 + 52" devient 

```
  235
+  52
-----
```

Créez une fonction qui reçoit une liste de chaînes de caractères qui sont des problèmes arithmétiques et renvoie les problèmes disposés verticalement et côte à côte. La fonction doit éventuellement prendre un deuxième argument. Lorsque le second argument est défini sur "Vrai", les réponses doivent être affichées.

### Par exemple

Appel de la fonction:

```
arithmetic_arranger(["32 + 698", "3801 - 2", "45 + 43", "123 + 49"])
```

Output:

```
   32      3801      45      123
+ 698    -    2    + 43    +  49
-----    ------    ----    -----
```

Appel de la fonction:

```
arithmetic_arranger(["32 + 8", "1 - 3801", "9999 + 9999", "523 - 49"], True)
```

Output:

```
  32         1      9999      523
+  8    - 3801    + 9999    -  49
----    ------    ------    -----
  40     -3800     19998      474
```

### Régles 

La fonction renvoie la conversion correcte si les problèmes fournis sont correctement formatés, sinon, elle **renvoie** une **chaîne** qui décrit une erreur significative pour l'utilisateur.

- Situations that will return an error:
  - S'il y a **trop de problèmes** fournis à la fonction. La limite est de **cinq**, tout problème supplémentaire renverra :  `Error: Too many problems.`
  - Les opérateurs appropriés que la fonction accepte sont **l'addition** et **la soustraction**. La multiplication et la division renverront une erreur. Les autres opérateurs non mentionnés dans ce point n'ont pas besoin d'être testés. L'erreur retournée sera: `Error: Operator must be '+' or   "-"`
  - Chaque nombre (opérande) ne doit contenir que des chiffres. Sinon, la fonction renverra: `Error: Numbers must only contain digits.`
  - Chaque opérande (c'est-à-dire le nombre de chaque côté de l'opérateur) doit contenir au maximum quatre chiffres. Sinon, la chaîne d'erreur retournée sera :  `Error: Numbers cannot be more than four digits.`
- si l'utilisateur a fourni le format correct des problèmes, la conversion que vous retournerez suivra ces règles :

  - Il doit y avoir un seul espace entre l'opérateur et le plus long des deux opérandes, l'opérateur sera sur la même ligne que le second opérande, les deux opérandes seront dans le même ordre que celui fourni (le premier sera celui du haut et le second celui du bas.
  - Les nombres doivent être alignés à droite.
  - Il doit y avoir quatre espaces entre chaque problème.
  - Il doit y avoir des tirets au bas de chaque problème. Les tirets doivent s'étendre sur toute la longueur de chaque problème. (L'exemple ci-dessus montre à quoi cela doit ressembler).


### Development

Ecrivez votre code dans `arithmetic_arranger.py`.





`BONNE CHANCE`