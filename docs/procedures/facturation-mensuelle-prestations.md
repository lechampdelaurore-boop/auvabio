# Facturation mensuelle : prestations de service aux producteurs

> **À vérifier** : reconstituée d'après l'enregistrement d'une démonstration par le fournisseur de Socleo (septembre 2025), sur un site de démonstration. Le sujet juridique associé doit être validé par le bureau et l'expert-comptable avant toute décision : voir les notes privées.
> Aucune capture dans cette version. Dernière vérification : aucune.

## Objectif
Facturer chaque mois la prestation de service de l'association aux producteurs (en remplacement d'une commission), tout en gardant une facture client unique, en passant par le mode « achat-revente » de Socleo.

## Qui la fait, quand
- Qui : la personne chargée de la facturation. Validation : à confirmer.
- Quand : en fin de mois, après les ventes du mois et l'inventaire du stock.
- Durée annoncée : environ une heure par mois, plus une vingtaine de minutes pour saisir à la main les versements (environ 26 producteurs).

## Principe
Dans ce mode, l'association « achète » les produits aux producteurs au même prix qu'elle les « vend » aux clients. Elle facture ensuite au producteur une prestation de service à 20 % de TVA, qui vient en déduction de ce qu'elle lui doit. Dans le vocabulaire de l'association : « prestation » quand c'est à 20 %, « commission » quand le taux suit celui du produit.

## Pré-requis
- Un produit « prestation de service » créé dans Socleo, avec la catégorie technique « prestations » (à faire une fois).
- Ventes du mois closes, inventaire fait.

## Étapes
1. **Ajouter les prestations.** Dans la liste des ventes du mois, sélectionner les lignes, « ajouter une prestation » : fournisseur concerné, date (le dernier jour du mois), produit « prestation ». Les montants sont ceux calculés sur le montant client (montant fixe ou en pourcentage : à confirmer). Ignorer ce qui concerne le compte de régulation de l'association.
2. **Générer les factures producteurs de prestation** : la facturation classique produit les factures de prestation envers les producteurs.
3. **Générer les factures fournisseurs** du mois : **sans commission** (le prix fournisseur n'est pas utilisé, on s'appuie sur le prix de vente).
4. **Côté comptabilité** : vérifier les factures fournisseurs (montant sans commission) et les factures clients avec leurs versements.
5. **Saisir les versements côté fournisseur** (étape manuelle fastidieuse) : pour chaque producteur, saisir en versement le montant de la prestation, afin que sa facture fournisseur soit réglée partiellement. Marquer ces prestations réglées « avec un autre mode ».
6. **Générer le règlement par virement** : sélectionner toutes les factures, demander la génération du règlement ; filtrer sur le virement pour retrouver ce qui reste à payer ; produire le fichier de virement au format SEPA comme d'habitude.

## Erreurs fréquentes
- Générer les factures fournisseurs avec la commission.
- Oublier de saisir un versement : le producteur est alors payé en trop.
- Mauvaise date (le dernier jour du mois, pas le premier du suivant).

## Points ouverts
- Valider avec le bureau et l'expert-comptable que ce mode de facturation est conforme (à ne pas décider seul).
- Confirmer le mode de calcul de la prestation et le taux de TVA.
- Préparer l'arrivée de la facturation électronique obligatoire.
