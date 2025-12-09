# Le processeur

Execute des calculs qui viennent des logiciels. Ces calculs sont des instructions qui viennent du programme ou de l'OS qu'on utilise.
Centre nerveux de l'ordinateur.

Fonctionne en 1 et en 0. Binair Binairee
Si tension : 1
Si pas de tension : 0

Le langage binaire = Ce que comprend le processeur.

Le Processeur a des instructions qui sont inscrites en lui, il a été PROGRAMME d'une certaine manière.

C'est pour ça que les processeur de différentes familles n'ont pas les même compatibilités.

Ils n'ont pas les même instructions logiques, en tout cas pas de la même manière.

## Emulateur 

L'emulateur est un logiciel qui traduit les instructions pour correspondre à un PC.

## Transfert du haut niveau au langage machine

Langage haut niveau : Obeit a la syntaxe classique selon langage

Langage assembleur : Execute les parties du code de haut niveau avec des instructions processeurs.

Langage binaire : Chaque binaire correspond à l'assembleur. C'est ce que le processeur comprend.

## Tâches

Execute 1 action par top d'horloge
Fréquence = nombre d'instruction par second (compté en herz).
De nos jours on est en Ghz, ce qui signifie des millions d'instruction par seconde.
On cherche à avoir des cycles régulier.

## 2004, chute de vitesse

Au départ, les processeurs avaient un seul coeur.

En 2004 on commence à avoir des processeurs de plus en plus petits et avec aussi plusieurs coeur.

Au départ les processeur avaient des fréquence super haute.

Aujourd'hui ce n'est plus autant le cas qu'avant car on s'est rendu compte que ça pouvait léser la précision de calcul du processeur.

Alors on a diminué la fréquence pour pouvoir faire plus petit.

Le défi est donc de pouvoir faire rapide sans que les calculs des coeurs s'influencent entre eux.

Alors on équilibre cette fréquence sur les plusieurs coeur.

Ainsi avec 2 coeur à 2000 de clock speed, on arrive a un total de 4000 puisqu'on a encore plus d'instruction executable.

1 coeur execute 1 instruction.

hyperThreading = Virtualiser des coeur.

Comment ? Enfait a la descence de tension d'horloge, on va executer l'instruction qu'on avais déjà.

## Choisir un processeur performant.

Reponse : CA DEPEND DES TÂCHES.

Reponse 2 : BENCHMARK sur internet.

## Mémoire cache

Mémoire qui stock les infos que le processeur utilise souvent.
Accès plus rapide que la RAM, capacités plus faible que la RAM.

## Transistor

Un peu comme un interrupteur.

Possède trois electrode (source, drain et comande)

Ce qui gère comment le courant electrique passe dans le processeur.

Composé de Silicium

Aujourd'hui on est a +50 miliards de transistor dans un processeur.

### Dans un processeur
On 'grave' des schema de transistor dans notre processeur pour créer les instructions. 

C'est pour ça qu'on ne peut pas apprendre de nouvelle chose à un processeur. C'est GRAVE littéralement dans le processeur.

C'est vraiment usiné enfait dans le processeur.


## Intel et l'hyperthreading

Virtualisation des coeurs.

# Observations

Le multicoeur rajoute une instruction par coeur, résultat : Processeur a 1 coeur vs 6 coeur va 6 fois plus vite pour le 6 coeur.
Hyperhtread : Gain de 30% grâce à la réexploitation de tâches déjà utilisée.

# Les familles

On a le 80x86. On remplace le x par un chiffre et ça fait la famille de processeur. Exemple : 80486 = Famille 486.
on a les puces ARM
IA 64
MIPS et Motorola qui sont plutôt côté serveurs
PowerPC
SPARC.

# Architecture

CISC: 80x86 et motorola 680x0
RISC: SPARC, POWER, PowerPC, MIPS, ARM
Vectoriel : Cray

CISC : Plus d'instruction, plus de consommation.
RISC : Moins d'instruction, moins de consommation.
Vectoriel : Architecture parallèle, souvent utilisé dans la recherche. On met plein de processeur en parallèle pour ça.

## Utilisation

RISC : Plus souvent pour du portable.


# Processeur graphique

Certains processeur ont un iGPU.
Ils ont moins peformant que des GPU dit 'standalone'.  Mais comme intégré dans le CPU, sont plus efficace pour des laptop.

Son problème, à l'iGPU, c'eset qu'il utilise la même mémoire vive que les autres parties du processeur.

Contrairement à un GPU qui lui aura sa propre mémoire vive pour gérer l'aspect video.

Quand on choisi un laptop, il faut donc prendre en compte, s'il a un iGPU, que ce iGPU va AUSSI utiliser de la RAM, donc il faut avoir suffisament de ram ET pour les fonctions primaire du processeur ET pour le processeur graphique intégré

# SOC

De nos jours, TOUT EST INCLUS Dans la puce du processeur. Ou presque, dépend de l'architecture... Et pour notre cas, nous parlons de SOC, SYSTEM ON A CHIP.

C'est le cas chez apple typiquement.

De nos jours, on a des design super compact et super efficient.

Ce SOC a comme avantage d'être ultra portable, de tout faire à unseul endroit, et de casi pas chauffer.

## FINAL

Comment choisir un processeur ?!

1. Utilisation
2. Budget
3. Adapter le processeur au reste des composants et périphériquese pour avoir des performances optimales.
4. Le nombre de coeur (Selon utilisation)
5. Le type de socket (compatible avec la motherboard)
6. Comparer sur benchmark
7. Regarder dans les dernière generation il peut y avoir des tarif interessant au fil de l'année (après 6 mois).
8. IDEALEMENT, C'EST CE QU'ON CHOISI EN PREMIER parce que c'eest CE QUI VA LE MOINS EVOLUER.
9. Si il faut changer le processeur, le problème c'est que ce qui tiens le processeur peut être vite endommagé.
