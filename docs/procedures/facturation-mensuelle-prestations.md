# Facturation mensuelle : prestations de service aux producteurs

> **À vérifier** : reconstituée d'après l'enregistrement d'une démonstration par le fournisseur de Socleo (septembre 2025), sur un site de démonstration. Le sujet juridique associé doit être validé par le bureau et l'expert-comptable avant toute décision : voir les notes privées.
> Recoupée le 23/11/2026 avec l'aide en ligne et les manuels de Socleo et la carte de Zandoly (tableau « Recoupement » en bas). Le mécanisme décrit existe dans la documentation ; le choix de ce mode de facturation reste à faire valider.
> Aucune capture dans cette version. Dernière vérification : aucune.

## Objectif
Facturer chaque mois la prestation de service de l'association aux producteurs (en remplacement d'une commission), tout en gardant une facture client unique, en passant par le mode « achat-revente » de Socleo.

## Qui la fait, quand
- Qui : la personne chargée de la facturation. Validation : à confirmer.
- Quand : en fin de mois, après les ventes du mois et l'inventaire du stock.
- Durée annoncée : environ une heure par mois, plus une vingtaine de minutes pour saisir à la main les versements (un versement par producteur).

## Principe
Dans ce mode, l'association « achète » les produits aux producteurs au même prix qu'elle les « vend » aux clients. Elle facture ensuite au producteur une prestation de service à 20 % de TVA, qui vient en déduction de ce qu'elle lui doit. Dans le vocabulaire de l'association : « prestation » quand c'est à 20 %, « commission » quand le taux suit celui du produit.

## Pré-requis
- Un produit « prestation de service » créé dans Socleo, avec la catégorie technique « prestations » (à faire une fois).
- Ventes du mois closes, inventaire fait.

## Étapes
1. **Ajouter les prestations.** Dans la liste des ventes du mois, sélectionner les lignes, « ajouter une prestation » : fournisseur concerné, date (le dernier jour du mois), produit « prestation ». Les montants sont ceux calculés sur le montant client (montant au prix du produit ou en pourcentage des commandes : confirmé par l'aide de Socleo). Ignorer ce qui concerne le compte de régulation de l'association.
2. **Générer les factures producteurs de prestation** : la facturation classique produit les factures de prestation envers les producteurs.
3. **Générer les factures fournisseurs** du mois : **sans commission** (le prix fournisseur n'est pas utilisé, on s'appuie sur le prix de vente).
4. **Côté comptabilité** : vérifier les factures fournisseurs (montant sans commission) et les factures clients avec leurs versements.
5. **Saisir les versements côté fournisseur** (étape manuelle fastidieuse) : pour chaque producteur, saisir en versement le montant de la prestation, afin que sa facture fournisseur soit réglée partiellement. Marquer ces prestations réglées « avec un autre mode ».
6. **Générer le règlement par virement** : sélectionner toutes les factures, demander la génération du règlement ; filtrer sur le virement pour retrouver ce qui reste à payer ; produire le fichier de virement au format SEPA comme d'habitude.

## Erreurs fréquentes
- Générer les factures fournisseurs avec la commission.
- Oublier de saisir un versement : le producteur est alors payé en trop.
- Mauvaise date (le dernier jour du mois, pas le premier du suivant). Une facture ne peut pas être datée avant la facture précédente (aide Socleo).

## Points ouverts
- Valider avec le bureau et l'expert-comptable que ce mode de facturation est conforme (à ne pas décider seul).
- Confirmer le taux de TVA de la prestation (20 % d'après l'aide de Socleo pour la facturation pour compte).
- Facturation électronique : d'après l'aide de Socleo, la réception est obligatoire depuis le 01/09/2026 et l'émission le 01/09/2027 pour les PME et micro-entreprises (à confirmer pour l'association avec l'expert-comptable) ; Socleo la propose avec la plateforme agréée SUPER PDP, pour les ventes aux professionnels.
- **Attention (aide Socleo)** : la facturation « pour le compte des producteurs » est un choix de départ ; elle est incompatible avec Chorus Pro et avec les exports comptables. Avant de changer de mode, demander au support de Socleo ce que le changement implique pour les factures déjà émises et l'export comptable.
- Le mode « achat-revente » décrit dans l'aide concerne la gestion du stock (facture fournisseur à la réception) : son effet sur la facturation est à faire confirmer par le support.

## Recoupement avec la documentation (23/11/2026)
Légende : **Confirmé** = la documentation décrit la même chose ; **À corriger** = elle dit autre chose ; **Non établi** = aucune source. Une étape recoupée avec la documentation reste « à vérifier » tant qu'elle n'a pas été essayée sur le vrai outil.

| Étape | Source | Verdict |
|---|---|---|
| Produit « prestation », catégorie technique | Aide Socleo, Livraisons et Commandes : produit de catégorie technique « Prestation », montant positif ou négatif | Confirmé |
| 1. Ajouter une prestation sur des commandes | Aide Socleo, Commandes : ajout de produit ou de prestation ; montant au prix du produit ou en pourcentage des commandes client ou fournisseur ; affichée en pied de facture | Confirmé |
| Prestation à 20 % de TVA, justificatif | Aide Socleo, Comptabilité : facturation pour compte = justificatif avec prestation à 20 % | Confirmé (principe) |
| 2-3. Factures fournisseurs sans commission | Aide Socleo, Comptabilité : en propre = facture avec commission ; pour compte = justificatif avec prestation | Cohérent |
| 5. Versements « avec un autre mode » | Aide Socleo : versement « Autre mode de versement » déduit du virement à la ferme (cas de l'adhésion), pointage facture client / facture fournisseur | Confirmé (même mécanisme) |
| 6. Règlement par virement, fichier SEPA | Aide Socleo, Comptabilité : virements SEPA fournisseurs, fichier ISO 20022 | Confirmé |
| Date de la facture | Aide Socleo : la facture suivante ne peut pas être antérieure à la précédente | Confirmé |
| Conformité juridique du mode | Aucune source ne tranche ; l'aide décrit plusieurs modes (en propre, pour compte) | À faire trancher par le bureau et l'expert-comptable |
| Durée (environ une heure par mois) | Annonce du vendeur dans la vidéo | Non établi |
