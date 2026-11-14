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

## 7. Compléments du 14/11/2026 : menu complet et documentation lue en entier
Voir [couverture.md](couverture.md).

### 7.1 Menu complet de la ferme de test (vu)
- **Accueil** : tableau de bord (bêta), notes, équipe, nouveautés, prévisions météo sur 13 jours.
- **Production** : planning (quotidien, hebdomadaire, annuel, nouveau planning en bêta), plan de culture, plan d'assolement, prévisionnel financier, semences et plants, itinéraires techniques, plan de la ferme, boîte à outils, analyses (temps de travail, cultures).
- **Vente** : Ventes, Clients, Produits, Catalogues, Boutiques en ligne, Caisse enregistreuse, Site internet, E-mailing.
- **Gestion** : facturation électronique, banque, cahiers de caisse, précomptabilité, comptabilité (livre journal, grand livre, balance, immobilisations, synthèse).
- **Paramètres** : administratif, profil, TVA, fonctionnalités, abonnement, production, commercialisation, comptabilité, facturation électronique, exporter les données, importer des données, intégrations (clés d'API : jamais ouvertes).

### 7.2 Écrans vus
- **Produits** : huit types : origine végétale, origine animale, alimentaire transformé, non alimentaire, composé (panier, bouquet), autre, prestation de service, frais de livraison.
- **Paramètres de commercialisation** : devis, bons de livraison et factures (coordonnées, mentions, textes) ; export des commandes en PDF (nombre par page, tri) ; modes de livraison (points de retrait et livraisons proposés aux clients) ; e-mails (messages aux clients et heure d'envoi) ; unités de vente ; modes de règlement ; paiement par carte (Stripe, SumUp) ; cagnottes ; précomptabilité (numéros de compte des ventes et frais de livraison).
- **Fonctionnalités** : production, temps de travail, RH (réservée aux offres Gestion et Pilotage à partir du 16/11/2026) ; en bêta, réservées aux adhérents de l'association OTF : caisse hors ligne, paiement au terminal SumUp, import de ventes (photo de ticket, facture PDF ou message ; réservé à l'offre Gestion), justificatifs.
- **Exporter les données** : par année : plan de culture, assolement, plan de la ferme, temps de travail, interventions, récoltes, ventes, articles vendus, factures, cahiers de caisse ; données intégrales : produits, clients.

### 7.3 Ce que dit la documentation (49 pages lues en entier)
- **Prix** : prix distincts professionnel (HT) et particulier (TTC) ; hiérarchie : prix de base, puis catalogue ou boutique, puis groupe de clients, puis client.
- **Boutiques** : personnelles ou collectives (groupe de producteurs, code d'invitation) ; pas de choix du paiement ni de frais de livraison dans une boutique collective ; paiement en ligne Stripe ou SumUp, liens de paiement (hors boutique collective).
- **Facturation** : acomptes, facturation mensuelle, avoir par vente négative, facturation électronique par la plateforme SUPER PDP (Chorus Pro annoncé).
- **Imports CSV** : produits (champ « distribution » production ou revente ; une réimportation écrase toutes les valeurs), clients, prix, tiers, plan de culture, adhérents d'AMAP.
- **AMAP** : contrats, souscriptions, règlements, permanences, adhésions, formulaire d'inscription.
- **Comptabilité** : treize pages (banque, cahiers de caisse, cahiers reliés à Stripe ou SumUp, import des ventes en écritures, comptabilité d'engagement, justificatifs, immobilisations, TVA, trames, livre des recettes, autoconsommation) ; la comptabilité est en grande partie automatique à partir des ventes rapprochées en banque.
- **Absents de la documentation** : tournées, chargement et livraison mobile, lots et DLC, marge et facture pour le compte d'autres fermes, facture fournisseur, duplication de commandes, disponibilités saisies par plusieurs fournisseurs, consignes.
- **Page d'accueil du site OTF** : mentionne aussi des relevés de prix (prix constatés chez les producteurs utilisateurs) et un outil de recherche d'aides agricoles.

## 8. Non relevé
Écrans avec données (ferme vide), formulaire complet de vente, catalogues et boutiques remplis, site internet, e-mailing, abonnement, intégrations, documentation de l'API, ferme de démonstration publique d'OTF.
