# Ouvre ta ferme (OTF), partie vente : carte de l'outil

Statut : **à vérifier**. Relevé du 14/11/2026, lecture seule, sur une ferme de test vide. Aucune vente, aucun client, aucun produit n'a été créé (une vente ne peut pas être supprimée dans OTF). Voir [README.md](README.md) pour la lecture des positions `(x, y, l × h)`, fenêtre 1224 × 862.

## 1. À quoi sert OTF pour nous
Outil cible : il doit remplacer Zandoly et Socleo. La partie vente couvre les produits, les clients, les ventes, les catalogues, les boutiques en ligne, la caisse, la facturation et une API. L'association ne l'utilise pas encore.

## 2. Menus
- Onglets du haut : Bureau (20, 62), Production (71, 62), Vente (132, 62), Gestion (183, 62).
- Colonne de gauche, onglet Vente (x = 36, largeur 205) : Ventes (y 184), Clients (216), Produits (249), Catalogues (281), Boutiques en ligne (314), Caisse enregistreuse (346), Site internet (416), E-mailing (449). Paramètres en bas (10, 812).

## 3. Écrans

### 3.1 Ventes
Liste vide sur la ferme de test. Bouton « Ajouter une première vente » (267, 499, 207 × 36) vers le formulaire de vente. Prix distincts : professionnel (HT) et particulier (TTC).

### 3.2 Produits
Choix du type de produit sur trois cartes (x 267, 580, 894 ; y 378, 489, 595). Formulaire (profil plante) :
- nom (418, 195, 771 × 31), référence (441, 239) ;
- unité (liste, 418, 309), origine (418, 353), qualité bio (418, 397), TVA (418, 475) ;
- complément (zone de texte, 423, 588) ;
- espèce (451, 1024), variété (423, 1068), conditionnement (423, 1112) ;
- prix particulier (423, 1375), prix professionnel (423, 1533), colis de base en kg (423, 1606) ;
- bouton **Créer le produit** (418, 813, 117 × 29).
Les unités de vente incluent colis, botte, pièce, sachet, kg. Import CSV des produits, clients et prix possible.

### 3.3 Clients
Choix de la catégorie par boutons radio (x 597 ; y 455, 487, 519), bouton **Créer le client** (583, 654, 105 × 29).

### 3.4 Catalogues
Un catalogue regroupe des produits avec leurs prix, pour une clientèle donnée.

### 3.5 Boutiques en ligne
Trois choix (382, y 211, 287, 381) : boutique personnelle, boutique collective, autre ; bouton Continuer (1005, 459, 82 × 29). **Boutique collective** : partagée entre producteurs par un groupe de producteurs et un code d'invitation ; pas de choix du mode de paiement ni de frais de livraison.

### 3.6 Caisse enregistreuse
« Nouveau point de vente » (1006, 20, 182 × 29) ; nom (587, 574, 587 × 31) ; « Créer le point de vente » (583, 658, 159 × 29).

### 3.7 Site internet et e-mailing
Menus présents (Site internet, E-mailing) ; non explorés plus avant.

### 3.8 Paramètres liés à la vente
Documents de vente (configuration des documents), unités, modes de paiement : écrans accessibles depuis les paramètres de la ferme.

## 4. Facturation
Les ventes ne peuvent pas être supprimées ; un avoir se fait par une vente en quantités négatives. Import de ventes depuis des documents (offre Gestion).

## 5. API
- Version bêta ; lecture ouverte aux structures abonnées, écriture bêta seulement.
- Limites : 4 requêtes par seconde, 30 par minute, 100 par jour avec l'offre Gestion (1 000 par jour avec Pilotage).
- Un jeton par ferme. Le jeton n'est jamais vu ni écrit par Claude ; la page des clés n'a pas été ouverte.
- Aucun accord écrit pour l'écriture : rester en lecture seule.

## 6. Offres
Gestion : 120 € par an HT. Pilotage : 300 € par an HT. Adhésion association à partir de 50 €. Ouverture des abonnements le 16/11/2026 ; toutes les fonctions sont ouvertes jusqu'au 15/11/2026.

## 7. Non relevé
Écrans avec données (ferme vide), formulaire complet de vente, catalogues et boutiques remplis, site internet, e-mailing, export comptable, intégrations.
