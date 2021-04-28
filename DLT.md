## Question 1 :
Un arbre de merkle nécessite une paire de hashes pour produire un nouveau hash parent. Il faut donc a absolument que le nombre de transactions qui produiront le Merkle root soit pair.
Comment est géré le cas ou le nombre de transactions dans le Block à valider est impair pour générer un Merlke root ?

### Réponse à la question 1 : 
Dans le cas où le nombre de transactions dans le Block à valider est impair, on combine la dernière transaction avec elle-même.

## Question 2 :
Dans le réseau bitcoin, Comment un nouveau noeud arrive t'il à retrouver ses pairs et ainsi rejoindre le réseau ? Expliquer le processus avec vos propres mots.

### Réponse à la question 2 :
Le nouveau noeud arrive à retrouver ses pairs, car il vérifie que chaque noeud avant de constituer un bloc, si celui-ci n'est pas bon il est écarter du réseaux.   

## Question 3 :
Pouvez vous nommer au moins une personne qui a ou aurait pu influencer directement ou indirectement la création de Bitcoin par ses travaux (une personne qui n'a pas été nommée dans le cours)?

### Réponse à la question 3 : 
Hal Finney a lancé un système appelé RPoW, on peut le considérer comme un premier prototype et une première étape dans l'histoire des crypto-monnaies.

## Question 4 : 
Avec vos propres recherches et grâce aux compétences acquises en cours pouvez vous expliquer comment une Blockchain crée un lien entre ses différents Blocks?

### Réponse à la question 4 : 
La Blockchain crée un lien différents entre ses blocks grâce au Hash.

## Question 5 :
Quelle structure de données informatique peut représenter le mieux cette chaine de Block: https://en.wikipedia.org/wiki/List_of_data_structures ?

### Réponse à la question 5 : 


## Question 6 : 
Si je souhaite modifier une transaction de 10 bitcoin que j'ai effectué il y a 6 mois en une transaction de 1 Bitcoin, que dois je modifier dans la Blockchain et que dois je mettre en oeuvre pour que cette modification persiste ?
Est ce possible selon vous ?

### Réponse à la question 6 : 
Pour pouvoir modifier il faut l'accord de l'autre partie. 