# One-pager — Offre V1 « service vocal de proximité » (draft BOS, 19/07/2026)

*Version interne : définit l'offre. Les blocs « côté client » sont prêts à copier dans un flyer / une page web / un email. Nom commercial à trancher par Karim — propositions en bas.*

## L'offre en une phrase (côté client)

> **« Plus jamais un client perdu parce que vous ne pouviez pas décrocher. »**
> Un assistant téléphonique qui répond quand vous ne pouvez pas, prend le besoin, le nom et le numéro, et vous envoie tout par SMS en une ligne. Installé, réglé sur votre métier et suivi par un professionnel de Tours.

## Ce que le client achète (V1 — périmètre volontairement minimal)

1. **Renvoi conditionnel** : l'assistant ne prend JAMAIS un appel que vous auriez décroché — il ne récupère que les appels déjà perdus (non-réponse ~20-25 s). Réversible à tout moment, aucun portage de ligne, rien à installer.
2. **Réponse 24h/24** au nom de votre entreprise : besoin, urgence, nom, numéro (répété), et pour les métiers concernés : véhicule / adresse / type de panne.
3. **Notification immédiate** : SMS/WhatsApp une ligne, numéro cliquable — vous rappelez en 30 secondes entre deux interventions.
4. **Option garage/atelier (mode débordé)** : confirmation et rappel de rendez-vous (anti-lapins) + tri des demandes (les grosses réparations signalées en priorité).
5. **Le service, pas le logiciel** : installation faite pour vous, réglages métier, ajustements le premier mois, un interlocuteur local joignable.

**Conformité** : l'appelant est informé qu'il parle à un assistant (réglementation européenne, applicable au 02/08/2026 — nous sommes en règle avant l'échéance). Enregistrements et données traités selon le RGPD, conservation limitée.

## Prix

| | Pilote fondateur (5 premiers) | Normal |
|---|---|---|
| Installation + réglage métier | **Offerte** | 990 € |
| Abonnement tout compris | **290 €/mois, sans engagement** | 290-350 €/mois selon volume |
| Engagement | Aucun — arrêt à tout moment | Sans engagement, préavis 1 mois |

Contrepartie pilote : un avis Google honnête + accord de référence locale. Contrat avec clause d'indexation en cas de hausse des coûts plateforme (transparence totale).

## La promesse chiffrée (à personnaliser avec le calculateur)

« Un seul chantier récupéré par mois — une chaudière, un dépannage, une inscription — et le service est remboursé plusieurs fois. On fait le calcul ensemble avec VOS chiffres, pas avec des statistiques. »

## Pour qui (ordre de priorité V1)

1. Plombiers-chauffagistes · 2. Électriciens · 3. Auto-écoles · 4. Garages/ateliers (mode débordé). 
Zone : Tours et agglo (déplacement en personne inclus). Hors zone : à distance, au cas par cas.

## Ce qu'on ne fait PAS en V1 (discipline)

Pas de prise de RDV calendrier complexe · pas de suivi d'état (« c'est prêt ? ») · pas de secteur santé (réglementation données de santé) · pas d'appels sortants de prospection · zéro accès aux systèmes du client (tout part de notre infra VERS ses canaux — rien à installer chez lui).

## Architecture (interne)

Stack pressentie : ElevenLabs Agents + Twilio + n8n self-hosted (~0,08 $/min ; coût de revient ~50 €/mois à 150 appels → marge ~83 % à 290 € MRR). Juge de paix avant tout engagement : le test d'écoute (protocole existant — statut à confirmer par Karim). Plan B : AirAgent marque blanche. La couche n8n + prompts + notifications nous appartient : la plateforme voix reste interchangeable.
Instrumentation dès J1 : « leads transmis vs rappelés » par client (= preuve de ROI mensuelle envoyée au client = anti-churn — le churn est LE risque n°1 documenté du secteur).

## Nom commercial — 3 propositions (à trancher par Karim)

1. **Standard Tourangeau** — ultra-local, dit exactement ce que c'est, imbattable en bouche-à-oreille local.
2. **DécrochePro** — bénéfice direct, marche au-delà de Tours si on scale.
3. **Holistic Lab — Accueil téléphonique** — sous la marque existante, zéro création, crédibilité de structure établie.
(Avis BOS : le n°1 pour le terrain local — un plombier de Joué-lès-Tours fait plus confiance au « Standard Tourangeau » qu'à un nom SaaS.)
