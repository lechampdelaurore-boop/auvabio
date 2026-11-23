# Inventaire hebdomadaire du stock

> **À vérifier** : reconstituée d'après une vidéo d'explication du 6 octobre 2026. Recoupée le 23/11/2026 avec l'aide en ligne et les manuels de Socleo et la carte de Zandoly (tableau « Recoupement » en bas). Non testée sur le vrai outil. Aucune capture dans cette version.
> Dernière vérification : aucune.

## Objectif
Faire correspondre le stock tenu dans Socleo (numéros de lots compris) avec le stock réellement présent dans les chambres et l'entrepôt, retrouver l'origine des écarts, et éviter de payer ou de facturer à tort.

## Qui la fait, quand
- Comptage physique : le préparateur de commandes, qui note les quantités et les lots dans un cahier.
- Saisie et rapprochement dans Socleo : la personne chargée du stock. Validation : à confirmer.
- Quand : le mardi, après le retour de la tournée du préparateur (entre 10 h et 13 h 30 selon le jour). En saison, pour gagner du temps : la chambre froide une semaine sur deux, en alternance avec la chambre chaude et l'entrepôt ; inventaire complet exceptionnel s'il n'y en a pas eu depuis trois semaines.
- Durée : de un quart d'heure (inventaire régulier) à plusieurs heures (inventaire complet).

## Règle importante
**Ne pas facturer les clients avant l'inventaire.** Une fois une commande facturée, les lots qui lui sont attachés sont verrouillés : on ne peut plus corriger une inversion de lots, ni retrouver un produit sorti à tort. Une facturation faite trop tôt (par exemple pour la trésorerie) est la cause de la plupart des écarts irréparables. Une proposition à étudier pour le futur outil : bloquer la facturation tant que le stock n'est pas validé.

## Pré-requis
- Le cahier d'inventaire du préparateur, et le cahier des entrées en stock (posé sur le bureau).
- Socleo, module de stock, qui comporte **deux pages** :
  1. **Approvisionnement** : stock à une date (on ne peut pas choisir la date du jour, choisir le lendemain) ;
  2. **État de stock** : détail par lot et par producteur, à la date du jour.
- Un surligneur (deux couleurs).

## Étapes
1. **Contrôler les entrées en stock depuis le dernier inventaire**, page par page du cahier d'entrées : le producteur a-t-il livré ce qui était prévu ? Sinon, corriger l'entrée dans Socleo (une entrée non facturée peut être « déclôturée » puis modifiée : fonction non retrouvée dans l'aide, à vérifier). Surligner en jaune ce qui est vérifié. Sans cette étape, on se retrouve avec de fausses erreurs.
2. **Passer le cahier d'inventaire ligne par ligne** : pour chaque ligne (producteur, produit, lot, nombre de caisses), comparer avec Socleo. Penser au colisage : l'affichage peut être en unités ou en colis.
3. **Si le nombre est bon et que c'est le bon lot** : surligner en jaune.
4. **Si le nombre est bon mais que le lot est différent** (lots inversés) :
   - si la commande est déjà facturée : rien à faire dans l'outil, prévenir le préparateur ;
   - sinon : refaire une entrée de stock sur le bon lot et une sortie sur l'autre, sans facturation.
   Dans les deux cas, regarder si le rangement permet aux préparateurs d'identifier les lots les plus anciens (étiquettes avec le numéro de lot, anciens devant).
5. **Si le nombre est différent : mener l'enquête.**
   1. Recompter (souvent une pile sur le côté a été oubliée).
   2. Demander au préparateur : a-t-il sorti des colis abîmés en préparant ? Y a-t-il une palette « à récupérer par les producteurs » ?
   3. Relire les commandes (filtre « commande invalide ») : une commande annulée dont la sortie de stock est restée valide ?
   4. Demander au producteur : a-t-il livré moins que prévu sans le noter ?
6. **Écart non expliqué.** Créer une commande au « compte de régulation » de l'association, à la date du jour, avec le produit et la quantité manquante, motif « disparu ». Cela empêche de vendre à un client ce qui n'existe plus. L'aide de Socleo prévoit aussi « Saisir une perte » (compte technique des pertes, au tarif fournisseur, non facturable) : le recours au compte de régulation est une pratique maison, à confirmer. On a ensuite jusqu'à la facturation (vers le 15 du mois) pour élucider ; après, la perte est payée par l'association. L'ordre de grandeur : quelques caisses, chiffrées au tarif fournisseur.
7. **Produit en trop** (« apparition ») : faire une entrée de stock du jour avec le bon lot.
8. **Produit non conforme à la fiche d'agréage** : le sortir du stock (sortie de stock, ou inventaire à zéro). Si le produit n'a pas été commandé par l'association mais apporté de sa propre initiative par le producteur, c'est la charge du producteur. En cas d'erreur « ne peut pas honorer les expéditions déjà rapprochées » : passer d'abord les commandes concernées en transit, actualiser, puis saisir l'inventaire.
9. **Saisie dans le module d'inventaire** : choisir le producteur et le lot, saisir en unités ou en colis (plus ou moins), enregistrer. Selon l'aide de Socleo : Stock > État de stock, cocher les produits, « Saisir un inventaire » ; **dater l'inventaire de la veille si on le fait le matin** ; on ne peut pas saisir un inventaire antérieur à un inventaire existant ; l'inventaire corrige des écarts, il ne déclare jamais d'entrées (voir l'étape 7).
10. **Produit apporté par un producteur sans commande** : surligner d'une autre couleur ; on ne le gère pas (stock de courte durée).
11. **Enfin** : informer le préparateur des lots inversés ou mal rangés, et noter les produits à recommander.

## Erreurs fréquentes
- Facturer avant l'inventaire (lots verrouillés).
- Entrées en stock non mises à jour (le producteur a livré 8 au lieu de 7).
- Comptage incomplet.
- Annulation d'une commande sans annulation de sa sortie de stock.
- Choisir une date du jour dans l'écran « Approvisionnement » (refusé).
- Inventaire par fichier : tout lot absent du fichier est clôturé à stock nul (aide Socleo).
- Produit à stock nul sans mouvement : retiré automatiquement le 1er du mois (aide Socleo) ; mettre à jour l'inventaire pour l'éviter.

## Points ouverts
- Qui a la responsabilité des sorties de stock ? Elle figurait dans la fiche de poste de la personne chargée du stock, pas dans celle du préparateur.
- Version mobile pour saisir sur place : n'existe pas aujourd'hui.
- Confirmer la date de facturation du mois et la règle « pas de facturation avant l'inventaire ».

## Recoupement avec la documentation (23/11/2026)
Légende : **Confirmé** = la documentation décrit la même chose ; **À corriger** = elle dit autre chose ; **Non établi** = aucune source. Une étape recoupée avec la documentation reste « à vérifier » tant qu'elle n'a pas été essayée sur le vrai outil.

| Étape | Source | Verdict |
|---|---|---|
| Règle « ne pas facturer avant l'inventaire », lots verrouillés | Aide Socleo : une commande facturée est clôturée, non modifiable ; l'inventaire fige la répartition des expéditions non rapprochées | Confirmé |
| Deux pages : Approvisionnement et État de stock | Aide et carte Socleo, Stock | Confirmé |
| Approvisionnement : date du jour refusée, choisir le lendemain | Aide Socleo : niveau à une date (par défaut dans 30 jours) ; refus de la date du jour non décrit | Non vérifié |
| Zones CC, CF, EP | Carte Socleo, État de stock | Confirmé |
| 1. « Déclôturer » une entrée non facturée | Aucune source retrouvée | Non établi |
| 2. Affichage en unités ou en colis | Aide Socleo, Stock : unités, colis (« 10 c + 3 u »), poids | Confirmé |
| 4. Lots inversés : rien si facturé ; sinon entrée et sortie | Aide Socleo : rapprochement des lots ; commande facturée non modifiable ; inventaire par lot | Principe confirmé ; gestes à vérifier |
| 5. Enquête, filtre « commande invalide » | Aide Socleo, Commandes : états invalides (brouillon, rétractée, annulée) | Confirmé |
| 6. Écart non expliqué : commande au compte de régulation | Aide Socleo : « Saisir une perte » existe ; le compte de régulation n'est pas décrit | Pratique maison ; fonction native à étudier |
| 7. Produit en trop : entrée de stock du jour | Aide Socleo : l'inventaire ne déclare jamais d'entrées, utiliser « Nouvelle entrée en stock » | Confirmé |
| 8. Produit non conforme | Aide Socleo : module Demandes (non-conformité réception ou inventaire), présent dans le menu | Possibilité à étudier |
| 8. Erreur « ne peut pas honorer les expéditions déjà rapprochées » | Aide Socleo : l'inventaire fige la répartition des expéditions non rapprochées | Cohérent ; message non retrouvé |
| 9. Saisie de l'inventaire | Aide Socleo : date de la veille si le matin ; unités, colis ou poids ; produit par lot | Confirmé et complété |
