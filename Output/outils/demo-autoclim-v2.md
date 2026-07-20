# Démo AutoClim v2 — le premier client pilote (deadline dure : 18/08)

*Kit v2 · 20/07/2026. AutoClim passe de « prospect démo vocale » à **candidat client pilote n°1 de la réactivation**. Contexte : garage clim à Joué-lès-Tours, gérant seul, injoignable au téléphone, SATURÉ en haute saison — donc l'angle est no-show/tri/étalement, jamais le volume. Atout : relation existante (Karim est client).*

## Ce qui change vs le plan du 06/07
| Avant (v1) | Maintenant (v2) |
|---|---|
| Démo = agent vocal qui répond aux appels | Démo = **diagnostic réactivation + anti-lapins sur SES clients** (le vocal en option « et ensuite ») |
| Email + Loom ≤ 2 min, CTA « appelez le numéro » | **Option A : visite en personne** (relation existante !) · Option B : email + Loom si pas de visite avant le 18/08 |
| Build : agent vocal ElevenLabs/Twilio (2-3 j, SAV risqué) | Build : **workflow réactivation v1** (import CSV → dormants → messages → envoi) — plus simple, réutilisable pour TOUS les clients suivants |
| Test d'écoute ElevenLabs = juge de paix | Reporté en phase 2 (avant le premier client vocal) — **ne bloque plus rien** |

## Le déroulé
### Option A — la visite (recommandée : Karim est un client, pas un démarcheur)
Passer en fin de matinée (9h30-11h30) : « Salut [prénom] — tu te souviens, j'avais galéré à te joindre pour ma clim. Je me suis mis à mon compte sur un truc : j'aide les garages du coin à faire revenir leurs clients perdus et à éviter les lapins. Comme t'es débordé, t'es exactement le profil. Tu me sors ta liste clients — ton logiciel sait faire un export — et je te montre gratuitement combien dorment. Si ça te plaît, t'es mon client fondateur avec le tarif qui va avec. Si non, tu m'auras aidé à roder le truc et je t'offre le diagnostic quand même. »
→ Dérouler le [script d'audit](script-audit-gratuit.md) en mode saturé (lapins + tri, PAS le volume) → engagement confidentialité signé → export récupéré → restitution sous 72 h.
### Option B — l'email du 18/08 (si la visite n'a pas eu lieu)
Email court + **Loom ≤ 2 min, voix off** : écran = calculateur onglet « Je suis débordé » rempli avec des chiffres de garage type, puis l'[exemple de rapport mensuel](exemple-rapport-mensuel.md). Message : « Je t'ai préparé ça en pensant à ton garage. Réponds-moi et je te fais le même diagnostic sur TON fichier — gratuit, 15 minutes de ton temps en tout. » Relance unique J+4 (SMS : « T'as vu mon mail ? Je passe te montrer ça quand tu veux »).

## Ce que BOS construit (semaines du 4 et du 11/08 — timeboxé, ~2 h/j de créneaux Karim pour valider)
1. **Workflow réactivation v1** (le cœur réutilisable) : import CSV (n'importe quel export DMS/caisse) → détection dormants (>12-14 mois) + échéances (révision ~12 mois, CT 24 mois) → génération des messages personnalisés par lots (validés par Karim avant envoi — jamais d'envoi auto en v1) → envoi via routeur SMS FR (~0,04 €/SMS) → log des réponses/STOP.
2. **Le template de diagnostic** (la restitution de l'audit) : 1 page — nb dormants, top échéances, CA récupérable prudent/plein, la liste des 20 premiers à rappeler.
3. **La maquette de rapport mensuel AutoClim** personnalisée (à partir de l'[exemple](exemple-rapport-mensuel.md)).
4. Le Loom option B (script écrit par BOS, enregistré par Karim en voix off — 2 min).
**Ce qu'on NE construit PAS maintenant** : l'agent vocal (phase 2), l'anti-no-show automatisé complet (v1 = confirmations manuelles-assistées le premier mois, automatisées ensuite).

## Jalon & critères
- **18/08 : AutoClim a reçu la proposition** (visite faite OU email envoyé) — deadline dure, inchangée.
- Succès pilote : export obtenu → diagnostic livré → **pilote fondateur signé (290 € setup + 149 €/mois)**. Premier client = cadre engagé (le moteur de Karim) + terrain d'apprentissage du delivery avant la tournée de septembre.
- Si AutoClim décline : aucune gravité — le diagnostic rodé sert tel quel pour la tournée 1 (fiche de tournée, 14 garages dans sa zone). Consigner la raison exacte (prix ? données ? pas de douleur ?) dans le tracker.
