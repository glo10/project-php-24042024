# Git simplifié

## Je souhaite envoyé mon code depuis le local vers GitHub

Depuis le terminal de VSCODE :

1. Ajoutez vos fichiers depuis l'interface Git de l'éditeur VSCODE
2. Ajoutez un message de commit (description de vos modifs)
3. Choisissez l'option Commit&Push
4. Envoyez
5. Depuis GitHub, faire une demande pull request de votre branche vers la branche principale main main <- maBranche
6. Validez
7. Faites signe aux autres pour qu'ils puissent faire les manip pour récupérer vos changements en local chez eux

---

## On m'a fait signe de récupérer en local les mises à jour d'un autre collaborateur (collegue)

Depuis le terminal de VSCODE:
1. Exécutez la commande `git merge origin/main`, c'est tout

PS : **en cas de conflit (git va vous le dire dans le terminal)** cad modifications du même fichier par votre collegue sur sa branche et modification de ce fichier par vous en local, **APPELEZ-MOI pour le résoudre**