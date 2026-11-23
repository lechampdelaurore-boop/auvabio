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

## D-006 — Abandon de la mesure des clics avec Romain (14/11/2026)
La mesure du nombre de clics avec Romain n'est plus prévue. Les estimations de clics du comparatif restent des estimations tirées de l'aide et des écrans, non mesurées.
Raison : François a demandé d'y renoncer.
Tranché par : François.

## D-007 — Transcrire les vidéos en local uniquement (23/11/2026)
Les vidéos laissées par les anciens cadres sont transcrites sur le PC de François (faster-whisper, modèle large-v3) ; aucune vidéo, audio ni transcription n'est envoyé à un service externe. Audio, transcriptions et images restent hors dépôt (Documents\AUVABIO-prive). Seules les procédures épurées (sans nom, client, producteur ni prix) entrent dans le dépôt.
Raison : les vidéos contiennent des données réelles et des passages sur le personnel.
Tranché par : François (accord sur l'installation locale, 23/11/2026).

## D-008 — Captures d'écran gardées hors dépôt (23/11/2026)
Les captures d'écran des outils ne sont pas déposées dans le dépôt public. Elles restent sur le PC de François (Documents\AUVABIO-prive\captures). Les procédures du dépôt renvoient à la capture par un repère (nom de fichier, sans contenu) ; Romain reçoit les captures avec son kit, hors dépôt.
Raison : les écrans montrent des données réelles ; le flou ne suffit pas à écarter tout risque.
Tranché par : François.

## D-009 — Recoupement des procédures avec la documentation (23/11/2026)
Chaque procédure tirée d'une vidéo est recoupée avec l'aide en ligne et les manuels de Socleo et la carte de Zandoly ; un tableau « Recoupement » (confirmé / à corriger / non établi) figure en bas de chaque procédure. Une procédure recoupée mais non essayée sur le vrai outil reste « à vérifier ». Les exemples chiffrés issus des vidéos sont remplacés par des exemples fictifs (aucun volume réel dans le dépôt).
Raison : la documentation est une source indépendante des vidéos, mais elle décrit l'offre complète de Socleo, pas ce qui est activé chez AUVABIO.
Tranché par : François (demande du 23/11/2026).
