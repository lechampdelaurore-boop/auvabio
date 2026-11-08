# AGENTS.md — règles de travail du projet AUVABIO

Ce fichier est lu au début de chaque conversation. Les instructions du projet (dans Claude) en donnent l'essentiel ; ce fichier donne le détail.

## Reprise obligatoire
1. Lire ce fichier.
2. Lire « Où on en est » en tête de docs/ETAT_DU_PROJET.md.
3. Lire la ligne de la tâche dans docs/ROADMAP.md, dont la colonne « Modèle · effort » ; vérifier que la session actuelle la respecte, sinon s'arrêter et le dire.
4. Dire à François en deux lignes : l'étape, le point ouvert, le réglage recommandé.

## Registres
- docs/ETAT_DU_PROJET.md : où on en est, journal court.
- docs/ROADMAP.md : tableau des étapes (section 1), ordre (section 2), détail par étape.
- docs/DECISIONS.md : une décision par entrée, numérotée D-001…, avec date, raison, qui a tranché.
- CHANGELOG.md : ce qui a changé et quand.
- docs/procedures/ : procédures métier avec captures. docs/fiches/ : fiches visuelles à afficher.
- docs/outils/zandoly.md et docs/outils/socleo.md : cartes de chaque outil (écrans, boutons, à quoi ils servent).
Toute modification de l'état du projet met les registres à jour dans la même PR (ou le même commit tant que le dépôt n'existe pas).

## Sécurité (absolue)
- Jamais de mot de passe, clé, jeton, code ou e-mail vu, saisi ou écrit par Claude.
- Zandoly, Socleo, OTF : lecture seule. Toute écriture exige la validation humaine écrite, action par action.
- Pas de donnée de client, de prix ou d'adhérent dans un dépôt public ni dans une capture non floutée.
- API OTF : 4 requêtes par seconde au plus, un jeton par ferme, lecture seule sans accord écrit d'OTF.

## Code (volet C)
Un chantier à la fois ; une PR par point ouvert ; lint, typage, tests, build avant PR ; sorties collées ; fusion une à une après déploiement vérifié ; surveillance au plus toutes les 5 minutes.

## Style
Français, vouvoiement de François, phrases simples, l'essentiel d'abord, une question par message numérotée.
