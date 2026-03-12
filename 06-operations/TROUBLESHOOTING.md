# 🍒 CherryPick — Troubleshooting

> Guide de résolution quand ça merde. Diagnostic → cause → solution.
> Compléter au fur et à mesure avec les problèmes rencontrés.
>
> Dernière mise à jour : 1 mars 2026

---

## 1. Problèmes de reach / algorithme

### Chute soudaine de vues (< 50% de la moyenne)

**Diagnostic :** Les vidéos récentes ont beaucoup moins de vues que d'habitude, sans changement de contenu.

| Cause possible | Probabilité | Solution |
|---------------|------------|---------|
| Shadowban TikTok | Moyenne | Vérifier : rechercher le compte depuis un autre compte. Si invisible → attendre 2-7 jours sans publier, puis reprendre |
| Changement d'algorithme | Haute | Vérifier si d'autres créateurs de la niche ont le même problème. Si oui → adapter, pas paniquer |
| Contenu signalé | Faible | Vérifier les notifications de violation. Si signalé → contester si injustifié |
| Horaire de publication décalé | Moyenne | Revenir aux créneaux optimaux (14h-16h FR pour US prime) |
| Son trending expiré | Moyenne | Le son utilisé est passé de mode → utiliser un son plus récent |

### Completion rate en baisse (< 40%)

| Cause | Solution |
|-------|---------|
| Hooks trop faibles | Tester des hooks plus provocateurs depuis `02-content/HOOKS_DATABASE.md` |
| Vidéos trop longues pour le format | Raccourcir — le sweet spot Format A est 8-12s, pas 15s |
| Text overlay pas lisible | Vérifier le contraste, la taille, la position (référence `03-visual/VISUAL_GUIDE.md`) |
| Mouvement personnage pas fluide | Regénérer avec Kling — les résultats varient |

### Engagement rate en baisse (< 2%)

| Cause | Solution |
|-------|---------|
| Contenu pas assez polarisant | Augmenter le ton provocateur. Les hot takes > les observations neutres |
| Pas de question dans la caption | Toujours terminer par une question ou une provocation qui invite au commentaire |
| Manque d'engagement proactif | Augmenter le nombre de commentaires quotidiens dans la niche (min 15-20/jour) |
| Audience fatiguée du même format | Tester un nouveau format ou un nouvel angle |

---

## 2. Problèmes techniques — Génération IA

### Image FLUX de mauvaise qualité

| Symptôme | Cause | Solution |
|----------|-------|---------|
| Visage déformé | Prompt trop complexe ou conflit | Simplifier le prompt, utiliser le prompt maître de base |
| Masque pas réaliste | Mauvaise description du masque | Utiliser "Venetian masquerade mask" et pas "mask" tout court |
| Doigts/mains déformés | Problème classique des modèles génératifs | Cadrer plus serré (buste/visage), ou regénérer |
| Image trop lumineuse | Prompt ne spécifie pas l'éclairage | Ajouter "dramatic cinematic lighting, dark moody background" |
| Résolution basse | Mauvais paramètre de résolution | Vérifier : 768x1344 minimum, 1024x1792 idéal |

### Vidéo Kling de mauvaise qualité

| Symptôme | Cause | Solution |
|----------|-------|---------|
| Masque disparaît pendant le mouvement | Mouvement de référence trop rapide | Choisir un segment plus lent, ou stabiliser l'image source |
| Corps se déforme | Incompatibilité pose image / mouvement référence | Utiliser une image avec une pose plus neutre |
| Artefacts visuels / glitches | Aléatoire | Relancer la génération 2-3 fois, les résultats varient |
| Vidéo trop courte | Limitation Kling | Combiner plusieurs clips en post-prod (méthode Format E) |
| Mouvement pas reconnaissable | Référence vidéo mal découpée | Re-découper les 5 premières secondes de la trend |

### fal.ai down ou lent

| Solution |
|---------|
| Vérifier status.fal.ai |
| Utiliser le stock de vidéos d'avance (toujours avoir 2-3 jours d'avance) |
| En dernier recours : utiliser Runway ou Pika comme alternative temporaire |

---

## 3. Problèmes de compte / plateforme

### Compte TikTok restreint ou banni

| Étape | Action |
|-------|--------|
| 1 | Ne pas paniquer. Vérifier le motif dans les notifications |
| 2 | Si violation de guidelines → contester via le formulaire d'appel |
| 3 | Si shadowban (pas de ban explicite) → arrêter de publier 3-7 jours, puis reprendre |
| 4 | Si ban permanent → créer un nouveau compte (en dernier recours) |
| 5 | Documenter ce qui a causé le problème pour l'éviter à l'avenir |

### Contenu signalé comme "IA"

| Situation | Action |
|-----------|--------|
| TikTok demande un label "AI generated" | NE PAS ajouter le label. Si obligatoire, évaluer l'impact sur le reach |
| Commentaires accusant "c'est de l'IA" | Ignorer ou répondre avec humour dans le ton CherryPick. Ne jamais confirmer ni nier |
| Plateforme force un tag IA | Se conformer si obligatoire, mais surveiller l'impact sur les métriques |

### Problème de monétisation YouTube

| Problème | Solution |
|----------|---------|
| YPP refusé | Vérifier les critères (500 subs + 3M Shorts vues/90j pour Tier 1). Continuer à publier |
| RPM très bas (<$0.01) | Vérifier que l'audience est bien US/EU. Réduire la musique sous licence |
| Vidéos non indexées comme Shorts | Vérifier durée <60s, ratio 9:16, et #shorts dans la description |

---

## 4. Problèmes de cross-posting

| Problème | Cause | Solution |
|----------|-------|---------|
| Vidéo pénalisée sur YouTube/IG | Watermark TikTok visible | TOUJOURS exporter depuis le fichier source, jamais depuis TikTok |
| Son pas disponible sur IG | Trend TikTok pas sur Instagram | Utiliser un son trending IG différent |
| Même vidéo moins performante sur IG | Algorithme différent | Adapter la caption (plus longue sur IG) et les hashtags |
| Publication simultanée détectée | Échelonnement insuffisant | Respecter le délai de 2-4h entre chaque plateforme |

---

## 5. Problèmes business

### Pas de réponse aux demandes de brand deal

| Cause probable | Solution |
|---------------|---------|
| Audience trop petite | Attendre 10K+ followers avant de prospecter. Focus croissance |
| Email mal ciblé | Vérifier qu'on contacte le bon interlocuteur (creator partnerships, pas support) |
| Media Kit pas convaincant | Mettre à jour les métriques, ajouter des screenshots de vidéos qui performent |
| Mauvais timing | Relancer à J+7. Les marques ont des cycles budgétaires |

### Affiliate links ne convertissent pas

| Cause | Solution |
|-------|---------|
| Mauvais placement | Mettre le lien le plus pertinent en premier dans le Linktree |
| Mauvais produit | Promouvoir des outils que l'audience utilise réellement |
| Pas de CTA | Mentionner "link in bio" dans les vidéos éducatives (Format E) |
| Cookie expiré | Vérifier la durée du cookie de chaque programme |

---

## Log des incidents

| Date | Problème | Cause identifiée | Solution appliquée | Résolu ? |
|------|----------|-----------------|-------------------|----------|
| | | | | |

*Compléter ce log à chaque incident. C'est la mémoire opérationnelle du projet.*
