# Répartition du matin (pré-répartition de 9 h)

> **À vérifier** : reconstituée d'après une vidéo d'explication du 2 septembre 2026 (partie 1). Recoupée le 23/11/2026 avec l'aide en ligne et les manuels de Socleo et la carte de Zandoly (tableau « Recoupement » en bas). Non encore testée sur le vrai outil. Aucune capture dans cette version.
> Dernière vérification : aucune.

## Objectif
Avant l'ouverture de la journée, vérifier que ce qui a été commandé dans Socleo existe vraiment dans les stocks et les offres Zandoly, attribuer chaque ligne à un producteur, repérer les erreurs et prévenir les clients touchés par un manque.

## Qui la fait, quand
- Qui : la personne chargée de la répartition. Validation : à confirmer.
- Quand : vers 9 h chaque jour de vente. Une répartition finale a lieu vers 17 h (voir « Après »).
- Pourquoi 9 h : repérer les erreurs de saisie des disponibilités, prévenir tôt les clients d'un manque, et permettre l'envoi de précommandes aux producteurs.

## Pré-requis
- Deux écrans au minimum.
- Un accès à Socleo et à Zandoly (la personne se connecte elle-même).
- Dans le navigateur, ouvrir :
  1. Socleo : panneau des commandes (pour modifier) ;
  2. Socleo : un second panneau des commandes (pour regarder les statistiques) ;
  3. Socleo : panneau des produits ;
  4. Zandoly : consultation des offres ;
  5. Zandoly : rapport de répartition.

## Étapes
1. **Choisir le jour.** Dans Socleo, panneau des commandes, se placer sur la **date de livraison client** voulue, en vue **produit**.
2. **Écarter les clients déjà traités.** Retirer du filtre un client dont les commandes ont déjà été envoyées. Attention : s'il commande aussi des produits frais non encore envoyés (par exemple des salades), les traiter à part.
3. **Commencer par les sorties de stock.** Pour chaque produit tenu en stock : attribuer **le lot le plus ancien d'abord**.
   - Le numéro de lot commence par une lettre = le mois (A = janvier … H = août, I = septembre), suivie du jour. (L'aide de Socleo décrit un numéro généré automatiquement au format jour-mois : la lettre serait donc une convention maison, à vérifier.)
   - Quand un lot ancien est épuisé, passer au suivant.
   - Une entrée de stock qui n'arrive que plus tard (jour de livraison) ne s'attribue pas en sortie de stock : elle passe **en transit**.
   - Pour gagner du temps : sélectionner plusieurs lignes, puis « modifier le mode de livraison ». (Dans l'aide de Socleo, l'action en lot qui correspond s'appelle « Modifier le suivi logistique » : nom exact à vérifier.)
4. **Produit sans numéro de lot.** Dans le panneau des stocks, sélectionner le produit, « activer le stock par lot », puis actualiser la page. Un produit terminé est retiré du module de stock (pour garder une liste lisible) ; il faut le **réactiver en début de saison**. L'aide de Socleo ajoute que les produits à stock nul et sans mouvement sont aussi **retirés automatiquement le 1er de chaque mois** (alerte cinq jours avant) ; pour l'éviter, mettre à jour l'inventaire.
5. **Consulter Zandoly.** Consultation des offres, à la date voulue, pour le débouché concerné : la liste est triée par produit. Elle dit qui a proposé quoi.
   - Un seul producteur a proposé : attribuer directement.
   - Plusieurs producteurs : ouvrir le rapport de répartition (qui est planifié, en mode mois).
6. **Répartir au prorata de la planification.** Regarder les **ventes dans Socleo**, pas dans la colonne « ventes » de Zandoly (sa mise à jour est rare, le plus souvent le dimanche ; lors du relevé du 14/11 elle était à zéro). Dans Socleo, filtrer sur le **type de produit** (pas sur le produit seul, sinon les variétés manquent), tous débouchés, tous types de transport. Si les ventes sont proches de la planification, attribuer ; sinon, attendre 17 h (voir « Après »). Calcul : ventes ÷ planification totale, puis × planification de chaque producteur.
7. **Produit pas encore réparti.** Le laisser au « compte de régulation » : aucun producteur ne le voit à tort comme vendu.
8. **Aléa (le produit n'existe pas en quantité suffisante).** Mettre la quantité à 0 et le motif « aléa », avec le produit au compte de régulation. Ne jamais indiquer au client quel producteur a manqué (la fiche producteur permet de masquer le nom du fournisseur sur les documents). Dans Socleo, la quantité livrée et la quantité commandée d'une ligne sont deux champs distincts : mettre la première à 0 garde la seconde. Un champ « motif » n'est pas documenté : à vérifier.
9. **Commande passée en avance** (le client a commandé avant la mise à jour des disponibilités) : même geste, motif « commandé en avance ».
10. **Client sous appel d'offres** : si une de ses lignes est annulée, **prévenir le responsable commercial**, qui prévient le client. Pour les autres clients, ce n'est pas nécessaire.
11. **Arbitrer entre clients** quand il manque de la marchandise : priorité aux clients conventionnés ; répartir les annulations pour ne pas toujours pénaliser le même client ; il est préférable de refuser entièrement un client plutôt que de lui livrer une fraction infime de sa commande.
12. **Changer de producteur sur une ligne** : sélectionner la ligne → « modifier le fournisseur ». Pour que les commandes suivantes suivent, le désigner « fournisseur principal » dans le panneau des produits.
13. **Prévenir les clients touchés.** Faire d'abord toute la liste, puis envoyer les messages d'un coup. Dans Socleo, mode client, bouton courriel : un modèle d'aléa et un modèle « mise à jour suite à la mercuriale » existent. Un client sous le franco à cause de notre manque garde la livraison gratuite. Socleo ne conserve pas les courriels envoyés : se mettre en copie pour garder une trace.
14. **Précommande aux producteurs** vers midi, pour ceux dont les commandes ne bougeront plus (ex. restauration collective).

## Erreurs fréquentes
- Faute de frappe sur une disponibilité (un « 28 » saisi « 8 »). La pré-répartition de 9 h sert à la repérer.
- Entrée de stock saisie sur le mauvais calibre : sélectionner la ligne → « changer la référence produit », puis choisir ce qu'il faut recalculer (poids, montants, désignation, tarifs).
- Se fier à la colonne « ventes » de Zandoly.
- Cliquer sur un seul produit au lieu du type de produit dans le filtre.
- Oublier de remettre un client écarté à l'étape 2.
- Produit sans « point d'interrogation » : le stock par lot n'a pas été réactivé (étape 4).

## Après
- Vers 17 h : répartition finale pour les produits restés au compte de régulation (voir procédure « Répartition du soir », à écrire).
- Avant la facturation : supprimer les lignes annulées une fois les clients prévenus. Le mode « commande invalide » permet de revoir les lignes supprimées.

## Points à confirmer avec les personnes qui connaissent l'outil
- Noms exacts des boutons et onglets.
- Qui valide la procédure.
- Règle exacte pour les clients conventionnés et sous appel d'offres.

## Recoupement avec la documentation (23/11/2026)
Légende : **Confirmé** = la documentation décrit la même chose ; **À corriger** = elle dit autre chose ; **Non établi** = aucune source. Une étape recoupée avec la documentation reste « à vérifier » tant qu'elle n'a pas été essayée sur le vrai outil.

| Étape | Source | Verdict |
|---|---|---|
| 1. Jour, date de livraison client, vue produit | Aide Socleo, Commandes (type de date, vues client / fournisseur / produit) | Confirmé |
| 2. Écarter des clients du filtre | Filtres de Commandes (groupe de clients, état de notification) | Plausible ; geste exact non documenté |
| 3. Lot le plus ancien d'abord | Aide Socleo, Stock et Commandes : rapprochement des lots dans l'ordre chronologique, « Détailler le lot », une référence à la fois | Confirmé |
| 3. Lettre du mois dans le numéro de lot | Aide Socleo : numéros générés au format jour-mois | À vérifier (convention maison ?) |
| 3. Transit contre sortie de stock | Aide Socleo : quatre circuits (direct, transit, réception en stock, expédition de stock) ; affichage Stock / Stock + Transit / Transit | Confirmé |
| 3. « Modifier le mode de livraison » | Aide et carte Socleo : action en lot « Modifier le suivi logistique » | À corriger probablement (nom) |
| 4. Activer le stock par lot | Aide Socleo, Produits et Stock : activer la gestion du stock, type par produit ou par lot | Confirmé |
| 4. Produit terminé retiré, à réactiver | Aide Socleo, Stock : retrait manuel, et retrait automatique le 1er du mois | Confirmé et complété |
| 5. Consultation des offres dans Zandoly | Carte Zandoly (rapport par date, filtres famille, produit, ferme, débouché) | Confirmé |
| 5. Rapport de répartition « en mode mois » | Carte Zandoly : compare planifié / offert / vendu par période et débouché ; le rapport de planification se lit par mois ou par semaine | Partiel ; modes à vérifier |
| 6. Ventes lues dans Socleo, pas dans Zandoly | Carte Zandoly : colonne « Ventes » à zéro lors du relevé | Confirmé |
| 6. Filtre sur le « type de produit » | Aide Socleo : le type de produit existe sur la fiche (classification) ; filtre de Commandes non listé | Non vérifié |
| 6. Calcul au prorata | Aucune source | Règle de gestion, à faire valider par le bureau |
| 7. Compte de régulation | Carte Socleo : le compte existe ; le manuel ne prévoit que trois comptes techniques (réception, inventaire, pertes) | Existence confirmée ; rôle connu par la vidéo seule |
| 8-9. Aléa, commandé en avance | Aide Socleo : quantité livrée et quantité commandée distinctes ; pas de champ « motif » documenté | Non établi (motif) |
| 10. Client sous appel d'offres | Aide Socleo : module Offres (marchés publics) ; absent du menu consulté | Plausible ; module non confirmé |
| 11. Arbitrage entre clients | Aucune source | Règle de gestion |
| 12. Changer de fournisseur ; fournisseur principal | Aide Socleo : changement de fournisseur (Commandes) ; producteur principal (fiche produit) | Confirmé |
| 13. Messages aux clients, modèles | Aide Socleo : modèles d'e-mails, messages en lot (Membres) | Confirmé ; modèles « aléa » non vus |
| 14. Précommande aux producteurs | Aide Socleo : bon de commande fournisseur généré à l'envoi | Confirmé |
| Après : lignes annulées, mode « commande invalide » | Aide Socleo : états invalides (brouillon, rétractée, annulée) ; commande facturée = clôturée, non modifiable | Confirmé ; supprimer avant la facturation |
