# Décisions AUVABIO

## D-001 — Trois volets (8/11/2026)
Le projet comporte trois volets : A (assistant lecture seule pour Romain sur Zandoly et Socleo, recopie, veille des prix), B (documentation vivante : procédures avec captures, fiches visuelles), C (module sur mesure adossé à Ouvre ta ferme par son API, pour la planification et le stock collectifs).
Raison : le besoin immédiat est de combler les pertes d'information (A, B) ; C vise le manque durable.
Tranché par : François.

## D-002 — Ordre des volets (8/11/2026)
B et A d'abord (procédures perdues, assistant en lecture seule), puis automatisations A, puis cadrage de C (cahier des charges, accès API OTF, démonstration) avant tout code.
Raison : les procédures réelles sont à reconstituer ; on ne code pas sur des hypothèses.
Tranché par : François.

## D-003 — Dépôt privé (8/11/2026) — REMPLACÉE par D-004
Le dépôt GitHub était privé à sa création.

## D-004 — Dépôt public sous licence PolyForm Shield 1.0.0 (8/11/2026)
Le dépôt devient public, sous licence PolyForm Shield 1.0.0 (fichier LICENSE, avec la ligne « Required Notice » au nom d'AUVABIO, à confirmer). Aucune donnée réelle n'y est déposée : captures floutées ou de test, prix, noms et adresses hors dépôt, aucun secret.
Raison : économiser les minutes GitHub Actions (gratuites en dépôt public). François a été prévenu du risque et a choisi cette option.
Tranché par : François. Remplace D-003.

## D-005 — Extraire toutes les données de Socleo et Zandoly avant la bascule (14/11/2026)
Avant de quitter Socleo et Zandoly, une extraction complète de leurs données est faite pour ne rien perdre, puis transférée vers le nouvel outil (OTF et module). Elle se fait en lecture seule (exports, puis API si accordée). Les fichiers extraits restent hors dépôt, dans l'espace privé. Aucun transfert n'est écrit dans un outil sans validation humaine écrite. Voir ROADMAP étape 10 bis.
Tranché par : François.
