# Carte de Zandoly


> **Relevé partiel : compte non administrateur.** Ce relevé a été fait avec un compte sans droits d'administration (le compte Socleo est en consultation seule). Il manque sûrement des écrans, des boutons, des modules (par exemple Comptabilité, Caisse, paramétrage, droits, comptes, éditions) et des fonctions réservées aux administrateurs. Une absence dans cette fiche veut dire « non vu », pas « n'existe pas ». À refaire avec un compte administrateur, en lecture seule, quand François le décidera.

Statut : **à vérifier** (relevé du 14/11/2026, lecture seule, compte de ferme). Voir [README.md](README.md) pour la lecture des positions (fenêtre 1224 × 862).

## À quoi sert Zandoly
Bourse d'offres et planification commune de l'association :
- chaque ferme annonce sa production prévue (**Planification**) ;
- chaque semaine, chaque ferme propose ce qu'elle peut livrer (**Offre** : produit, prix, quantité, unité de conditionnement) ;
- les rapports regroupent les offres en **mercuriale** par date de livraison, recopiée dans Socleo trois fois par semaine.

Technique : application web de la famille ERPNext / Frappe (écrans de liste, de fiche et de rapport communs). Espace de travail unique « Auvabio ». **Aucune aide intégrée** : le menu « Aide » ne contient que « À propos » et « Raccourcis clavier ».

## Cadre commun à tous les écrans
- Barre du haut : fil d'Ariane à gauche (vers (191, 20)), nom de la ferme du compte (pastille verte), recherche « Rechercher (Ctrl + G) » (≈ (650, 12, 300 × 36)), menu « Aide » (≈ (1042, 23)), avatar du compte (≈ (1099, 12, 36 × 36)).
- Bouton principal d'une fiche : **Enregistrer**, en haut à droite (≈ (1103, 96)). Une fiche non enregistrée affiche « Non sauvegardé » à côté du titre.

## Page d'accueil (espace « Auvabio »)
Cinq raccourcis en haut, puis quatre cartes de liens.

| Élément | Position (x, y, l × h) | Ouvre |
|---|---|---|
| Saisir une offre | (91, 237, 250 × 38) | nouvelle offre (formulaire vide) |
| Consultation des offres | (355, 237, 250 × 38) | rapport des offres par date |
| Mercuriale | (619, 237, 250 × 38) | rapport avec les prix |
| Rapport planification | (91, 289, 250 × 38) | rapport quantités prévues |
| Rapport répartition | (355, 289, 250 × 38) | planifié / offert / vendu |
| Carte « Données fermes » : Liste des offres | (95, 428, 234 × 28) | liste des offres |
| — Planification | (95, 460, 234 × 28) | liste des planifications |
| — Stocks longue conservation | (95, 492, 234 × 28) | liste des stocks |
| Carte « Rapports » : Rapport planification | (359, 428, 234 × 28) | rapport |
| Carte « Référentiels » : Produits | (623, 428, 234 × 28) | fiches produit |
| Carte « Paramètres » : Produits planifiables | (887, 428, 234 × 28) | produits planifiables |
| — Utilisateurs | (887, 460, 234 × 28) | comptes (non consulté) |

## Écran : liste des offres
- Boutons en haut à droite : **Consulter les offres** (788, 83, 145 × 30), **Ajouter Offre** (1016, 83, 118 × 30).
- Barre de filtres : date de livraison (88, 153, 140 × 26), débouché (238, 153, 140 × 26), producteur (388, 153, 140 × 26), **Filtre** (829, 153, 67 × 30), réinitialiser (897, 153), tri (939, 153), « Dernière Mise à Jour » (972, 153, 149 × 30).
- Lignes : case à cocher à gauche (95, ≥ 210), identifiant de l'offre (≈ (148, ≥ 244)), statut (Brouillon ou Soumis), date de livraison (≈ (750, ≥ 245)), ancienneté. Un calendrier est affiché à droite de la page.
- Identifiant : `AAAAMMJJ-FERME`.

## Écran : fiche d'une offre
- Champs : « Date de livraison » (obligatoire), « Débouché » (obligatoire : Magasin, Restauration collective, Transformation, Maraichers), « Producteur » (rempli d'office avec la ferme du compte).
- Une fois enregistrée : tableau de lignes (produit, prix, quantité, unité, total), bouton « Ajouter une ligne », zone de commentaires, journal des modifications (qui, quand).
- Une offre **soumise n'est plus modifiable** (message « Cette fiche n'est plus modifiable ») ; bouton « Dupliquer cette offre » pour la reconduire. Un administrateur valide et peut corriger un prix (à confirmer).
- Formulaire « Nouvelle offre » : champs en haut à gauche, **Enregistrer** en haut à droite.

## Écran : planification
- Liste : une fiche par campagne + ferme + produit planifiable + débouché (de l'ordre de 2 000 fiches). Filtres : campagne, producteur, produit, famille. Bouton « Ajouter Planification » en haut à droite.
- Fiche : campagne (par défaut la campagne en cours), produit planifiable (obligatoire), débouché (obligatoire), quantité totale, unité (K = kilo, U = unité), prix moyen, tableau « Quantités » (12 mois de mai à avril, crayon à droite de chaque mois), bouton « Ajouter une ligne ». Journal des modifications.

## Écran : stocks longue conservation
- Liste (vide pour le compte de ferme utilisé). Fiche : onglets « Détail du stock » et « Ventes » ; champs campagne, ferme, entrepôt, produit planifiable, quantité initiale, nombre de palox, commentaire ; section repliable « Modification du stock ».

## Rapports (lecture)
- **Rapport planification** : filtres campagne, producteur, famille, produit, débouché, période (par mois ou par semaine). Lent (jusqu'à environ 10 s). Une ligne par ferme × produit.
- **Consultation des offres** : filtre par date de livraison, famille, produit, producteur, débouché ; un commentaire libre est affiché en tête ; total des colis ; bouton « Mercuriale » en haut à droite.
- **Mercuriale** : même contenu avec le prix, le total en euros et le débouché ; bouton « Consultation des offres ». C'est la sortie la plus proche de la recopie vers Socleo.
- **Rapport répartition** : période et débouché, comparaison planifié / offert / vendu par ferme et produit, total par produit, rapport ventes / planification. La colonne « Ventes » était à zéro lors du relevé : origine à confirmer.

## Référentiels
- **Produits** (≈ 960 fiches, dont ≈ 200 désactivées) : code, nom, famille, unité de stock (K ou U), conditionnement, facteur de conversion (kg par colis), prix moyen et sa date, ancien code (proche des références de Socleo).
- ≈ 57 conditionnements différents ; les plus fréquents : colis de 10 kg, 5 kg, 8 kg, 7 kg ; bottes ; pièces par 8 ; sacs de 20 kg.
- **Variantes d'un même produit** (source probable d'erreurs de saisie) : suffixes RHD (restauration collective), TRANSFO (transformateurs), HL (fiches désactivées), PALOX (200 à 250 kg), « avec étiquette EAN », « (Conversion) » (sens à confirmer), « (botte) », « (gros / petit calibre) ». Un même nom peut avoir plusieurs conditionnements.
- **Produits planifiables** (≈ 210) : statut Activé ou Désactivé, famille, durée de saisie.
- ≈ 27 familles (ratatouille, légumes feuilles, pommes de terre tendres ou fermes, légumes racines, alliacées, crudités, choux, pommes, courges…).

## Ce qui n'apparaît pas
Facturation, tournées, clients (Socleo). Origine des ventes du rapport répartition : inconnue. Export fichier ou API : inconnus.

## Tâches probables liées à Zandoly (pour l'étape 1)
1. Tenir le référentiel et ouvrir la campagne. 2. Relancer les fermes qui n'ont pas soumis leur offre. 3. Valider les offres, corriger les prix. 4. Produire la mercuriale de la date de livraison. 5. Recopier la mercuriale dans Socleo. 6. Suivre planifié / offert / vendu. 7. Gérer les comptes.

## Questions ouvertes
Qui valide les offres et quand ? Comment sont fixés les prix ? D'où viennent les ventes du rapport répartition ? Existe-t-il un export ou une API ? Rôle précis du stock longue conservation ? Droits de chaque type de compte ? Sens de « (Conversion) » dans les noms de produits ?

Dernière vérification sur le vrai outil : 14/11/2026 (lecture seule, partielle).
