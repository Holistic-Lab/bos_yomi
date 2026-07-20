# Passe 1 — Carte des automatisations IA par vertical PME de proximité
*Fable, 20/07/2026. Survol de cadrage (5 agents de recherche web parallèles). À rapporter à BOS pour décider la présélection. Passe 2 non lancée.*

## 1. Tableau maître

| Vertical | Top automatisations vendables | Signal demande | Potentiel récurrent | Produit d'ancrage candidat | Maturité digitale gérant | Facilité de vente estimée |
|---|---|---|---|---|---|---|
| **Plombiers-chauffagistes** | Relance devis J+3/J+7 · avis Google post-chantier · réception d'appels (acquis 18/07) · relance impayés | **Fort** (écosystème SaaS payant dense = VÉRIFIÉ) | **Fort** (flux continu devis/avis/appels) | Bundle relance devis + avis Google (ou agent vocal, acquis 18/07) | Faible-moyenne ; **délègue** | **Bonne** — mais SaaS 25-90 €/mois couvrent la fonction → vendre le clé-en-main, pas la feature |
| **Électriciens** | Identique plombiers (mêmes vendeurs, mêmes briques) | **Fort** | **Fort** | Idem plombiers | Idem | Idem — **fusionner en un segment « artisan BTP »** |
| **Garages auto/clim** | Rappel entretien/révision sur base clients · anti-no-show · avis (Custeed occupe le haut de marché) | **Moyen** (preuves surtout SUSPECT, sources vendeurs) | **Fort** (campagnes continues sur base clients) | Rappel entretien/révision automatique (« X clients dormants = Y € », démo chiffrable) | Moyenne ; équipé DMS → **comparateur** | **Moyenne** — cibler les indépendants, angle rétention pas acquisition |
| **Auto-écoles** | Anti-no-show (rappel + reconfirmation + refill de créneau) · relance prospects · avis | **Moyen-fort** (douleur no-show reconnue par le métier lui-même, pas que par des vendeurs) | **Fort** (flux continu d'élèves) | Système anti-no-show intelligent (au-dessus des packs SMS bruts) | Moyenne ; habitué au logiciel métier → comparateur | **Moyenne** — rappel SMS déjà commodifié (Codes Rousseau, Ornikar Pro) → différenciation à prouver |
| **Boulangeries / bouche** | Agent commandes spéciales (gâteaux/traiteur) + acompte · fidélité/SMS · click&collect · avis | **Moyen mais trou le plus large** : aucun SaaS dominant | **Moyen-fort** (agent + campagnes ; setup one-shot bundlable) | **Agent IA commandes spéciales WhatsApp/formulaire + acompte + alerte production** | **La plus faible** ; délègue nettement | **Bonne sur le closing, cycle plus lent** (éducation, confiance) |
| **Restaurants / bars** | Avis Google + relance post-visite · fidélité/SMS · anti-no-show (capté par Zenchef/TheFork) | **Fort mais encombré** | **Fort** (flux d'avis continu) | Gestion avis Google + relance post-visite (éviter la résa : Zenchef/TheFork gagnent) | Moyenne-haute ; déjà équipé, **sur-sollicité** par les commerciaux SaaS | **Moyenne** — demande réelle mais concurrence commerciale intense |
| **Coiffure / beauté** | Réactivation clientes dormantes (seul interstice) · fidélité créative | **Fort mais quasi totalement capté par Planity** (~80 €/mois) | Récurrent structurel mais occupé | Réactivation clientes dormantes par SMS/IA | Moyenne ; délègue mais **déjà équipé** | **Faible** — objection « j'ai déjà Planity » quasi systématique |
| **Paysagistes / extérieur** | Relance devis · avis post-chantier · **relance saisonnière d'entretien** (aucun SaaS dédié = terrain ouvert) · qualification entrante | **Moyen** (pain admin VÉRIFIÉ — Observatoire BTP : ~30 % du temps ; ROI vendeurs = SUSPECT) | **Fort** (relances continues + campagne saisonnière) | Relance devis + avis Google ; option relance saisonnière | Faible (<10 % usage IA, VÉRIFIÉ) ; délègue | **Bonne mais lente** — extension naturelle du segment artisan BTP |
| **Agences immo locales** | Première réponse + qualification leads <5 min · avis Google (Qualitelis vise les réseaux) · relances | **Moyen, très bruité** (stats quasi toutes SUSPECT) | Moyen-fort (leads continus) | Qualification/première réponse leads ; ou avis Google en pied-de-porte | **La plus haute** → risque comparaison + « je le fais avec ChatGPT » ; annonces/estimation/pige déjà couverts | **Faible-moyenne** |

## 2. Axe maturité digitale — verdict sur la croyance de Karim

**La croyance « le gérant non-tech est plus dur à convaincre » est plutôt DÉBUNKÉE côté closing — verdict NUANCÉ, confiance MOYENNE.**

- Preuve la plus solide (DGE/BCG/EY, VÉRIFIÉ) : le profil « Prudent » (pas à l'aise avec le numérique) **demande lui-même** en priorité « une mise en relation avec des prestataires de confiance » (40 %) — il ne veut pas apprendre, il veut déléguer. C'est exactement l'offre clé-en-main de Karim.
- Nuance : ce profil achète sur la réduction de coût/temps (« je m'occupe de tout, ça te fait gagner X € »), pas sur la croissance ; son ambition de développement est plus faible (Sceptiques Bpifrance : 38 %, surreprésentés dans le BTP).
- La contre-thèse (le digitalisé compare, négocie, fait lui-même) reste **SUPPOSÉE** — plausible, zéro preuve directe. Convergence qualitative des agents verticaux : garages/auto-écoles/immo (équipés d'un logiciel métier) ressortent partout « comparateurs », BTP/boulangerie « délégants ».
- **Le facteur réellement décisif n'est pas la maturité : c'est la douleur ressentie + la confiance dans le prestataire local** (81 % préfèrent un prestataire FR, 56 % un local — DÉCLARÉ). Le canal audit gratuit en face-à-face est validé pour tous les profils.
- Distinction utile : le garagiste type n'est pas « illectronique » (7 % des artisans, INSEE), il est « mal à l'aise » (1/3 des dirigeants TPE-PME) — proscrire le jargon IA, pas simplifier le fond.
- **À tester empiriquement sur les 20 premiers audits à Tours** — aucune donnée de closing/churn par profil n'existe (catégorie trop récente).

## 3. Produits d'ancrage candidats (tous verticaux)

Rappel du filtre économique (Agent D, structurant) : **l'abonnement tient quand il y a du volume traité en continu (appels, SMS, avis) ou de l'hébergement/itération — pas quand c'est un workflow figé** (qui se fait résilier, ou pousse au one-shot : AgentLibre vend « zéro abonnement » comme argument). Structure FR observée : setup 800-1 200 € + 80-300 €/mois. Les briques existent en self-serve à 29-49 €/mois → la marge est dans le service, jamais dans la licence.

1. **Bundle relance devis + avis Google (artisan BTP + paysagistes)** — valeur directe (« récupère des devis perdus »), démo live (le SMS part devant le gérant), récurrent naturel. Concurrent : Relencio 29-49 €/mois self-serve → se vendre comme clé-en-main intégré.
2. **Réceptionniste/agent vocal IA flat-rate (artisan BTP)** — le modèle d'abonnement le plus robuste du panorama (sweet spot anglo 149-199 $/mois flat ; FR 49-350 €/mois). Déjà validé par la passe téléphone du 18/07.
3. **Agent IA commandes spéciales boulangerie/traiteur (WhatsApp + acompte + alerte production)** — douleur non résolue (cahier/téléphone), zéro SaaS dominant, démo très impressionnante, récurrent.
4. **Rappel entretien/révision garage sur base clients** — démo chiffrable en euros dès l'audit ; récurrent.
5. **Avis Google + relance post-visite restaurants** — récurrent, sans toucher à la caisse ni à la résa ; marché plus encombré.

## 4. Recommandation de présélection (3-4 verticaux pour la Passe 2)

1. **Artisan BTP élargi (plombiers-chauffagistes + électriciens + paysagistes)** — le seul segment fort sur les DEUX lentilles (téléphone 18/07 + large 20/07), profil délégant, trois ancrages possibles (vocal, relance devis+avis, saisonnier). À traiter comme UN segment go-to-market.
2. **Boulangeries / commerces de bouche** — **la surprise de la passe** : faible au téléphone, mais remonte fort sur la lentille large (aucun SaaS dominant = vrai trou pour du fait-pour-lui, gérant le plus délégant, ancrage original et démoable). Contrepartie à vérifier : volume réel de commandes spéciales et cycle de vente.
3. **Garages indépendants (angle rétention uniquement)** — base clients dormante = démo chiffrable en euros ; mais gérant comparateur et preuves faibles. À creuser pour confirmer ou éliminer.
4. **Auto-écoles** — douleur no-show reconnue par le métier lui-même (crédibilité au-dessus de la moyenne) ; mais brique SMS commodifiée → la Passe 2 doit tester si « l'orchestration au-dessus du pack SMS » se vend vraiment.

**Écartés** : coiffure/beauté (Planity a tout commodifié — le plus risqué), agences immo (gérant le plus « comparateur/DIY », angles principaux déjà refermés), restaurants en option basse (demande réelle mais segment sur-sollicité — repêchable si les 4 premiers déçoivent).

**Autres surprises** : l'immobilier, intuitivement attractif (digitalisé, ticket élevé), ressort défavorable — la maturité joue contre le fait-pour-lui. Signal bonus (Agent A, non vérifié) : vétérinaires/toiletteurs comme vertical hors liste à fort potentiel — à trancher avec Karim.

## 5. Trous à combler en Passe 2

- **Densité locale** : combien de prospects réels par vertical à Tours + agglo (annuaires, terrain) — rien chiffré localement dans cette passe.
- **Économie de l'ancrage** : coût de livraison réel (n8n, téléphonie, LLM, hébergement) vs prix vendable → marge et MRR atteignable par client ; combien de clients pour 3-5 k€/mois.
- **Churn/rétention** : zéro donnée sur la durée de vie réelle des abonnements d'automatisation PME — le plus gros angle mort du modèle MRR.
- **Boulangerie** : valider par entretiens terrain le volume/douleur des commandes spéciales avant d'investir (preuves actuelles = blogs d'agences, SUSPECT).
- **Auto-écoles/garages** : la différenciation au-dessus des briques commodifiées (Codes Rousseau, Custeed) est-elle vendable ou cosmétique ?
- **Concurrence locale à Tours** : existe-t-il déjà des agences IA locales actives sur ces verticaux ?
- **Profil acheteur** : les deux hypothèses (Prudent = facile à closer sur le coût ; Réceptif = risque DIY) à tester sur les 20 premiers audits — aucune preuve ne les tranche.
- **Fait notable transverse** : aucune preuve publique vérifiable d'un indépendant FR vivant d'un MRR d'automatisations IA pour PME locales (la traction vérifiée est chez des startups VC visant l'entreprise/la santé). Marché jeune : opportunité réelle, mais le chemin n'est pas balisé — prudence sur les promesses des vendeurs de formations.
