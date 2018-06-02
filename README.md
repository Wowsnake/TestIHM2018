# <img src="https://raw.githubusercontent.com/IUTInfoAix-M2105/Syllabus/master/assets/logo.png" alt="class logo" class="logo"/> Module 2105 : Introduction aux IHM en Java 

## Test d'IHM et langage Java [![Build Status](https://travis-ci.com/IUTInfoAix-M2105/TestIHM2018.svg?token=zPXgu159amQhEb4ShTxW&branch=master)](https://travis-ci.com/IUTInfoAix-M2105/TestIHM2018)

**Test du samedi 9 juin 2018 – Durée 2 heures – Documents autorisés**

L'objet de ce test est l'écriture en Java de l'IHM d'une version simplifiée du jeu Neutreeko. C'est un jeu de société combinatoire abstrait, qui oppose deux joueurs. Inventé en 2001 par le mathématicien norvégien Jan Kristian Haugland qui se joue sur un plateau en 5×5. Les règles de bases sont simples : le but est d’aligner ses trois pions. Ces derniers se déplacent dans tous les sens **d’un maximum de cases possibles**. Soit ils sont stoppés par le bord du plateau soit par un autre pion.

## Mise en place et but du jeu
On place les 2 fois 3 pièces comme indiqué par les ronds noirs et blancs. Le but du jeu est d'aligner ses trois pièces en continu (il ne doit pas y avoir d'espace entre les pièces), verticalement, horizontalement ou diagonalement.

## Déroulement
Les joueurs déplacent alternativement une de leurs pièces. Le joueur déplace une de ses pièces dans la direction de son choix, orthogonale ou diagonale, aussi loin qu'il est possible : la pièce s'arrête si elle rencontre une autre pièce ou le bord du tablier(plateau de jeu). Il n'y a ni prise ni saut dans ce jeu. Les joueurs jouent à tour de rôle de la même manière jusqu'à la fin de la partie.

[V]: https://github.com/IUTInfoAix-M2105/TestIHM2014/raw/master/vide.png
[B]: https://github.com/IUTInfoAix-M2105/TestIHM2014/raw/master/blanc.png
[N]: https://github.com/IUTInfoAix-M2105/TestIHM2014/raw/master/noir.png
[G]: https://github.com/IUTInfoAix-M2105/TestIHM2014/raw/master/noir_transparent.png
[H]: https://github.com/IUTInfoAix-M2105/TestIHM2014/raw/master/blanc_transparent.png

|     | A    | B    | C    | D    | E    | 
| --- | ---- | ---- | ---- | ---- | ---- | 
|**5**|![][V]|![][B]|![][V]|![][B]|![][V]|
|**4**|![][V]|![][V]|![][N]|![][V]|![][V]|
|**3**|![][V]|![][V]|![][V]|![][V]|![][V]|
|**2**|![][V]|![][V]|![][B]|![][V]|![][V]|
|**1**|![][V]|![][N]|![][V]|![][N]|![][V]|

