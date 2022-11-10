# Typescript starter

## Instructions de lancement 
  - Télécharger le repo 
  - Le dézipper et ouvrir le dossier dans VSCode 
  - __FAIRE ATTENTION A AVOIR BIEN OUVERT LE DOSSIER PROJET ET NON PAS SON PARENT__
  - Exécuter `npm install` à la racine du dossier
  - Dans un terminal lancer la commande `npm start`
  - Vous pouvez coder dans le fichier `./src/index.ts` et votre code est tranpile et executer dès que vous effectuez des modifications

## Consignes du kata

### Objectif
  Tu vas mettre en place un algo qui permettra de compter les points d'une partie de bowling.

### Règles du bowling
  Une partie consiste en 10 sessions, pour chaque sessions un.e joueur.se a 2 boules à lancé pour faire tomber 10 quilles. Le score d'une session correspond au nombre de quilles tombées + le bonus d'un spare ou d'un strike.

  Un spare arrive si les 10 quilles ont été renversé au bout du 2e lancé de boule : le bonus correspond alors à la valeur du prochain lancé.
  Un strike arrive si les 10 quilles ont été renversé en 1 seul lancé de boule : le bonus correspond alors à la valeur des 2 prochains lancés.
