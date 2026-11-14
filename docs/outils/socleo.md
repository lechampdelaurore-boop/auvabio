# Socleo (site de l'association) : carte de l'outil


> **Relevé partiel : compte non administrateur.** Ce relevé a été fait avec un compte sans droits d'administration (le compte Socleo est en consultation seule). Il manque sûrement des écrans, des boutons, des modules (par exemple Comptabilité, Caisse, paramétrage, droits, comptes, éditions) et des fonctions réservées aux administrateurs. Une absence dans cette fiche veut dire « non vu », pas « n'existe pas ». À refaire avec un compte administrateur, en lecture seule, quand François le décidera.

Statut : **à vérifier** avec Romain et le bureau. Relevé du 14/11/2026, lecture seule, compte de consultation (menu complet, aucun droit de modification). Version affichée : Socleo 3.4. Voir [README.md](README.md) pour la lecture des positions `(x, y, l × h)`, fenêtre 1224 × 862.

## 1. À quoi sert Socleo pour nous
Logiciel de **vente, facturation, stock et livraison**. Chaque client commande ; chaque ligne est rattachée à un **fournisseur** (une ferme). Socleo calcule les montants client, fournisseur et la marge, édite les bons de livraison et les factures, organise les tournées, suit le chargement et la livraison, gère le stock et l'approvisionnement. Le site public sert de vitrine ; « Mon compte » ouvre Socleo.

Les fermes sont des fournisseurs. Des comptes techniques (stock, sortie de stock, régulation) servent à faire entrer et sortir du stock : leur rôle exact est à confirmer.

## 2. Menu
Menu vertical à gauche (x = 0, largeur 225) : Commandes (y 94), Etat (131), Stock (163), Tournées (200), Produits (236), Activités (273), Demandes (309), puis Membres. Le menu Assistance donne : Nouveautés, Aide en ligne, communauté Socleo. Stock regroupe État de stock et Approvisionnement ; Tournées regroupe Tournées, Chargement, Livraisons.

## 3. Écrans

### 3.1 Commandes (écran central)
Barre du haut :
- type de date à filtrer (liste, 263, 64, 185 × 25) : livraison client, livraison fournisseur, facturation client, facturation fournisseur, DLC/DDM ;
- périodes : Jour (485, 63), Mois (594, 63), Libre (638, 63), Précédent (682, 63), Suivant (1014, 63) ;
- montants affichés (liste, 986, 92, 193 × 25) : client, client TTC, fournisseur, marge, facturé client, facturé fournisseur, marge sur facturation, suivi logistique.

Cinq vues (onglets, y = 153) : Vue client (629), Vue fournisseur (704), Vue produit (807), Synthèse (889), Statistiques (971).

Autres boutons :
- **Autres** (1104, 152, 70 × 23) : menu avec Exporter et Importer (d'après l'aide) ;
- liste « Sélectionnez une action » (362, 231, 172 × 25), pour les commandes cochées : Dupliquer la commande, Détailler le lot, Modifier le suivi logistique ;
- **Éditer** (1115, 225, 76 × 34) ;
- **Afficher** (662, 312) et **Cacher** (752, 312) : ouvrent ou ferment les filtres.

Filtres : état de la commande (valides : en cours, clôturées, facturées client, facturées fournisseur ; invalides : brouillon, rétractées, annulées), notification, groupe de clients (nombreux), fournisseur, seuil de poids ou de montant. Des **favoris** (filtres enregistrés) existent.

Lecture : commandes regroupées par date de livraison puis par client, avec quantité, poids, montant ; le code de lot apparaît sous les produits. Au bout de chaque ligne de client et de produit : un crayon jaune (modifier la commande ou la ligne), d'après l'aide ; non relevé à l'écran.

Particularités : produits « anti-gaspi », caisses consignées (quantités négatives au retour), ligne « Transport » ajoutée à chaque livraison. Plusieurs modes de paiement. Facturation fournisseur globale ou par client. Une commande **facturée** ne peut plus être modifiée.

### 3.2 Saisie d'une commande (d'après l'aide, non ouverte à l'écran)
Bouton **Nouvelle commande** ; choix du client et de la date de livraison ; filtres produits (producteur, étiquette, mot-clé) ; pastilles de disponibilité (vert, orange, rouge) ; boutons + et − ; bouton **Détail** (prix, poids, lot, DLC, producteur secondaire, préférence) ; onglet **Commande type** ; bouton **Valider**.

### 3.3 Etat (éditions)
Liste des documents édités (bons de livraison, par date, client, fournisseur, numéro). **Filtrer** (258, 127). **Télécharger** (1090, 204, 104 × 34). Autres types d'états : non ouverts.

### 3.4 Stock : État de stock
- recherche (255, 149, 390 × 27) et OK (648, 149) ; choix du niveau (957, 149) ; unité ou colisage (1081, 149) ;
- liste d'actions (379, 188, 206 × 29) pour les produits cochés : Saisir un inventaire, Modifier la zone de stockage, Retirer du stock, Rapprocher les lots ;
- Afficher (773, 272) / Cacher (864, 272) les filtres ; icônes de ligne vers x ≈ 799, 1106, 1129, 1148 ;
- boutons Import inventaire, Export niveaux, Import / Export paramètres ;
- filtres : producteur, étiquette, secteur, famille, mode de gestion (produit ou lot), zone (trois zones de stockage).
Inventaire (d'après l'aide) : cocher les produits, « Saisir un inventaire », choisir la date ; **si fait le matin, choisir la veille**.

### 3.5 Stock : Approvisionnement
Recherche (255, 186) ; unité (1081, 186) ; actions (379, 225). Colonnes : Aujourd'hui, Rec. (à recevoir), Exp. (à expédier), niveau à la date choisie (par défaut J+30), risque de rupture (sans risque, sensible, moyen, fort). Action « Nouvelle entrée en stock ».

### 3.6 Tournées, Chargement, Livraisons
- Tournées : Semaine (366, 63), Mois (448, 63), Libre (509, 63) ; liste des plans de tournée par secteur ; filtre par état (nouvelle, en cours, en pause, terminée).
- Plans fixes : depuis Commandes, Vue client, à une date, icône « Écran dédié » (module sur demande). Boutons : Enregistrer comme une nouvelle tournée, Enregistrer la tournée existante, Supprimer la tournée (définitif). Éditions : synthèse transporteur (.csv ou .pdf) et bons de livraison (PDF, dans l'ordre de tournée).
- Chargement et Livraisons : écrans mobiles ; on choisit date et tournée, puis chaque client. Non ouverts à l'écran.

### 3.7 Produits (catalogue)
Filtrer (258, 61) ; **Exporter** (407, 61, 69 × 23) ; **Editer** (486, 61, 53 × 23) ; recherche (258, 119, 337 × 26) ; liste d'actions (370, 183, 206 × 29) : modifier la zone de stockage, activer la gestion du stock, éditer des étiquettes ; liens de secteur y = 216. Colonnes : désignation, délai de commande, tarif fournisseur, prix de vente HT, marge %. L'import (Enregistrer, Tester le fichier, Planifier l'import) est en haut de page.

### 3.8 Activités et Demandes
Activités : agenda de relation client (rendez-vous, appel, e-mail, rappel), import par fichier. Demandes : demandes internes ou de clients et fournisseurs (réception, préparation, inventaire, livraison). Peu utilisés sur la période.

### 3.9 Membres
Filtrer (258, 62) ; Tous (407, 62) ; Clients (454, 62) ; Fournisseurs (531, 62) ; Coordinateurs (638, 62) ; recherche (257, 120) ; onglets Général (260, 189), Commandes (330, 189), Comptes (426, 189), Adhésions (502, 189), Emballages réemployables (588, 189) ; liste d'actions (359, 233, 200 × 25) ; taille de page (1144, 233). Bouton « Inscrire un membre » (d'après l'aide). Environ 380 membres. Familles de clients : restauration collective, restauration commerciale, magasins, transformateurs, maraîchers, grande distribution, grossistes. Messages en lot et message de bienvenue.

## 4. Import et export (point clé pour la recopie)
- **Commandes** : l'import ne fait que **créer**, jamais modifier. Partir du fichier vierge fourni par Socleo. Colonnes obligatoires : référence client, date de livraison (JJ/MM/AAAA), référence produit, unités commandées (entier). **Importer deux fois le même fichier crée les commandes deux fois** ; aucune annulation prévue : contrôle humain obligatoire.
- **Produits** : exporter, modifier, réimporter (.ods conseillé). « Tester le fichier » donne un bilan sans rien modifier. **Danger** : l'option « Supprimer définitivement les produits absents du fichier ».
- Option « Forcer la mise à jour du tarif client » : écrase le prix catalogue de la ligne.
- API « Circuit ouvert » : gratuite sur demande au support Socleo ; produits, commandes, stocks, dans les deux sens ; la clé de sécurité n'est jamais vue ni écrite par Claude. Maintenance seulement.

## 5. Risques à mettre dans les procédures
1. Import de commandes en double.
2. Suppression de produits absents du fichier à l'import.
3. Commande facturée : plus modifiable.
4. Caisses consignées : quantités négatives normales au retour.
5. « Forcer la mise à jour du tarif client ».
6. Inventaire du matin : dater de la veille.

## 6. Défauts d'ergonomie constatés
- Très nombreux filtres et groupes de clients, sans guide pour savoir lesquels utiliser.
- Beaucoup d'actions cachées derrière « Sélectionnez une action » et « Autres ».
- Même information (date, montant) à choisir dans plusieurs listes avant de lire un écran.
- Aucune annulation d'un import ; peu de garde-fous.
- Comptabilité absente du menu du compte consulté (autre compte probable).

## 7. Compléments du 14/11/2026 : écrans parcourus et aide lue en entier
Voir [couverture.md](couverture.md). Tout ce qui suit vient de l'aide en ligne (décrit, non testé, pas forcément activé chez nous) ou d'un écran parcouru (marqué « vu »).

### 7.1 Ce que montrent les écrans (vu)
- **Commandes** : fenêtres cachées dans la page : saisie d'une commande, duplication (fréquence et nombre de répétitions, date), facturation (une facture globale ou une facture par client), versement (onze modes : chèque, espèces, virement, carte, bon d'achat, prélèvement, paiement différé, monnaies locales, lettre de change, autre), calcul des emballages réemployables, export des données de réception, changement de fournisseur. Quatre modes logistiques de ligne : livraison en direct, en transit, entrée en stock, expédition de stock. Six favoris de filtres déjà enregistrés. Des pastilles de ligne : non notifiée, validée, modifiée depuis la notification.
- **Stock** : « Afficher les produits en rupture » ; trois lectures (Stock, Stock + Transit, Transit) ; colisage livraison ou unité ; filtres supplémentaires : étiquette (bio, sélection, anti-gaspi, produit à l'unité, prestation producteur, disponibilité garantie), secteur, famille, groupe fournisseur (dont un groupe par année d'adhésion), type de stock (par produit ou par lot), **gestion des lots**, **DLC en alerte**, catégorie (adhésion, catalogue, consigne, emballage réemployable, facture fournisseur, frais de port, prestation), agriculture (bio, conversion, sans engrais ni pesticides, biodynamie), conditionnement, zone de stockage, précommande, saisonnalité, catégorie comptable. Environ 46 produits en stock.
- **Approvisionnement** : colonnes Aujourd'hui, Rec., Exp., Dans le futur, Risque de rupture, Actions ; date de visualisation du stock théorique ; mêmes filtres plus « Fournisseur auprès de ». Environ 89 produits.
- **Tournées** : même barre jour, semaine, mois, libre ; une liste d'une vingtaine de plans de tournée (par secteur et par jour) ; aucune tournée à la date vue.
- **Produits** : environ 78 produits visibles ; onglets de secteurs et de familles ; colonnes désignation, délai de commande, tarif fournisseur, prix de vente HT, marge ; boutons Exporter, Éditer, Taux de marque, Produit disponible ; fenêtres cachées : étiquette de répartition, « Visualiser les quantités disponibles pour », import (fichier, action, tester), « Affecter en tant que », période de livraison.
- **Activités** : jour, semaine, mois, libre ; catégories rendez-vous, appel, e-mail, rappel ; actions : dupliquer, supprimer, modifier ; import d'activités (Enregistrer, Tester le fichier, option de retrait des activités absentes). Vide sur la période.
- **Demandes** : statuts ouvertes, clôturées, toutes ; types réception, préparation, inventaire, livraison, demande client, demande fournisseur ; action « Changer le statut » ; export. Vide sur la période.
- **Membres** : filtre par rôle (tous, clients, fournisseurs, coordinateurs) ; onglets Général, Commandes, Comptes, Adhésions, Emballages réemployables ; une quarantaine de champs de fiche (raison sociale, profil, type d'établissement, SIRET, groupe, rôle, état de relance...) ; actions « Envoyer un message », « Envoyer le message de bienvenue », extraction, import de membres. Quelques favoris de relance hebdomadaire.
- **Mon compte (vue client)** : onglets Commander, Mes achats, Mes informations, Mes demandes ; deux listes Commandes et Factures ; commande type ; panier ; fenêtres cachées : copier la commande, dupliquer sur une date ou sur un intervalle (répéter toutes les x semaines), déplacer le brouillon, nouveau versement, nouvel abonnement, créditer mon compte, modifier la livraison.
- **Boutique « Commander »** : s'ouvre sur un calendrier pour choisir la date de livraison.
- **Chargement et Livraisons** : s'ouvrent vides sur ordinateur (écrans mobiles) ; non cliqués.

### 7.2 Ce que décrit l'aide (lu en entier)
- **Disponibilités par fournisseur** : chaque fournisseur ayant le droit « gestion des disponibilités » saisit sa quantité et son état ; le coordinateur voit la somme ; quantité restante calculée ; prix et quantité par fournisseur et par période. C'est la fonction la plus proche de l'offre hebdomadaire de Zandoly.
- **Stock** : par produit ou par lot, à l'unité ou au poids ; seuil d'alerte, stock de sécurité, niveau de réapprovisionnement ; DLC/DDM avec délai d'alerte ; rapprochement commande/lot en trois modes ; DLC dépassée = rapprochement impossible ; inventaire manuel ou par fichier ; pertes ; suppression automatique des produits à stock nul sans mouvement le 1er du mois.
- **Rupture à la commande** : affecter au fournisseur, autoriser avec ou sans notification, bloquer.
- **Livraisons (module calendrier)** : dates de livraison avec ouverture et fermeture des commandes, producteurs disponibles par date, points de retrait, permanences ; duplication de semaines types ; modes de livraison (sur un lieu, à domicile, relais) ; frais de port de cinq types ; lieux avec créneaux ; ordres de transport électroniques pour deux transporteurs ; casiers de distribution.
- **Tournées** : plans fixes, tournées quotidiennes optimisées par un partenaire, export GPX, chargement et livraison sur mobile avec signature et justificatif envoyé au client, tableau de bord par état (nouvelle, en cours, en pause, terminée).
- **Emballages réemployables** : produit et conditionnement de livraison par emballage, niveaux chez chaque client, inventaire automatique mensuel.
- **Offres et remises** : par catalogue, secteur, fournisseur ou produit ; priorités ; remise figée à la création de la commande (« Propager le tarif catalogue » pour mettre à jour).
- **Contrats** : abonnements de livraisons récurrentes (module absent du menu consulté).
- **Demandes** : non-conformités avec motifs, sévérité, préjudice, commentaires, clôture.
- **Activités** : agenda client, relances périodiques, états « Relancée » et « Mise en demeure » des factures.
- **Fabrication** : ordres de fabrication pour transformateurs.
- **Caisse** : webcaisse avec ticket Z inaltérable (module absent du menu consulté).
- **Comptabilité** : facturation client globale ou par bon, avoirs de trois façons, factures fournisseur et justificatifs, facturation pour le compte des producteurs, relances, paiement en ligne, rapprochement bancaire par un service tiers, prélèvements SEPA, virements aux fournisseurs, Chorus Pro, exports comptables, **archives comptables** (ZIP de PDF et CSV, irréversibles : à télécharger avant toute bascule).
- **Facturation électronique** : format Factur-X, plateforme agréée SUPER PDP (la même qu'OTF), phase pilote ; limitée à certaines interfaces.
- **Site** : site vitrine, pages, éditeur, suivi d'audience, domaine, mentions légales.
- **Droits** : rôles par périmètre de groupe, droits « chargement » et « livraison » pour des externes, droit fournisseur « gestion des disponibilités ».
- **Manuels** : l'aide liste des manuels téléchargeables (coordinateur, producteur, comptable, module fabrication, Chorus Pro, API) : probablement la meilleure source pour les procédures. Non téléchargés.
- **Sauvegarde** : données conservées 10 ans ; les e-mails envoyés par Socleo ne sont pas stockés.

### 7.3 Risques supplémentaires à mettre dans les procédures
7. « Forcer la mise à jour des livraisons existantes » (duplication de livraisons) : écrase.
8. Import de contacts en mode « Remplacer » : supprime les contacts absents du fichier.
9. Import d'inventaire d'un produit par lot : tout lot absent du fichier est clôturé à stock nul.
10. « Calcul des emballages réemployables » : recréé à chaque clic.
11. Option « Supprimer du site distant les produits non sélectionnés » (copie entre sites) : non pertinente chez nous, à connaître.
12. Produits à stock nul sans mouvement : supprimés le 1er du mois.
13. Archivage comptable : irréversible ; fige la période.

## 8. Non relevé
Comptabilité, Caisse, Paramétrage, droits et rôles, Contrats, Offres, Fabrication (absents du menu consulté), boutons au bout des lignes de données, écrans de saisie (nouvelle commande, fiche produit, fiche membre : non ouverts pour ne rien enregistrer), Chargement et Livraisons en détail, manuels téléchargeables.
