# Comparatif : Zandoly + Socleo face à OTF (vente)

Statut : **brouillon à vérifier**. Établi le 14/11/2026 à partir des cartes [zandoly.md](zandoly.md), [socleo.md](socleo.md), [otf-vente.md](otf-vente.md), de l'aide en ligne de Socleo et d'un relevé en lecture seule. Aucune donnée réelle. Règle de rédaction : une ligne n'affirme « absent » que si la fonction a été cherchée des deux côtés (écrans et aide). Les nombres de clics sont des **estimations tirées de l'aide et des écrans**, pas des mesures chronométrées : à confirmer avec Romain.

Rappel : Zandoly et Socleo vont par deux chez nous. On compare donc le duo à OTF.

## 1. Ce que le duo fait et qu'OTF ne fait pas (ou pas encore)
| Fonction | Où | Remarque pour le module complémentaire |
|---|---|---|
| Offre hebdomadaire de chaque ferme, par débouché, avec validation par un administrateur | Zandoly | Cœur du besoin collectif. À reconstruire. |
| Planification des cultures commune (campagne, produit, mois) et rapport planifié / offert / vendu | Zandoly | Idem. |
| Mercuriale : prix et quantités de toutes les fermes par date de livraison | Zandoly | Sortie à produire sans recopie. |
| Stocks de longue conservation partagés (palox, entrepôt) | Zandoly | À cadrer. |
| Référentiel commun d'environ 960 produits avec conditionnements et facteur kg par colis | Zandoly | À nettoyer (variantes). |
| Vente d'une ferme **pour le compte d'autres fermes** avec marge, tarif fournisseur et tarif client par ligne | Socleo | Boutique collective OTF : sans choix du paiement ni frais de livraison, sans paiement en ligne (prévu) ; aucune marge ni facture pour le compte des fermes ; la logistique n'est volontairement pas cadrée. |
| Facture fournisseur globale ou par client | Socleo | **Non trouvé dans OTF** : la facturation d'OTF part des ventes de la ferme ; achat-revente, marge et facture par ferme ne sont ni documentés ni prévus. À construire. |
| Tournées : plans fixes, chargement, livraison sur mobile, consignes et emballages réemployables | Socleo | **Absent d'OTF** : ni documentation, ni feuille de route. Seul un export PDF des ventes du jour sert à préparer les livraisons. À construire. |
| Gestion de stock par lot, DLC, zones, approvisionnement et risque de rupture | Socleo | **Partiel dans OTF** : les catalogues gèrent des disponibilités et un « stock principal » existe, mais les **lots** sont seulement prévus (priorité élevée) et la **DLC** n'est pas mentionnée. Pas d'alertes de rupture documentées. À construire. |
| Groupes de clients, favoris de filtres, relances en lot | Socleo | Partiellement dans OTF (e-mailing). |
| Duplication de commandes (récurrence, groupe de clients) | Socleo | **Non trouvé dans OTF** (ni documentation, ni feuille de route). |

## 2. Ce qu'OTF fait que le duo ne fait pas (constaté des deux côtés)
Chaque ligne a été cherchée dans l'aide en ligne de Socleo (116 articles par rubrique), sur ses écrans et sur ceux de Zandoly. Les lignes que Socleo couvre aussi sont dans le tableau suivant.

| Fonction | Constat OTF | Constat duo |
|---|---|---|
| Comptabilité tenue dans l'outil (livre-journal, TVA, immobilisations, cahiers de caisse), en grande partie automatique avec l'offre Gestion | Documentation de 15 pages | Socleo ne tient pas la comptabilité : exports vers des logiciels comptables, rapprochement bancaire, prélèvements, virements SEPA fournisseurs. Zandoly : rien |
| Plan de culture et production de la ferme dans le même outil que la vente | Documentation et FAQ | Zandoly ne montre qu'une planification mensuelle par produit et par ferme ; pas de séries ni d'itinéraires techniques constatés |
| API documentée et ouverte aux abonnés (lecture ; écriture en bêta) | Documentation de l'API | Socleo : API « Circuit ouvert » gratuite sur demande, en maintenance seule. Zandoly : aucune API connue |
| Facturation électronique avec plateforme agréée intégrée | Documentation | Socleo : une rubrique « Facturation électronique » existe dans l'aide, non lue ; à vérifier |

## 2 bis. Ce qu'OTF fait et que Socleo fait aussi (retiré de la liste « OTF seul »)
Erreur corrigée le 14/11/2026 : la première version disait que le duo n'avait pas ces fonctions.
| Fonction | OTF | Socleo (aide en ligne et écrans) |
|---|---|---|
| Boutique en ligne pour les clients (commander, panier, commande type, familles de produits) | Boutiques personnelles et collectives | Écran « Commander » du site, panier, commande type ; articles sur la finalisation de commande et les liens vers la boutique |
| Paiement en ligne | Oui (offre dédiée) | Article « Comment gérer le paiement en ligne sur mon site » |
| Site internet | Création de site | Site vitrine : rubriques, pages, éditeur, logo, couleurs, pied de page, suivi d'audience, mentions légales |
| Envoi d'e-mails aux clients | E-mailing | « Envoi de messages », « Envoyer une newsletter à ses clients », messages en lot depuis Membres, relance des factures |
| Caisse enregistreuse | Points de vente | Module Caisse (20 articles : session de vente, ticket Z, fond de caisse, livre de caisse) ; absent du menu du compte consulté, donc probablement non activé chez nous |
| Prix différents selon le client | Prix pro et particulier, prix personnalisés | Article « Attribuer différents tarifs aux clients » ; prix de vente par produit |
| Facturation, avoirs, relances | Oui | Oui (avoir de trois façons, relance, proforma) |
| Prix et factures pour le compte des producteurs | Non | Oui (commissions et prestations en pied de facture) |
| Adhésions, programme de fidélité, points de ramasse | Adhésions et cagnottes (AMAP) | Gestion des adhésions, programme de fidélité, points de ramasse |

Nuance sur la boutique : OTF la présente comme une fonction centrale. Chez nous, la boutique de Socleo existe mais sa qualité d'usage n'a pas été jugée.

## 3. Défauts d'ergonomie constatés
**Zandoly**
- Aucune aide intégrée (seulement « À propos » et « Raccourcis clavier »).
- Rapports lents (jusqu'à environ 10 secondes).
- Référentiel très dupliqué : mêmes produits en variantes (RHD, TRANSFO, PALOX, étiquette EAN, Conversion, HL), source d'erreur de saisie.
- Une offre soumise n'est plus modifiable ; l'administrateur corrige les prix après coup.
- Le tableau de lignes d'une offre n'apparaît qu'après un premier enregistrement.
- Colonne « Ventes » non alimentée : aucun lien avec Socleo.

**Socleo**
- Un écran de commandes à cinq vues, plusieurs listes de dates et de montants, de nombreux filtres : il faut tout régler avant de lire.
- Actions cachées dans « Autres » et « Sélectionnez une action ».
- Import de commandes : création seulement, doublon si on réimporte, pas d'annulation.
- Import de produits : option de suppression définitive à un clic de distance.
- Commande facturée : plus modifiable ; annulation seulement par avoir.
- Inventaire du matin à dater de la veille (règle invisible à l'écran).
- Comptabilité absente du menu du compte consulté.

## 4. Clics et pièges pour les tâches courantes (estimations)
| Tâche | Parcours aujourd'hui | Clics estimés | Pièges |
|---|---|---|---|
| Recopier la mercuriale dans Socleo, 3 fois par semaine | Zandoly : Mercuriale, choisir la date, lire ; Socleo : Nouvelle commande, client, date, filtres produits, quantité ligne par ligne, Détail, Valider | dizaines à centaines selon le nombre de lignes | variante de produit confondue, référence différente entre outils, double saisie |
| Importer des commandes par fichier | Télécharger le fichier vierge, remplir, Autres, Importer | environ 8 hors remplissage | réimport = doublons ; pas de test de fichier indiqué |
| Corriger une commande | Commandes, filtres, crayon jaune, modifier, valider | 6 à 10 | impossible si facturée |
| Dupliquer une commande | cocher, action, Dupliquer, date, tarif, quantités, cible, valider | 8 à 10 | tarif du jour ou d'origine, mauvaise cible |
| Faire un inventaire | Stock, État de stock, cocher, Saisir un inventaire, date, saisir, valider | 8 et plus | date du matin, produits non cochés |
| Éditer les bons de livraison d'une tournée | Commandes, Vue client, date, écran dédié, ordonner, enregistrer, éditer, tarification | 10 environ | client « non livré » exclu sans avertissement visible |
| Faire un avoir | trois voies selon le cas | 6 à 12 | mauvaise voie choisie |
| Saisir une offre (ferme) | Zandoly : Saisir une offre, date, débouché, Enregistrer, ajouter chaque ligne, soumettre | 6 + 3 par ligne | offre figée après soumission |

À mesurer : refaire ces parcours avec Romain en comptant clics, écrans et temps, puis comparer avec la cible du module.

## 5. Les trois reproches de François, et la réponse visée
1. **Procédure complexe, erreur facile.** Réponse : un seul écran par tâche, vérifications avant envoi (doublon, variante de produit, facture déjà émise), jamais d'option destructrice.
2. **Trop de clics pour la moindre action.** Réponse : mesurer le nombre de clics des tâches ci-dessus et se fixer une cible chiffrée.
3. **Zandoly et Socleo non connectés.** Réponse : une seule source (OTF et le module), la recopie disparaît ; en transition, fichier d'import préparé et contrôlé par un humain.

## 6. Vérifications faites le 14/11/2026 (documentation et feuille de route d'OTF)
Méthode : documentation officielle d'OTF (31 pages lues par mots-clés), FAQ, page des fonctionnalités, feuille de route publique, écrans de la ferme de test (vide). Le site de démonstration d'OTF est indisponible (fermé aux robots). **Aucune vérification en saisie** : une vente ne peut pas être supprimée.

| Point | Résultat |
|---|---|
| Stock par lot et DLC | Lots : prévus, priorité élevée. DLC : aucune mention. Stock : « disponibilités » dans les catalogues et un stock principal ; imputation du stock sur toute vente prévue (priorité élevée). Pas d'alerte de rupture trouvée. |
| Tournées, chargement, livraison mobile | Rien dans la documentation ni la feuille de route. Export PDF des ventes du jour seulement. |
| Emballages consignés | Aucune mention. |
| Boutique collective : marge | Aucune mention. |
| Boutique collective : facture par ferme | Aucune mention ; chaque producteur facture ses propres ventes. À confirmer auprès d'OTF. |
| Boutique collective : frais de livraison | Impossible (limite documentée), comme le choix du mode de paiement. |
| Facture fournisseur | Aucune mention. |
| Duplication de commandes | Aucune mention. |
| Export des données d'OTF | CSV de la plupart des données, dans Paramètres, « Exporter les données ». |

## 7. Conséquences pour le module complémentaire
- À construire par nous : offres et planification collectives, mercuriale, marge et facture pour le compte des fermes, tournées et livraisons, emballages consignés, lots et DLC avec alertes, duplication de commandes.
- Risque : OTF dit ne pas prendre de demandes de fonctionnalités et conseille de ne pas l'utiliser si une fonction structurante manque. Le module doit donc vivre à côté, via l'API (100 appels par jour avec Gestion), sans compter sur OTF pour ces fonctions.
- Question à OTF : faut-il compter sur les lots (priorité élevée) pour les prochains mois ? À poser à l'étape 10.
- Limite : certaines fonctions peuvent exister sans être documentées ; seule la démonstration en saisie, avec accord d'OTF, le dirait.
