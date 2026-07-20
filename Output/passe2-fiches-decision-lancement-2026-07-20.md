# Passe 2 — Fiches de décision & reco de lancement
*Fable/BOS, 20/07/2026. Base : 5 axes de recherche (économie des ancrages, validation boulangerie, churn/MSP, concurrence locale + outsider, densité locale par comptage SIRENE direct). Statuts VÉRIFIÉ/DÉCLARÉ/ESTIMATION respectés dans les rapports sources. Décision finale : Karim.*

---

## L'ENSEIGNEMENT CENTRAL DE LA PASSE 2

**Le produit gagnant n'est pas un vertical — c'est une MÉCANIQUE : « réactivation et rappels intelligents sur la base clients existante ».** Elle a gagné l'arbitrage économique (30/35, meilleur ratio marge/effort, seule équation où la capacité solo n'est jamais la contrainte), et elle est la seule **démoable en 10 minutes devant le gérant avec SES propres données** (« ton export clients → 340 clients dormants → X € de CA récupérable » — sa donnée, pas une promesse). Elle se décline par vertical :
- **Garage** → rappel révision/entretien + anti-no-show (créneau perdu = 80-150 €).
- **Plombier-chauffagiste** → rappel d'**entretien annuel de chaudière** (obligation légale pour le client final = récurrence structurelle en béton) + relance devis.
- **Paysagiste** → relance saisonnière des contrats d'entretien (en annuel pour neutraliser le churn hivernal).

Le **vocal** reste vrai mais devient le **produit premium de phase 2** (forte douleur, mais SAV 1,5 h/client/mois → plafond ~20-30 clients, coût variable qui mord, risque de réputation en v1). On le vend aux clients déjà conquis, pas en porte d'entrée.

---

## FICHES DE DÉCISION PAR VERTICAL

### ① GARAGES INDÉPENDANTS — verdict : **GO — PORTE D'ENTRÉE N°1**
- **Densité** : 355 en agglo Tours, ~279 solo-TPE ; ~20 sites de chaînes à retrancher (Norauto 7, Speedy 6, Midas 3, Feu Vert 2-3) → **~260 cibles indépendantes**. Largement assez pour 15-25 clients.
- **Ancrage** : réactivation base clients dormante (rappel révision, relance CT, anti-no-show). Vainqueur du comparatif économique (30/35).
- **Économie** : coût ~6 €/client/mois · prix vendable 129-179 €/mois + setup · marge éco ~113 €/client · maintenance 0,5 h/mois · **3 k€ ≈ 21-26 clients, 5 k€ ≈ 35-42 — plafond de capacité (~60-100) jamais atteint.**
- **Churn** : parade = rapport mensuel chiffré en euros + 2e automatisation dès le mois 2-3.
- **Risques** : gérant « comparateur » (équipé DMS) → neutralisé par la démo chiffrée sur SES données ; hypothèse critique = base clients exportable (vrai chez la majorité via DMS).
- **Atout de départ** : AutoClim = pilote naturel (saturé → angle no-show/tri, exactement cette mécanique).

### ② ARTISAN BTP ÉLARGI (plombiers-chauffagistes, électriciens, paysagistes) — verdict : **GO — VERTICAL N°2, même mécanique**
- **Densité** : la plus grosse réserve de chasse — agglo : 369 plombiers (315 solos) + 408 électriciens (364 solos) + 226 paysagistes (191 solos) ≈ **~870 cibles solos**.
- **Ancrage décliné** : plombier-chauffagiste = rappel entretien chaudière annuel (récurrence légale) + relance devis · paysagiste = relance saisonnière EN ANNUEL · électricien = relance devis + avis.
- **Arbitrage des 3 ancrages BTP initiaux** : vocal = premium phase 2 (25/35) · relance devis+avis = add-on à +30 €/mois, jamais standalone (24/35 — SaaS freemium DropAvis/Relencio à 39 € plafonnent le prix) · saisonnier paysagiste = 2e temps en annuel (24/35). **La déclinaison « rappels sur base clients » transversale bat les trois.**
- **Risque spécifique** : la base clients de l'artisan est souvent moins structurée que le DMS d'un garage (carnet, Excel sale) → setup plus long (nettoyage de données), à facturer.

### ③ BOULANGERIE / COMMERCE DE BOUCHE — verdict : **NO-GO (enterré)**
- Le trou de marché n'existe pas : Kazalendar vend le produit exact (agent WhatsApp commandes + acompte) à **9,99 €/mois** ; les caisses installées (Toporder, DGsys, Crisalid) couvrent commande spéciale + acompte + bon de production ; l'économie ne boucle pas (~100 clients nécessaires à 49 € face à un comparable à 10 €, plafond solo ~30-50, support de pic intenable) ; la douleur n'est prouvée que par des vendeurs (SUSPECT).
- Porte résiduelle : service done-for-you saisonnier « je gère tes commandes de fêtes » vendu cher 2-3 pics/an — à ne considérer QUE si un boulanger l'exprime spontanément en audit. Les 3 questions terrain sont consignées dans le rapport boulangerie.

### ④ VÉTO / TOILETTEUR — verdict : **ÉCARTÉ comme porte d'entrée, extension possible plus tard**
- Garde-fou réglementaire : **levé** (pas d'article 9 RGPD pour l'animal, pas de HDS, l'Ordre contraint le vétérinaire pas le prestataire — messages factuels non promotionnels obligatoires).
- Mais : **véto localement consolidé** (sur ~45 cliniques agglo : Sevetys 9 + Vetloire 5 + Mon Véto ≥1 — et Vetstoria appartient au groupe Santévet qui possède Vétocom, le logiciel métier central → défendabilité structurellement faible) ; **toiletteur trop étroit** (~20-25 salons en agglo — impossible d'y bâtir 15-25 clients) et déjà servi (Planity, DogPlanner).

---

## RÈGLES DE DESIGN DE L'OFFRE (anti-churn, benchmarks MSP)

Sans design : churn attendu ~26-40 %/an (régime « service facilement coupé »). Avec ces règles : cible **~18-24 %/an, durée de vie client 30-50 mois** (régime retainer).
1. **Rendre le travail visible** : notification à chaque action + **rapport mensuel chiffré en euros** (clients « qui ne voient rien » : churn +60 %).
2. **Flux critique, pas confort** (relances = argent visible ; jamais de gadget).
3. **Setup PAYANT, jamais offert** (finance l'acquisition, protège la fenêtre à risque des 9 premiers mois). ⚠️ **Révise le one-pager du 19/07 (« setup offert »)** → pilote fondateur : setup réduit (ex. 290-490 €) mais jamais gratuit.
4. **Time-to-value < 7 jours** : première victoire mesurable la 1re semaine (70 % du churn se joue à 90 jours ; TTV<7 j = churn ÷2).
5. **Flat mensuel tout-inclus** par flux, jamais à l'heure ni à l'usage.
6. **Montée en gamme** : 2e automatisation dès le mois 2-3, viser 3+ par client (churn -60 % chez les clients multi-projets).
7. **Sans engagement** + rétention par la preuve (le setup payant remplace le lock-in).
8. **Visite trimestrielle locale** (QBR de TPE) — l'arme que les SaaS n'ont pas ; 16 % des TPE partent en se sentant négligées.
9. **4 signaux d'alerte churn** instrumentés dès J1 (0 action utile 2-4 sem · rapports non lus · question prix/résiliation · silence d'un trimestre).
10. **Offre simple calibrée TPE** (une chose, prix bas, contact humain — la sur-offre fait churner).
11. **Cohortes 1/3/6/12 mois** suivies dès le premier client ; sur-investir les 90 premiers jours.

---

## RECO DE LANCEMENT

**Produit d'ancrage : « Réactivation clients + rappels intelligents » — lancé sur les GARAGES d'abord, décliné plombiers-chauffagistes ensuite.**
- **Offre pilote (à réviser depuis le one-pager 19/07)** : setup 290-490 € (jamais offert) + **129-149 €/mois sans engagement**, tout inclus : campagne de réactivation mensuelle, anti-no-show, rapport chiffré en euros, visite trimestrielle. Up-sell mois 2-3 : relance devis/avis +30 €, puis vocal premium 199-249 € pour les conquis.
- **Chemin chiffré** : 25 clients × ~140 €/mois ≈ **3,5 k€ MRR** + setups (~10 k€ cumulés la 1re année) — capacité solo OK (~15-25 h/mois de maintenance à terme).
- **Réconciliation des chantiers existants** :
  - **Kit vocal du 19/07** : listes SIRENE, calculateur ROI, playbook terrain, tracker → **tout reste valide** (mêmes cibles, même terrain). À adapter : le pitch d'entrée devient « audit + réactivation », le vocal passe en slide « et ensuite » ; le calculateur gagne un mode « base dormante ».
  - **AutoClim (deadline 18/08) : MAINTENUE et renforcée** — la démo devient « réactivation + anti-no-show sur TES clients » (plus simple à livrer qu'un agent vocal, plus impressionnante car chiffrée sur ses données), avec le vocal en option premium. AutoClim = client pilote idéal de la mécanique gagnante.
  - Conversation Kevin (marque blanche financement) : inchangée, pari latéral coût ~0.
- **Gate terrain (inchangé dans l'esprit)** : 20 audits gratuits en démarchage terrain → si < 2 pilotes signés, re-diagnostic (pas de RDV → ciblage/pitch · RDV sans vente → offre/prix · ventes sans rétention → produit).
- **Ce que seul le terrain tranchera** : le taux de gérants qui acceptent l'audit · l'accès réel aux exports de base clients · la willingness-to-pay à 129-149 € · le profil acheteur (prudent-délégant vs comparateur).

## Trous résiduels assumés
- Comptages électriciens/garages plafonnés à 1000 résultats scannés (cap API) — ordres de grandeur légèrement sous-estimés, sans impact sur les verdicts.
- Churn : benchmark TSIA (90 % rétention MSP) relayé, non consulté à la source primaire.
- Part exacte des garages avec DMS exportable : à mesurer sur les 20 premiers audits.
- Vétérinaires « solo probable » (37/45 agglo) : chiffre fragile — beaucoup d'inscriptions SIRENE individuelles de praticiens exerçant en réalité dans des cliniques employeuses (double comptage possible). Sans impact : le vertical est écarté, et cette fragilité va dans le sens de l'écartement (encore moins de cibles indépendantes réelles).
