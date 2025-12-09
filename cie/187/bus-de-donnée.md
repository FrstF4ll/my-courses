# Le bus de donnée
Admettons qu'on ait 8 bits de donnée à envoyer enter deux machines.

## Bus en parallèle
Cette liaison va envoyer les 8 bits d'un coup dans différent canaux de données.

## Bus en série
Va envoyer des flux de bits les uns après les autres, petit à petit (1 bit par bit par exemple).

### Problème de liaison parallèle

Les liaisons parallèle peuvent s'influencer entre elle, et c'est embêtant. Car on peut avoir des données corrompues.

On a remarqué que des données allant dans le même sens pouvait plus simplement se corrompre que si on en envoyait une dans un sens, puis une autre dans l'autre sens.


A force, avec le bus en série, on s'est rendu compte qu'on pouvait faire autant que le bus en parallèle pour plus fiable.

Résultat : **Aujourd'hui on utilise que des liaison en série.** 
