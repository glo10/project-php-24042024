# *Git* simplifié pour les besoins du projet

## Je souhaite envoyer mon code depuis le local *VSCODE* vers *GitHub*

Depuis le *terminal* de *VSCODE* :

1. Ajoutez vos fichiers depuis l'interface *Git* de l'éditeur *VSCODE*
2. Ajoutez un message de *commit* (description de vos modifications autrement sur quoi avez-vous travaillé)
3. Choisissez l'option *Commit&Push*
4. Depuis *GitHub*, faire une demande *pull request* de votre *branche* vers la *branche principale main* `main <- maBranche`
6. Validez en suivant les étapes
7. Signalez aux autres afin qu'ils puissent récupérer vos changements en local sur *VSCODE* de leur côté.

### Vidéos des manipulations à télécharger et regarder

- [1. Vidéo d'envoi des fichiers vers GitHub depuis ma branche](./videos/manipulation_vscode.mp4)
- [2. Vidéo de la fusion de mes travaux dans la branche principale depuis GitHub](./videos/manipulation_sur_github.mp4)
---

## On m'a fait signe de récupérer en local les mises à jour d'un autre collaborateur (collègue) après que ce dernier ait fusionné son travail sur la *branche principale main*

Depuis le *terminal* de *VSCODE* sur ma branche :
1. Exécutez la commande `git merge origin/main`, c'est tout

### Vidéo de la manipulation à faire

- [Vidéo pour récupérer en local les mises à jour](./videos/de_github_vers_ma_branche.mp4)


PS : **en cas de conflit (git va vous le dire dans le terminal)** cad modifications du même fichier par votre collègue sur sa branche et modification de ce fichier par vous en local, **APPELEZ-MOI pour le résoudre**