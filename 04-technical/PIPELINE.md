# 🍒 CherryPick — Pipeline de Production

> Workflow step-by-step complet de la trend au post publié sur 3 plateformes.
> Ce fichier est le mode opératoire. Chaque étape est actionnable.
> Référence outils : `04-technical/TOOLS_AND_ACCOUNTS.md`
> Référence cross-posting : `04-technical/CROSS_POSTING.md`
>
> Dernière mise à jour : 1 mars 2026

---

## Vue d'ensemble du pipeline

```
VEILLE (5-10 min)
  └→ Identifier la trend du jour
       └→ Télécharger la vidéo de référence

CRÉATION IMAGE (3-5 min)
  └→ Sélectionner le prompt FLUX adapté
       └→ Générer l'image via fal.ai
            └→ Valider la qualité (checklist)

CRÉATION VIDÉO (6-10 min)
  └→ Upload image + vidéo de référence dans Kling
       └→ Générer la vidéo Motion Control
            └→ Valider la qualité (checklist)

POST-PRODUCTION (10-15 min)
  └→ Importer dans CapCut
       └→ Ajouter text overlay + timing
            └→ Exporter SANS watermark (fichier propre)

PUBLICATION (15-20 min)
  └→ TikTok (14h-16h FR)
       └→ YouTube Shorts (16h-18h FR)
            └→ Instagram Reels (18h-20h FR)

ENGAGEMENT (20-30 min)
  └→ Répondre aux commentaires (3 plateformes)
       └→ Commenter dans la niche
```

---

## Étape 1 — Veille des trends (5-10 min)

### Quotidien (si production au jour le jour)

1. Ouvrir TikTok, aller sur la page Discover/For You
2. Identifier les trends en cours dans la niche dev/tech ou les trends de danse virales
3. Critères de sélection d'une trend :
   - Le mouvement est reproductible par Kling (pas trop complexe)
   - La trend a < 3 jours (encore en phase montante)
   - Le son est populaire mais pas encore saturé
   - Le mouvement est faisable en 5 secondes
4. Télécharger la vidéo de référence (SnapTik ou SSSTik)
5. Couper les 5 premières secondes (le segment le plus reconnaissable)

### En batch (dimanche soir pour la semaine)

1. Identifier 5-7 trends de la semaine
2. Télécharger toutes les vidéos de référence
3. Les nommer : `trend_YYYYMMDD_description.mp4`
4. Stocker dans un dossier organisé par semaine

---

## Étape 2 — Génération d'image (3-5 min)

1. Ouvrir fal.ai (ou lancer le script `cherrypick-engine`)
2. Sélectionner le prompt adapté depuis `03-visual/PROMPTS_IMAGE.md`
   - Trend danse → prompt maître ou variation mouvement
   - Format E statique → variation assise ou tech futuriste
3. Générer 2-3 images, sélectionner la meilleure
4. Passer la checklist qualité (`03-visual/PROMPTS_IMAGE.md` section Checklist)
5. Si aucune image n'est satisfaisante → ajuster le prompt ou le seed et regénérer

---

## Étape 3 — Génération vidéo (6-10 min)

1. Ouvrir Kling Motion Control sur fal.ai (ou script `cherrypick-engine`)
2. Upload : image CherryPick sélectionnée + vidéo de référence de la trend
3. Sélectionner le prompt vidéo adapté depuis `03-visual/PROMPTS_VIDEO.md`
4. Lancer la génération (3-6 min d'attente)
5. Passer la checklist qualité (`03-visual/PROMPTS_VIDEO.md` section Checklist)
6. Si le résultat n'est pas satisfaisant → relancer (les résultats varient) ou changer d'image source

### Pour le Format E (1-2 min)

1. Générer 2-3 clips de 5-10s avec des images source différentes
2. Varier les poses et mouvements entre les clips
3. Stocker tous les clips pour assemblage en post-production

---

## Étape 4 — Post-production (10-15 min)

### Outil : CapCut (ou DaVinci Resolve)

1. **Importer** la vidéo Kling dans CapCut
2. **Découper** : ajuster la durée exacte (8-15s pour Format A, 1-2min pour Format E)
3. **Text overlay** :
   - Sélectionner le hook depuis `02-content/HOOKS_DATABASE.md`
   - Appliquer la font et le style depuis `03-visual/VISUAL_GUIDE.md`
   - Le texte doit être visible DÈS LA FRAME 1
   - Pour Format E : créer les transitions entre les écrans de texte
4. **Audio** : NE PAS ajouter de son dans CapCut
   - Le son trending TikTok sera ajouté directement dans l'app TikTok lors de la publication
   - Pour YouTube : utiliser un audio original ou libre de droits (meilleur RPM)
   - Voir `04-technical/CROSS_POSTING.md` pour les détails audio par plateforme
5. **Format** : vérifier 9:16 / 1080x1920
6. **Exporter** : MP4 H.264, qualité maximale, **SANS watermark CapCut**

### Nommage du fichier exporté

```
CP_YYYYMMDD_formatX_hook##.mp4
```
Exemple : `CP_20260301_formatA_hook05.mp4`

---

## Étape 5 — Publication (15-20 min total, 3 plateformes)

Voir `04-technical/CROSS_POSTING.md` pour les détails par plateforme.

### 5a. TikTok (14h-16h FR) — EN PREMIER

1. Ouvrir l'app TikTok
2. Uploader la vidéo exportée (sans son)
3. **Ajouter le son trending** directement dans l'éditeur TikTok
4. Ajuster la synchronisation son/mouvement
5. Rédiger la caption depuis `02-content/CAPTIONS_TEMPLATES.md`
6. Ajouter les hashtags (3-5 de niche)
7. Publier

### 5b. YouTube Shorts (16h-18h FR) — 2-4h APRÈS TIKTOK

1. Ouvrir YouTube Studio
2. Uploader la même vidéo (sans watermark)
3. **Audio** : ajouter un audio original ou libre de droits (pas le son TikTok)
4. Titre SEO depuis `02-content/CAPTIONS_TEMPLATES.md` section YouTube
5. Description avec liens affiliés + mots-clés
6. Tags YouTube pertinents
7. Publier comme Short

### 5c. Instagram Reels (18h-20h FR) — 4-6h APRÈS TIKTOK

1. Ouvrir Instagram
2. Uploader la vidéo via Reels
3. **Audio** : ajouter un son trending Instagram (peut être différent du son TikTok)
4. Caption narrative depuis `02-content/CAPTIONS_TEMPLATES.md` section Instagram
5. Hashtags IG (10-15)
6. Publier

---

## Étape 6 — Engagement post-publication (20-30 min)

### Immédiat (30 min après publication)

1. Répondre à TOUS les commentaires sur TikTok dans les 30 premières minutes
2. Répondre aux commentaires YouTube et Instagram dans les 2h

### Quotidien (en dehors des publications)

1. Commenter 10-15 vidéos dans la niche dev/indie hacker sur TikTok
2. Commenter authentiquement (pas de spam, pas de promo)
3. Liker et répondre aux commentaires sur les publications de la journée
4. Identifier des opportunités de Stitch/Duet pour les Formats C/D

---

## Temps total par jour

| Mode | Production | Publication | Engagement | Total |
|------|-----------|-------------|------------|-------|
| Production au jour le jour | 25-40 min | 15-20 min | 20-30 min | **60-90 min** |
| Batch (week-end) + publication quotidienne | 0 min (fait le WE) | 15-20 min | 20-30 min | **35-50 min** |
| Session batch week-end | 3-4h en une session | 0 | 0 | **3-4h** |
