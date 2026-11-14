# Carte de Zandoly

Statut : **à vérifier** (relevé du 14/11/2026, lecture seule, avec un compte de ferme ; rien n'a été saisi ni testé). Aucune donnée réelle dans ce fichier : le détail avec données est conservé hors dépôt.

## À quoi sert Zandoly
Bourse d'offres et planification commune de l'association :
- chaque ferme annonce sa production prévue (**Planification**) ;
- chaque semaine, chaque ferme propose ce qu'elle peut livrer (**Offre** : produit, prix, quantité, unité) ;
- les rapports regroupent les offres en **mercuriale** par date de livraison ; c'est elle qui est recopiée dans Socleo (3 fois par semaine).

## Menus (espace « Auvabio »)
| Entrée | Ce que c'est |
|---|---|
| Saisir une offre | Formulaire de nouvelle offre (non ouvert lors du relevé). |
| Consultation des offres | Rapport des offres par date de livraison ; filtres famille, produit, ferme, débouché ; commentaire libre affiché en tête. |
| Mercuriale | Même contenu avec les prix, total en euros ; sortie la plus proche de la recopie vers Socleo. |
| Rapport planification | Quantités prévues par ferme et produit, par mois ou par semaine (rapport lent, jusqu'à ~10 s). |
| Rapport répartition | Compare planifié / offert / vendu par ferme et produit, avec un total par produit et un pourcentage ventes / planification. |
| Données fermes > Liste des offres | Liste avec statut, date de livraison, calendrier. |
| Données fermes > Planification | Une fiche par campagne + ferme + produit + débouché. |
| Stocks longue conservation | Liste de stocks (vide pour le compte de ferme utilisé). |
| Référentiels > Produits | Environ 960 fiches produit. |
| Paramètres > Produits planifiables | Environ 210 produits planifiables, avec statut Activé/Désactivé, famille, durée. |
| Paramètres > Utilisateurs | Comptes (non consulté : contient des adresses). |

## Écrans
- **Offre** : identifiant `AAAAMMJJ-FERME`, statut Brouillon ou Soumis, débouché (Magasin, Restauration collective, Transformation, Maraîchers), producteur, tableau de lignes (produit, prix, quantité, unité, total), bouton « Dupliquer cette offre », commentaires. Une offre **soumise n'est plus modifiable** ; le journal montre qu'un administrateur la valide et peut corriger un prix (à confirmer).
- **Planification** : campagne, ferme, produit planifiable, débouché, quantité totale, unité (K = kilo, U = unité), prix moyen, quantités de mai à avril ; journal des modifications.

## Ce qui n'apparaît pas
Facturation, tournées, clients (c'est Socleo). Origine des « ventes » du rapport répartition : inconnue. Export fichier ou API : inconnus.

## Tâches probables liées à Zandoly (pour l'étape 1)
1. Tenir le référentiel (produits, produits planifiables) et ouvrir la campagne.
2. Relancer les fermes qui n'ont pas saisi ou soumis leur offre.
3. Valider les offres, corriger les prix.
4. Produire la mercuriale de la date de livraison.
5. Recopier la mercuriale dans Socleo.
6. Suivre planifié / offert / vendu.
7. Gérer les comptes utilisateurs.

## Questions ouvertes
Qui valide les offres et quand ? Comment sont fixés les prix ? D'où viennent les ventes du rapport répartition ? Existe-t-il un export ou une API ? À quoi sert précisément le stock longue conservation ? Quels droits a chaque type de compte ?

Dernière vérification sur le vrai outil : 14/11/2026 (lecture seule, partielle).
