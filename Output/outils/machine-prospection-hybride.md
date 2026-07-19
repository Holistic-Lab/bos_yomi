# La machine de prospection hybride — terrain (Karim) × data/IA (BOS)

*Rédigé le 19/07/2026. Principe : Karim ne fait QUE ce qui exige un humain de confiance (la poignée de main, la conversation, la démo) ; BOS fait tout le reste (données, ciblage, préparation, suivi, relances). Respecte l'acquis n°2 : on n'automatise l'acquisition à grande échelle qu'APRÈS les 2 premières ventes manuelles — cette machine prépare et outille le manuel, elle ne le remplace pas.*

## Vue d'ensemble du flux

```
[BOS] Listes SIRENE scorées (fait ✅)
   → [BOS] Enrichissement par lots (web/avis/site) 
   → [BOS] Tournées géographiques préparées (10-12 portes/matinée)
   → [KARIM] Passage 1 terrain (contact + calculateur, 5 min/porte)
   → [BOS] Log tracker + fiche de suivi + rappels
   → [KARIM] Passage 2 (démo vivante sur numéro de démo)
   → [BOS] Contrat pré-rempli + onboarding technique complet
   → [KARIM] Signature + encaissement
   → [BOS] Rapport ROI mensuel automatique au client (anti-churn)
```

## Étape par étape — qui fait quoi

### 1. Ciblage (BOS — fait)
4 CSV scorés dans `Output/prospection/` : plombiers-chauffagistes (315 solos en agglo), électriciens (364), auto-écoles (58), garages (279). Score : agglo +3, solo probable +3, entrepreneur individuel +1, établi >5 ans +1.

### 2. Enrichissement par lots (BOS — à la demande)
Avant chaque tournée, Karim dit : « prépare-moi 12 plombiers autour de [quartier/commune] ». BOS produit la **fiche de tournée** : pour chaque prospect — nom, dirigeant, adresse, ancienneté, présence web (site ? fiche Google ? avis ? note ?), signal d'appétence (pas de site + bons avis = déborde de travail et rate des appels = cible en or), et l'itinéraire logique. *(Enrichissement par recherche web publique uniquement — pas de scraping en violation de CGU.)*

### 3. La tournée (Karim — 1 matinée = 10-12 portes)
Playbook en poche, calculateur sur le téléphone, cartes de visite. Format : passage 1 court (5 min), noter à chaud 3 infos dans le téléphone (vocal suffit — BOS transcrit dans le tracker).

### 4. Suivi automatisé (BOS)
Après chaque tournée : mise à jour du tracker, fiches de relance (« repasser jeudi », « attend ses comptages d'appels »), SMS/email de suivi rédigés prêts à envoyer, préparation du passage 2.

### 5. La démo vivante (BOS construit, Karim montre)
Un numéro de démo par vertical (assistant configuré plombier / électricien / auto-école / garage). Le prospect appelle LUI-MÊME et juge. Build : timeboxé, dérivé du build AutoClim (même socle, prompts métier différents).

### 6. Conversion (mix)
BOS : contrat type pré-rempli (clause indexation, sans engagement pilote), process d'installation documenté (renvoi conditionnel = 1 code à taper sur le téléphone du gérant, ~2 min). Karim : la signature et la relation.

### 7. Rétention (BOS — dès le client n°1)
Rapport mensuel automatique : « ce mois-ci : X appels pris en débordement, Y transmis, Z rappelés → estimation récupérée : N € ». C'est la parade au churn (risque n°1 du secteur) ET l'argument de renouvellement. Instrumenté dès J1.

## Canaux complémentaires (après les 2 premières ventes, pas avant)

- **Auto-écoles** : démarchage possible par téléphone/email (elles ont un secrétariat léger mais une adresse mail) — séquence BOS 100 % rédigée, Karim valide par lot.
- **Prescripteurs locaux** : réseau d'Agathe (bars/commerçants de Tours — bouche-à-oreille), président de quartier Place Plume, MAME (démos/visibilité tech locale). À activer quand il y a 2-3 références clients à montrer, pas avant.
- **Avis Google + fiche locale** : dès le premier client pilote (contrepartie contractuelle du setup offert).
- **La vague réglementaire du 02/08/2026** (annonce IA obligatoire) : angle de contenu local unique — « le seul service de standard assisté de Touraine déjà conforme ».

## Cadence type (à partir de septembre, matinées libres)

- **Lundi** : revue tracker avec BOS (15 min) + BOS prépare les tournées de la semaine.
- **2-3 matinées** : tournées terrain (10-12 portes) + passages 2 chez les chauds.
- **Vendredi** : bilan de semaine, BOS met à jour le funnel, décision d'itération (pitch ? vertical ? offre ?).
- **Fenêtre Luna (jusqu'au 19/08)** : préparation uniquement (démos, one-pager, test d'écoute, 2-3 portes d'essai max pour roder le pitch — dont AutoClim).

## Le gate, rappel

**20 démarchages passage-1 complets** → lecture à la grille de diagnostic (ciblage / douleur / offre / confiance) → GO (≥1 pilote signé) ou pivot. Tout est consigné dans `tracker-demarchage.csv`.
