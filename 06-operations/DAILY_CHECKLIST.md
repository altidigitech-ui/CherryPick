# 🍒 CherryPick — Checklist Quotidienne

> La routine d'exécution de chaque jour. Pas de réflexion, juste de l'exécution.
> Ouvre ce fichier chaque jour, suis les étapes, coche, passe au suivant.
> Référence workflow détaillé : `04-technical/PIPELINE.md`
>
> Dernière mise à jour : 1 mars 2026

---

## Mode "Publication quotidienne" (~35-50 min/jour)

Utilisé quand les vidéos ont été produites en batch le week-end.

### 13h30-14h00 — Préparation (15 min)

- [ ] Ouvrir le `02-content/CONTENT_CALENDAR.md` — identifier la vidéo du jour
- [ ] Vérifier que le fichier vidéo est prêt (exporté sans watermark)
- [ ] Préparer la caption TikTok (depuis `02-content/CAPTIONS_TEMPLATES.md`)
- [ ] Préparer le titre + description YouTube
- [ ] Préparer la caption Instagram

### 14h00-14h15 — Publication TikTok (5 min)

- [ ] Uploader la vidéo dans TikTok
- [ ] Ajouter le son trending TikTok
- [ ] Synchroniser le son avec le mouvement
- [ ] Coller la caption + hashtags
- [ ] Publier
- [ ] Rester dans l'app 5 min (engagement immédiat)

### 14h15-14h30 — Engagement TikTok (15 min)

- [ ] Répondre à tous les commentaires reçus
- [ ] Commenter 10-15 vidéos dans la niche dev/indie hacker
- [ ] Liker les commentaires pertinents sous les vidéos populaires de la niche

### 16h00-16h10 — Publication YouTube Shorts (5 min)

- [ ] Uploader la vidéo dans YouTube Studio
- [ ] Ajouter l'audio original/libre de droits
- [ ] Titre SEO + description avec liens affiliés
- [ ] Tags YouTube
- [ ] Publier comme Short

### 18h00-18h10 — Publication Instagram Reels (5 min)

- [ ] Uploader la vidéo dans Instagram Reels
- [ ] Ajouter le son trending Instagram
- [ ] Caption narrative + hashtags IG
- [ ] Publier

### 18h10-18h20 — Engagement YouTube + Instagram (10 min)

- [ ] Répondre aux commentaires YouTube
- [ ] Répondre aux commentaires Instagram
- [ ] Répondre aux DMs pertinents (pas de spam)

---

## Mode "Production + Publication" (~70-95 min/jour)

Utilisé quand la vidéo n'a pas été produite en batch.

### Avant 13h — Production (30-45 min)

- [ ] Identifier la trend du jour (5-10 min)
- [ ] Télécharger la vidéo de référence
- [ ] Sélectionner le hook du jour depuis `02-content/HOOKS_DATABASE.md`
- [ ] Générer l'image FLUX (3-5 min)
- [ ] Valider la qualité de l'image (checklist `03-visual/PROMPTS_IMAGE.md`)
- [ ] Générer la vidéo Kling (6-10 min d'attente)
- [ ] Valider la qualité de la vidéo (checklist `03-visual/PROMPTS_VIDEO.md`)
- [ ] Post-production CapCut : text overlay + export sans watermark (10-15 min)

### 13h30+ — Publication + Engagement

→ Suivre le mode "Publication quotidienne" ci-dessus

---

## Session Batch Week-end (3-4h le dimanche)

### Veille (30 min)

- [ ] Identifier 5-7 trends pour la semaine
- [ ] Télécharger toutes les vidéos de référence
- [ ] Nommer : `trend_YYYYMMDD_description.mp4`

### Production images (30 min)

- [ ] Générer 10-15 images FLUX (variations de pose et tenue)
- [ ] Sélectionner les 7 meilleures
- [ ] Noter les seeds des meilleures images dans `03-visual/PROMPTS_IMAGE.md`

### Production vidéos (60-90 min)

- [ ] Générer 7 vidéos Kling (image + trend de référence)
- [ ] Sélectionner les 7 meilleures
- [ ] Pour les Format E : générer 2-3 clips par vidéo longue

### Post-production (60-90 min)

- [ ] CapCut : text overlay pour les 7 vidéos
- [ ] Export sans watermark
- [ ] Nommer : `CP_YYYYMMDD_formatX_hook##.mp4`
- [ ] Ranger dans un dossier de la semaine

### Planification (15 min)

- [ ] Remplir le `02-content/CONTENT_CALENDAR.md` de la semaine
- [ ] Associer chaque vidéo à un jour + un hook
- [ ] Pré-rédiger les captions des 3 premières vidéos

---

## Fin de journée (5 min)

- [ ] Vérifier les métriques de la vidéo du jour (vues, completion rate, engagement)
- [ ] Si une vidéo performe exceptionnellement bien → noter dans le Content Calendar
- [ ] Mettre à jour le hook utilisé dans `02-content/HOOKS_DATABASE.md` (statut ✅)
