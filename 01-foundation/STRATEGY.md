# CHERRYPICK — Stratégie de Contenu & Exécution Multi-Plateforme

> **CE FICHIER EST LE PLAYBOOK D'EXÉCUTION DU COMPTE CHERRYPICK.**
> Il applique les mécanismes documentés dans 01-foundation/ALGORITHM_TIKTOK_2026.md au persona défini dans 01-foundation/PERSONA.md.
> TikTok est la plateforme de découverte principale. Chaque vidéo est cross-postée sur YouTube Shorts et Instagram Reels.
> Les stratégies de monétisation sont dans 01-foundation/MONETIZATION.md.
> Dernière mise à jour : 1 mars 2026

---

## 1. LE COLD-START PROBLEM — LANCER UN COMPTE À 0 FOLLOWERS

### Le défi

Le follower-first testing de 2026 signifie que les vidéos sont d'abord testées auprès des followers existants. À 0 followers, les premières vidéos seront testées sur un pool de 200-500 inconnus basé sur les signaux vidéo (texte, audio, hashtags). Si le test échoue → la vidéo meurt à 200 vues.

Les 2 premières semaines sont les plus critiques. Le compte n'a aucune autorité, aucun follower, aucun historique. Chaque vidéo est un dice roll.

### Stratégie de pré-lancement (Semaine -1, AVANT la première vidéo)

**Objectif : créer un minimum de présence et de signaux avant de publier.**

**1. Setup du profil**
- Username : @cherrypick (ou variante disponible)
- Bio : courte, punchy, immédiatement compréhensible. Exemple : *"Cherry-picking the truth you don't want to hear. 🍒 SaaS roasts & dev reality checks."*
- Photo de profil : le masque vénitien, reconnaissable même en miniature
- Lien : aucun pour l'instant (pas de conversion en Phase 1, focus 100% croissance)

**2. Infiltrer la niche AVANT de publier**
- Follow 30-50 comptes dev/builder/indiehacker actifs sur TikTok
- Commenter quotidiennement sur 20-30 vidéos dans la niche avec des commentaires QUALITATIFS et dans le ton CherryPick (sarcastique, punchline). Pas de "nice video 🔥". Des commentaires du type : *"200h of code, 0 users. Classic."* ou *"Another tutorial. Still 0 MRR."*
- Objectif : que les gens de la niche voient le nom CherryPick et cliquent sur le profil AVANT qu'il y ait du contenu
- Ces commentaires créent de la curiosité et des premiers followers organiques

**3. Préparer un stock de 7-10 vidéos**
- Ne PAS publier au jour le jour au début — avoir un buffer permet de poster régulièrement même si une génération Kling échoue
- Varier les personnages, garder le masque, tester différents styles de text overlay
- Sélectionner les 3 meilleures pour le lancement

### Stratégie de lancement (Semaine 1)

**Jour 1-3 : Rafale de lancement**
- Publier 1 vidéo par jour pendant 3 jours consécutifs
- Choisir les 3 vidéos les plus fortes du stock (hooks les plus provocateurs)
- Publier aux heures US prime (voir section 8)
- Immédiatement après publication : aller commenter sur 20+ vidéos dans la niche pour ramener du trafic vers le profil

**Jour 4-7 : Observer et ajuster**
- Analyser les métriques des 3 premières vidéos (completion rate, vues, engagement)
- Identifier quel style de hook performe le mieux
- Continuer à publier 1/jour
- Continuer les commentaires dans la niche (15-20/jour minimum)

### Objectif fin de semaine 1
- 50-200 followers (réaliste pour un lancement à froid)
- Au moins 1 vidéo qui passe le "200-view jail" (>500 vues)
- Identifier le style de contenu qui résonne le plus

---

## 2. OPTIMISATION POUR LE COMPLETION RATE

### Pourquoi CherryPick a un avantage structurel

Le seuil de viralité 2026 est de ~70% de completion rate. Le format CherryPick est naturellement optimisé pour ça :

- **Durée cible : 8-15 secondes** — plus c'est court, plus il est facile d'atteindre 70%+ de completion
- **Le texte overlay est lisible en 3-5 secondes** — le viewer reste pour le lire
- **La trend danse retient l'attention** — le mouvement empêche de scroller
- **Le masque crée de la curiosité** — élément visuel inattendu qui intrigue
- **Le loop naturel** — une vidéo de 10s qui boucle seamlessly = le viewer la regarde 2-3 fois sans s'en rendre compte = completion rate de 200-300%

### Structure optimale d'une vidéo CherryPick

```
FRAME 1 (0.0 - 0.5s) : HOOK VISUEL
├── Le texte overlay apparaît immédiatement (pas d'intro, pas de transition)
├── Le personnage masqué est visible
└── Le mouvement de danse commence

FRAME 2 (0.5 - 3.0s) : LECTURE DU TEXTE
├── Le viewer lit le texte roast/éducatif
├── Le mouvement continue (retient l'attention)
└── Le viewer décide de rester → open loop si le texte est provocateur

FRAME 3 (3.0 - 8.0s) : RÉTENTION
├── La danse/trend continue
├── Le texte peut évoluer (deuxième ligne, punchline)
└── Le son trending maintient l'engagement

FRAME 4 (8.0 - 12.0s) : FIN + LOOP
├── La vidéo se termine naturellement
├── Transition fluide vers le début → encourager le rewatch
└── Pas de CTA vocal, pas de "follow for more" (tue le completion rate)
```

### Ce qui tue le completion rate (à ÉVITER)

- Intro ou logo avant le contenu (les gens scrollent immédiatement)
- Texte trop long à lire (max 2 lignes, max 15 mots)
- Vidéo de plus de 20 secondes sans raison (dur d'atteindre 70% sur 20s+). **Exception : Format E (1-2min) a un objectif de completion rate différent (~40-50%) mais compense par le watch time total et l'éligibilité Creator Rewards**
- "Follow for more" ou CTA en fin de vidéo (le viewer scroll avant d'atteindre la fin)
- Qualité vidéo basse (pixelisé, flou = signal négatif)
- Début lent sans hook immédiat

---

## 3. LA STRATÉGIE DE HOOKS — LES 2 PREMIÈRES SECONDES

### Principe

Le hook CherryPick repose sur le **texte overlay provocateur**. C'est lui qui arrête le scroll, pas la danse. La danse retient, le texte accroche.

### Les 5 patterns de hooks CherryPick

**Pattern 1 : Le Roast Direct**
Attaque frontale sur un comportement commun des builders.
- *"YOUR SAAS SOLVES A PROBLEM NOBODY HAS"*
- *"200H OF CODE. 0 USERS."*
- *"HE REFACTORED 4 TIMES. STILL NO CUSTOMERS."*
- *"ANOTHER FRAMEWORK. SAME 0 MRR."*

**Pattern 2 : Le Miroir Douloureux**
Le viewer se reconnaît personnellement.
- *"YOU SPENT 3 MONTHS ON YOUR LANDING PAGE. NOBODY VISITS IT."*
- *"YOUR SIDE PROJECT HAS MORE GITHUB STARS THAN USERS"*
- *"YOU KNOW MORE ABOUT TAILWIND THAN ABOUT YOUR CUSTOMERS"*
- *"YOU'RE NOT BUILDING. YOU'RE HIDING."*

**Pattern 3 : La Contradiction**
Challenge une croyance commune de la niche.
- *"YOUR STACK IS PERFECT. THAT'S THE PROBLEM."*
- *"STOP LEARNING. START SELLING."*
- *"THE BEST CODE WON'T SAVE YOUR BUSINESS"*
- *"YOU DON'T NEED ANOTHER FEATURE. YOU NEED 1 CUSTOMER."*

**Pattern 4 : Le Chiffre Choc**
Statistique qui frappe.
- *"97 OUT OF 100 SAAS BUILDERS FAIL. HERE'S WHY."*
- *"0€ MRR AFTER 6 MONTHS. THE REAL REASON."*
- *"HE SPENT $0 ON ADS. MADE $10K MRR."*

**Pattern 5 : Le Tease Éducatif (pour les Formats B et E)**
Promet une leçon en créant un open loop.
- *"THE 3% WHO MAKE IT ALL DO THIS ONE THING..."*
- *"THE FIRST THING I'D DO WITH 0 FOLLOWERS AND A SAAS..."*
- *"WHY YOUR COMPETITOR WITH WORSE CODE MAKES MORE MONEY"*

### Règles de rédaction des hooks

- **MAJUSCULES** — toujours, pour l'impact visuel et la lisibilité
- **Max 2 lignes, max 15 mots** — doit être lu en 2 secondes
- **Pas de question** — les affirmations provocatrices performent mieux que les questions
- **Adresse directe ("YOU/YOUR")** — crée une connexion personnelle immédiate
- **Zéro jargon technique obscur** — "MRR" oui (la niche comprend), "CQRS" non
- **Le texte doit provoquer une réaction émotionnelle** — rire, indignation, identification

---

## 4. TIKTOK SEO APPLIQUÉ À CHERRYPICK

### Keywords cibles

L'algo scanne les mots prononcés, le texte à l'écran et les captions. CherryPick doit intégrer ces keywords naturellement.

**Keywords primaires (fort volume dans la niche) :**
- SaaS
- indie hacker / indie hackers
- side project
- build in public
- startup
- MRR (Monthly Recurring Revenue)
- coding / code / developer
- ship / shipping (livrer du code)

**Keywords secondaires :**
- no-code
- solopreneur
- tech startup
- passive income
- quit your job
- freelance developer
- product market fit
- landing page
- first customer

**Keywords longue traîne (contenu éducatif) :**
- how to get first SaaS customer
- why SaaS builders fail
- SaaS marketing with no budget
- indie hacker mistakes
- build vs sell

### Application par couche SEO

**Couche 1 — Texte à l'écran (le plus fort pour CherryPick) :**
Les text overlays contiennent naturellement les keywords. "YOUR SAAS SOLVES A PROBLEM NOBODY HAS" contient "SaaS" — l'algo le scanne et catégorise.

**Couche 2 — Caption :**
Format type : une phrase naturelle + keywords + 3-5 hashtags.
Exemple : *"When you've been building for 6 months and your MRR is still at zero 🍒 #indiehacker #saas #buildinpublic #devlife #shiporsink"*

**Couche 3 — Audio (optionnel mais puissant) :**
Si la vidéo inclut une voix (text-to-speech ou voix off future), prononcer les keywords dans les 5 premières secondes. Exemple : *"Every SaaS builder needs to hear this."*

---

## 5. STRATÉGIE HASHTAGS

### Les hashtags CherryPick

**Set principal (utiliser 3-5 par vidéo, varier la combinaison) :**

| Hashtag | Volume | Pertinence |
|---------|--------|------------|
| #indiehacker | Élevé | Cœur de cible |
| #saas | Élevé | Mot-clé produit |
| #buildinpublic | Élevé | Communauté active |
| #devlife | Élevé | Large audience dev |
| #codinghumor | Moyen | Divertissement dev |
| #techstartup | Moyen | Audience startup |
| #solopreneur | Moyen | Cible directe |
| #mrr | Faible | Ultra niche, haute pertinence |
| #shiporsink | Faible | Pourrait devenir signature CherryPick |
| #cherrypicked | Faible | Hashtag de marque à construire |

### Règles

- **3-5 hashtags par vidéo, jamais plus**
- **Rotation** — ne pas utiliser les mêmes 5 à chaque fois, varier les combinaisons
- **1 hashtag de marque récurrent** : #cherrypicked (à inclure dans chaque vidéo pour construire la découvrabilité)
- **JAMAIS** : #fyp #viral #foryou #trending #foryoupage (spam, zéro valeur, risque de suppression de reach)
- **Tester** : surveiller quels hashtags sont associés aux vidéos qui performent le mieux

---

## 6. MAXIMISER LES SHARES ET SAVES

### Pourquoi c'est critique

En 2026, shares et saves sont les signaux les plus puissants. Un share = quelqu'un envoie ta vidéo à un ami développeur en disant "c'est tellement moi". Un save = quelqu'un veut revoir cette vérité.

### Ce qui déclenche un share dans la niche dev/builder

- **L'identification personnelle** — le viewer se reconnaît et veut montrer à son pote dev que "c'est nous"
- **Le roast de groupe** — touche un comportement collectif ("on fait tous ça")
- **La vérité inconfortable** — le viewer partage pour valider son propre ressenti
- **L'humour insider** — blagues que seuls les devs/builders comprennent

### Ce qui déclenche un save

- **Le contenu éducatif condensé** — une leçon en 10 secondes que le viewer veut retenir
- **Les chiffres/stats choc** — données qu'on veut retrouver plus tard
- **Les "vérités" quotables** — phrases que le viewer veut réutiliser

### Optimisation CherryPick pour les shares

Le format idéal pour le share : une vidéo que le viewer envoie en DM à son pote dev avec le message "bro 💀". Pour ça, le texte overlay doit toucher un comportement UNIVERSEL dans la niche, pas un cas hyper spécifique.

✅ **Shareable** : "YOU REFACTORED YOUR CODE 4 TIMES BUT HAVE 0 USERS" → tous les devs ont fait ça
❌ **Pas shareable** : "YOUR KUBERNETES CLUSTER IS OVERKILL FOR 3 USERS" → trop spécifique, moins de gens se reconnaissent

---

## 7. MITIGATION DU RISQUE SHADOWBAN IA

### Le risque spécifique à CherryPick

CherryPick est un personnage IA généré par des modèles de génération d'images et vidéos. TikTok pénalise de plus en plus le contenu détecté comme synthétique ou mass-produced. C'est le risque #1 du projet.

### Stratégie de mitigation

**1. Ne JAMAIS taguer ou mentionner "IA" dans le contenu**
- Pas de #ai #aiart #aigeneratedcontent
- Pas de mention dans la caption que c'est généré par IA
- Le masque vénitien aide ici — il détourne l'attention du visage et réduit la probabilité de détection "deepfake"

**2. Varier les styles visuels**
- Personnage différent à chaque vidéo = pas de pattern répétitif détectable
- Varier les backgrounds, tenues, ambiances (le prompt Kling permet ça)
- Ne jamais publier 2 vidéos consécutives avec un style visuel trop similaire

**3. Post-production "humaine"**
- Ajouter le text overlay manuellement (CapCut/FFmpeg), pas dans la génération IA
- Utiliser des sons trending TikTok natifs (pas de l'audio généré)
- Ajouter des effets TikTok natifs quand c'est pertinent (signale un vrai créateur)
- Exporter en qualité native TikTok (1080x1920, pas de watermark IA)

**4. Engagement pattern humain**
- Répondre aux commentaires (en texte, dans le ton CherryPick)
- Commenter sur d'autres vidéos régulièrement
- Ne pas publier avec une régularité robotique (varier légèrement les heures)
- Utiliser les outils natifs TikTok (duets, stitches) quand c'est pertinent

**5. Surveiller les signaux d'alerte**
- Chute soudaine des vues sur plusieurs vidéos consécutives → possible shadowban
- Vidéos qui restent à 0 vues pendant 24h+ → vérifier les paramètres
- Si shadowban détecté : pause 3 jours, reprendre avec du contenu adapté

**6. Plan B si TikTok détecte systématiquement le contenu IA**
- Réorienter vers des formats plus "hybrides" (texte sur fond coloré + musique, sans personnage IA)
- Utiliser le personnage IA uniquement sur Instagram Reels et YouTube Shorts (algos différents)
- Tester des formats alternatifs (screenshots de code + voix off, screen recordings)

---

## 8. CALENDRIER ET TIMING DE PUBLICATION

### Heures optimales pour la niche dev/builder (US timezone)

La cible est principalement US (contenu en anglais). Les devs/builders consultent TikTok :

| Créneau | Heure EST | Heure FR | Pourquoi |
|---------|-----------|----------|----------|
| Morning scroll | 8h-10h EST | 14h-16h FR | Avant le travail, pause café |
| Lunch break | 12h-13h EST | 18h-19h FR | Pause déjeuner |
| After work | 17h-20h EST | 23h-02h FR | Fin de journée, détente |
| Late night | 21h-23h EST | 03h-05h FR | Les devs qui codent tard |

**Créneau recommandé pour Fabrice (depuis la France) :**
- Publier entre **14h-16h heure française** (= 8h-10h EST, morning scroll US)
- OU entre **18h-19h heure française** (= 12h-13h EST, lunch break US)
- Ces créneaux tombent dans le temps de travail CherryPick de Fabrice (13h-21h)

### Fréquence

- **Objectif : 1 vidéo par jour, 7/7**
- Minimum viable : 5 vidéos par semaine (ne jamais descendre en dessous)
- La cohérence > la fréquence. Mieux vaut 1/jour stable que 3 un jour et 0 les 3 jours suivants
- L'algo récompense la régularité — un compte qui publie chaque jour à heures similaires construit de la fiabilité auprès de l'algo

---

## 9. STRATÉGIE D'ENGAGEMENT ACTIF

### Pourquoi c'est non-négociable

L'engagement actif (commenter, répondre, interagir) est un facteur de distribution en 2026. Les créateurs qui interagissent activement reçoivent un avantage de distribution. C'est DOUBLE valeur pour CherryPick : ça nourrit l'algo ET ça construit la notoriété du personnage dans la niche.

### Routine quotidienne d'engagement

**Avant publication (10-15 min) :**
- Scroller le FYP dans la niche dev/builder
- Commenter sur 10-15 vidéos de créateurs de la niche
- Commentaires TOUJOURS dans le ton CherryPick (sarcastique, provocateur, marrant)
- Exemples : *"Another todo app tutorial. Groundbreaking."* / *"Ship it or it doesn't exist."* / *"This is why 97% fail. And I love watching it."*

**Après publication (20-30 min) :**
- Rester actif sur TikTok pendant la première heure après publication (engagement velocity)
- Répondre à CHAQUE commentaire sur la nouvelle vidéo dans le ton CherryPick
- Continuer à commenter sur d'autres vidéos de la niche
- Les réponses en vidéo aux commentaires sont extrêmement puissantes (crée du contenu additionnel + signal d'engagement actif)

**Quotidien (5-10 min supplémentaires) :**
- Vérifier les commentaires sur les vidéos précédentes
- Répondre aux nouveaux commentaires (même sur les vieilles vidéos)
- Identifier les créateurs de la niche qui grandissent et interagir avec eux

### Le ton des commentaires CherryPick

Les commentaires sont une extension du personnage. Ils doivent être :
- Reconnaissables immédiatement comme CherryPick (même ton, même arrogance)
- Courts et punchline (1 ligne max)
- Jamais méchants gratuitement — toujours un fond de vérité
- Jamais promotionnels ("check my page!" = interdit)

---

## 10. PLAN DE LANCEMENT — SEMAINE PAR SEMAINE

### Semaine -1 : Préparation (pas de publication)

| Jour | Action |
|------|--------|
| L | Setup profil TikTok complet (bio, photo masque, username) |
| L | Setup chaîne YouTube CherryPick (même username, même bio, même photo) |
| L | Setup compte Instagram CherryPick (même username, même bio, même photo) |
| L-M | PAS de Linktree ni de lien en bio en Phase 1. 100% focus croissance. |
| M-J | Générer 10 images de personnages variés avec masque vénitien (fal.ai FLUX) |
| J-V | Télécharger 10 vidéos de trends TikTok récentes (danses, mouvements) |
| V-S | Générer 10 vidéos via Kling Motion Control, sélectionner les 7 meilleures |
| S-D | Post-production : text overlays, sons trending, format 9:16, export sans watermark |
| Toute la semaine | Commenter 20-30 vidéos/jour dans la niche dev/builder sur TikTok |

### Semaine 1 : Lancement

| Jour | Publication | Engagement | Objectif |
|------|-------------|------------|----------|
| Lundi | Vidéo #1 — Hook le plus fort du stock → TikTok + YT + IG | 30 commentaires TikTok + réponses | Tester le format |
| Mardi | Vidéo #2 — Style différent de #1 → 3 plateformes | 25 commentaires + réponses | Comparer les métriques |
| Mercredi | Vidéo #3 — Le meilleur hook restant → 3 plateformes | 25 commentaires + réponses | Identifier le pattern gagnant |
| Jeudi | Analyse des 3 vidéos sur les 3 plateformes. Quel format/plateforme performe le mieux ? | 20 commentaires | Décider la direction |
| Vendredi | Vidéo #4 — Dans le style le plus performant → 3 plateformes | 25 commentaires + réponses | Confirmer le pattern |
| Samedi | Vidéo #5 — Variante du pattern gagnant → 3 plateformes | 20 commentaires | Consolider |
| Dimanche | Vidéo #6 — Format E éducatif long 1min+ → 3 plateformes | 15 commentaires | Tester le format long |

**Métriques à tracker :**
- Vues par vidéo (objectif : au moins 1 vidéo à 500+ vues)
- Completion rate par vidéo (objectif : 50%+ en moyenne)
- Commentaires organiques reçus (signal de résonance)
- Followers gagnés (objectif semaine 1 : 50-200)

### Semaine 2 : Optimisation

- Doubler sur le format qui performe le mieux
- Tester 2 nouveaux styles de hooks
- Augmenter la qualité de post-production si nécessaire
- Commencer à identifier les heures de publication optimales via les analytics
- Objectif : 200-500 followers cumulés

### Semaine 3 : Accélération

- Le pattern de contenu est validé — produire à cadence régulière
- Tester le premier Duet ou Stitch avec un créateur de la niche
- Commencer à répondre à des commentaires en vidéo (contenu bonus gratuit)
- Objectif : 500-1 000 followers cumulés

### Semaine 4 : Consolidation

- Analyser les 25-30 vidéos publiées : top 5, flop 5, patterns
- Ajuster la stratégie éditoriale basée sur les données
- Augmenter la proportion de contenu éducatif si le roast pur stagne
- Objectif : 1 000-2 000 followers cumulés, au moins 1 vidéo à 10K+ vues

### Bilan Mois 1

| Métrique | Objectif minimum | Objectif ambitieux |
|----------|-----------------|-------------------|
| Vidéos publiées (par plateforme) | 25 | 30 |
| Followers TikTok | 1 000 | 5 000 |
| Subscribers YouTube | 200 | 1 000 |
| Followers Instagram | 500 | 2 000 |
| Vidéo la plus vue (toutes plateformes) | 10K vues | 100K vues |
| Completion rate moyen TikTok | 50% | 70% |
| Engagement rate TikTok | 3% | 7% |
| Vidéos Format E (long) publiées | 4 | 8 |

---

## 11. FORMATS DE CONTENU DÉTAILLÉS

### Format A — Trend Danse + Roast (50% du contenu)

**Structure :**
- Personnage masqué exécute une trend TikTok populaire
- Text overlay : punchline roast en majuscules
- Son : audio trending TikTok du moment
- Durée : 8-15 secondes
- Post-prod : text overlay ajouté dans CapCut, format 9:16

**Exemple concret :**
```
Visuel : Femme avec masque vénitien, hoodie tech, danse trend du moment
Texte : "YOUR SAAS HAS MORE FEATURES THAN USERS"
Son : [son trending de la semaine]
Durée : 12 secondes
Caption : "Cherry-picked 🍒 #indiehacker #saas #buildinpublic #devlife #cherrypicked"
```

### Format B — Éducatif Provocateur Court (20% du contenu)

**Structure :**
- Même personnage masqué, même esthétique
- Texte overlay plus long (peut évoluer en 2-3 écrans)
- Contenu : une vérité business condensée en 10-15 secondes
- Ton : toujours arrogant, jamais "coach bienveillant"
- Son : beat plus calme ou dramatique

**Exemple concret :**
```
Visuel : Femme avec masque vénitien, bras croisés, mouvement lent et confiant
Texte écran 1 (0-5s) : "THE 3% WHO SUCCEED ALL DO THIS"
Texte écran 2 (5-12s) : "THEY SELL BEFORE THEY CODE."
Son : beat dramatique/cinématique
Durée : 12 secondes
Caption : "The truth nobody teaches in coding bootcamps 🍒 #indiehacker #saas #techstartup #cherrypicked"
```

### Format C — Réponse en Vidéo à un Commentaire (Bonus)

**Structure :**
- Répondre à un commentaire intéressant avec une nouvelle vidéo
- Le commentaire s'affiche en haut de l'écran (feature native TikTok)
- CherryPick "répond" avec un roast ou un conseil
- Double valeur : nouveau contenu + signal d'engagement actif

**Quand l'utiliser :**
- Quand un commentaire a beaucoup de likes (l'audience veut une réponse)
- Quand un commentaire setup parfaitement une punchline
- Quand quelqu'un challenge CherryPick (la confrontation = engagement)

### Format D — Stitch/Duet (Occasionnel)

**Structure :**
- Stitch : prendre le début d'une vidéo d'un autre créateur dev + ajouter la réaction CherryPick
- Duet : réagir côte à côte à une vidéo de la niche
- Puissant pour piquer l'audience d'un créateur plus gros

**Quand l'utiliser :**
- Quand un créateur de la niche poste un take contestable
- Quand une vidéo "grind motivation" mérite un roast
- 1-2 fois par semaine maximum

### Format E — Éducatif Approfondi Long (1-2 min) — CRITIQUE POUR LA MONÉTISATION

Ce format est essentiel. C'est le seul format éligible au TikTok Creator Rewards Program (minimum 1 minute) et il génère un meilleur RPM sur YouTube Shorts (les vidéos 50-60s ont 76% de watch-through rate sur YouTube).

**Fréquence : 2 vidéos par semaine.**

**Structure :**
- Même personnage masqué, même esthétique CherryPick
- Hook provocateur dans les 3 premières secondes (identique au format court)
- Développement du point pendant 40-60 secondes
- Punchline finale percutante (10 secondes)
- Ton toujours arrogant, mais plus de substance que le format court

**Exemple concret :**
```
Visuel : Femme avec masque vénitien, mouvement lent et confiant, environnement studio sombre avec accents néon
Texte écran 1 (0-3s) : "WHY 97% OF SAAS BUILDERS FAIL"
Texte écran 2 (3-20s) : "REASON 1: THEY BUILD BEFORE THEY SELL"
Texte écran 3 (20-40s) : "REASON 2: THEY OPTIMIZE CODE, NOT DISTRIBUTION"
Texte écran 4 (40-60s) : "REASON 3: THEY THINK THE PRODUCT SELLS ITSELF"
Texte écran 5 (60-75s) : "THE 3% WHO WIN? THEY SELL FIRST. CODE SECOND."
Son : beat cinématique/dramatique
Durée : 1min15
Caption : "97% fail. Not because of code. Because of ego. 🍒 #indiehacker #saas #buildinpublic #techstartup #cherrypicked"
```

**Différences clés avec le format court :**
| | Format A/B (court) | Format E (long) |
|--|-------------------|-----------------|
| Durée | 8-15 secondes | 1-2 minutes |
| Objectif algo | Completion rate max → viralité | Watch time + Creator Rewards |
| Texte overlay | 1-2 lignes, 1 punchline | 3-5 écrans, développement d'un argument |
| Son | Trending TikTok | Beat cinématique/original (meilleur RPM YouTube) |
| Monétisation directe | Non (trop court pour Creator Rewards) | Oui (éligible Creator Rewards TikTok + ad revenue YouTube) |
| Risque | Hook faible = scroll immédiat | Rétention difficile sur 1min+ |

**Conseil de production :** générer une vidéo Kling plus longue (demander 10s au lieu de 5s, ou combiner 2 clips). En post-prod, ajouter des transitions entre les écrans de texte pour maintenir l'attention. Utiliser des zooms lents, des changements de plan, des effets de texte progressifs.

---

## 12. PRODUCTION QUOTIDIENNE — WORKFLOW OPTIMISÉ

### Temps estimé par vidéo

| Étape | Temps | Outil |
|-------|-------|-------|
| Trouver la trend du jour | 5-10 min | Scroll TikTok, identifier la danse/mouvement populaire |
| Télécharger la vidéo source | 2 min | SnapTik, SSSTik, ou sauvegarde manuelle |
| Écrire le texte overlay | 5 min | Brainstorm punchline dans le ton CherryPick |
| Générer l'image personnage | 3 min | fal.ai FLUX (prompt avec masque vénitien) |
| Générer la vidéo Motion Control | 6-8 min | fal.ai Kling v2.6 Standard |
| Post-production | 10-15 min | CapCut : text overlay, format 9:16 (PAS de son dans CapCut) |
| Export sans watermark | 2 min | Export fichier propre pour cross-posting |
| Publier TikTok (caption + hashtags) | 3 min | Appliquer la stratégie SEO et hashtags TikTok |
| Adapter et publier YouTube Shorts | 5-7 min | Titre SEO, description avec liens, audio original si possible |
| Adapter et publier Instagram Reels | 5-7 min | Caption IG, hashtags IG, tags produit si pertinent |
| Engagement post-publication | 20-30 min | Commentaires sur les 3 plateformes (prioriser TikTok) |
| **TOTAL** | **~70-95 min** | |

### Optimisation batch

Pour gagner du temps, produire en batch :
- **Dimanche soir :** Trouver 5-7 trends pour la semaine, télécharger toutes les vidéos sources
- **Lundi-Mardi :** Générer toutes les images et vidéos de la semaine (fal.ai)
- **Mardi-Mercredi :** Post-production de toute la semaine + export sans watermark
- **Quotidien :** Publier sur les 3 plateformes + engagement actif (35-50 min/jour)

En mode batch, le temps quotidien tombe à **~35-50 min** (publication 3 plateformes + engagement) avec une session de production de **~3-4h** le week-end.

### Ordre de publication quotidien

| Heure (FR) | Plateforme | Action |
|------------|-----------|--------|
| 14h-16h | TikTok | Publier en premier (plateforme de découverte #1) |
| 16h-18h | YouTube Shorts | Publier 2-4h après TikTok |
| 18h-20h | Instagram Reels | Publier 4-6h après TikTok |

Cet échelonnement évite la détection de "spam cross-plateforme" et permet de tester des heures optimales différentes par plateforme.

---

## 13. MÉTRIQUES À SURVEILLER

### Dashboard hebdomadaire — TikTok (plateforme principale)

| Métrique | Où la trouver | Seuil d'alerte | Action si en dessous |
|----------|--------------|-----------------|---------------------|
| Completion rate moyen | TikTok Analytics | < 40% | Raccourcir les vidéos, renforcer les hooks |
| Vues moyennes par vidéo | TikTok Analytics | < 300 | Vérifier shadowban, revoir les hashtags |
| Engagement rate | TikTok Analytics | < 2% | Revoir le contenu, plus provocateur |
| Shares par vidéo | TikTok Analytics | < 5 | Le contenu n'est pas assez "envoyable" |
| Followers gagnés/semaine | TikTok Analytics | Stagnation 2 semaines | Tester un nouveau format |
| Meilleure heure de publication | TikTok Analytics | N/A | Ajuster le créneau de publication |
| Ratio contenu court/long | Manuel | Plus de 85% court | Réintroduire du Format E (long) |

### Dashboard hebdomadaire — YouTube Shorts

| Métrique | Où la trouver | Seuil d'alerte | Action si en dessous |
|----------|--------------|-----------------|---------------------|
| Vues Shorts | YouTube Studio | < 50% des vues TikTok | Revoir titres SEO, descriptions |
| RPM Shorts | YouTube Studio (après monétisation) | < $0.03 | Réduire musique sous licence, + audio original |
| Subscribers gagnés/semaine | YouTube Studio | Stagnation 2 semaines | Ajouter CTA "subscribe" en description |
| CTR (click-through rate) | YouTube Studio | < 2% | Améliorer les titres |

### Dashboard hebdomadaire — Instagram Reels

| Métrique | Où la trouver | Seuil d'alerte | Action si en dessous |
|----------|--------------|-----------------|---------------------|
| Vues Reels | Instagram Insights | < 30% des vues TikTok | Revoir les hashtags IG, heures de post |
| Engagement rate | Instagram Insights | < 3% | Adapter le contenu au ton IG |
| Followers gagnés/semaine | Instagram Insights | Stagnation 2 semaines | Plus d'interaction communauté |
| Saves | Instagram Insights | < 2% des vues | Contenu pas assez "saveable" |

### Red flags (toutes plateformes)

- **3 vidéos consécutives sous 200 vues** → possible shadowban → pause 48h
- **Completion rate < 30% sur 5 vidéos** → les hooks ne marchent pas → pivoter le style
- **0 commentaires sur 3 vidéos consécutives** → le contenu ne provoque pas de réaction → plus provocateur
- **Followers qui baissent** → le contenu déçoit l'audience existante → revoir la qualité

---

## 14. ÉVOLUTION LONG TERME

### Mois 1-3 : Croissance Pure (3 plateformes)

- 100% focus sur l'engagement et les followers sur TikTok + YouTube + Instagram
- Cross-posting de chaque vidéo sur les 3 plateformes dès le jour 1
- Zéro mention de FoundryTwo ou de produits
- Zéro lien en bio, zéro affiliation — 100% focus croissance organique
- Objectif : valider le concept, trouver le product-market fit éditorial
- Tester, itérer, analyser, ajuster par plateforme

### Mois 3-5 : Introduction Subtile + Premiers Revenus

- CherryPick commence à mentionner "des outils qui marchent vraiment" vs "du code inutile"
- Contenu éducatif qui pointe naturellement vers des solutions (sans nommer FoundryTwo)
- Teasers cryptiques : *"I know a tool that fixes this. Stay tuned."*
- Ajouter Linktree complet en bio (affiliés + FoundryTwo)
- Premiers brand deals actifs ($300-$2 500/mois)
- YouTube Partner Program atteint (ad revenue sur Shorts)
- Format E (long) déjà intégré → Creator Rewards TikTok activé si 10K+ followers

### Mois 5+ : Synergie Complète & Monétisation Full

- CherryPick renvoie explicitement vers FoundryTwo sur les 3 plateformes
- Chaque lancement de SaaS est annoncé par CherryPick dans son ton
- Le compte CherryPick + le compte FoundryTwo (géré par Romain) fonctionnent en réseau (Option B)
- Brand deals cross-plateforme (prix premium car 3 plateformes)
- Mesurer le trafic et les conversions depuis CherryPick vers les SaaS par plateforme
- Objectif : $8 000+/mois toutes sources combinées (voir 01-foundation/MONETIZATION.md)

---

## 15. CHECKLIST PRÉ-PUBLICATION

### Checklist production (avant export)

- [ ] Le texte overlay est visible dès la FRAME 1 (pas de délai)
- [ ] Le texte fait max 2 lignes, max 15 mots (Format A/B) ou progression multi-écrans (Format E)
- [ ] Le texte est provocateur / drôle / identifiable
- [ ] La vidéo fait entre 8-15s (Format A/B) ou 1-2min (Format E)
- [ ] Le masque vénitien est visible
- [ ] Le format est 9:16 natif (1080x1920)
- [ ] Pas de mention d'IA, pas de tag IA
- [ ] Pas de watermark de génération IA
- [ ] **Export SANS watermark** (fichier propre pour cross-posting)

### Checklist TikTok

- [ ] Son trending TikTok ajouté depuis l'app (pas pré-intégré)
- [ ] Caption avec keywords de la niche
- [ ] 3-5 hashtags de niche (pas de #fyp #viral)
- [ ] #cherrypicked inclus
- [ ] Heure de publication en créneau US prime (14h-16h FR)
- [ ] Stock de vidéos pour les jours suivants prêt

### Checklist YouTube Shorts

- [ ] Titre optimisé SEO (ex: "Why SaaS builders fail | CherryPick")
- [ ] Description avec keywords + liens affiliés
- [ ] Audio : original ou libre de droits si possible (meilleur RPM, -33% si musique sous licence)
- [ ] Tags YouTube pertinents
- [ ] Publié 2-4h après TikTok

### Checklist Instagram Reels

- [ ] Audio trending Instagram (peut différer du son TikTok)
- [ ] Caption adaptée au ton Instagram (plus longue, plus narrative)
- [ ] Hashtags IG (différents de TikTok, plus de hashtags communautaires)
- [ ] Tags produit si pertinent (Instagram Shopping)
- [ ] Publié 4-6h après TikTok

---

*Ce playbook évolue en continu. Chaque semaine, les métriques doivent être analysées sur les 3 plateformes et la stratégie ajustée. L'algo change, le marché change, le contenu qui performe change. L'adaptabilité est le seul avantage durable. Voir 01-foundation/MONETIZATION.md pour les stratégies de revenus détaillées.*
