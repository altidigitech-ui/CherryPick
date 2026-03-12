# 🍒 CherryPick — Prompts de Génération d'Images (FLUX)

> Prompts testés et validés pour générer les images du personnage CherryPick via fal.ai FLUX.
> Ces prompts sont la base du pipeline. Copier-coller dans l'API ou l'interface fal.ai.
> Référence visuelle : `03-visual/VISUAL_GUIDE.md`
>
> Dernière mise à jour : 1 mars 2026

---

## Configuration API fal.ai

| Paramètre | Valeur recommandée |
|-----------|-------------------|
| Modèle | FLUX 1.1 Pro (ou dernière version disponible) |
| Résolution | 768x1344 (portrait 9:16) ou 1024x1792 |
| Guidance scale | 7.5-8.5 |
| Steps | 28-35 |
| Seed | Fixer un seed pour reproduire un résultat réussi |

---

## Prompt maître (base de tous les prompts)

Ce prompt de base produit le personnage CherryPick standard. Les variations sont des ajouts à ce prompt.

```
A confident young woman wearing an elegant Venetian masquerade mask, black and gold ornate design, looking directly at camera with piercing eyes through the mask. Fitted black dress with subtle cleavage, accentuating her silhouette. Dramatic cinematic lighting with subtle cyan neon accents, dark moody background, studio setting. Professional fashion photography style, shallow depth of field, 9:16 portrait orientation. Hyper-realistic, photographic quality, no text, no watermarks.
```

---

## Variations du personnage

### Variation 1 — Bordeaux séduisant

```
A confident young woman wearing an ornate Venetian masquerade mask in deep burgundy and gold, looking directly at camera with a seductive gaze. Wearing a fitted burgundy bodysuit, subtle neckline. Dramatic side lighting with violet neon rim light, dark studio background. Professional fashion photography, cinematic mood, shallow depth of field, 9:16 portrait. Hyper-realistic, photographic quality, no text, no watermarks.
```

### Variation 2 — Tech futuriste

```
A confident young woman wearing a sleek black and silver Venetian masquerade mask, looking directly at camera with intensity. Fitted black top with mesh details, accentuating silhouette. Dark environment with cyan neon strip lights in the background. Futuristic tech aesthetic, dramatic lighting, shallow depth of field, 9:16 portrait. Hyper-realistic, photographic quality, no text, no watermarks.
```

### Variation 3 — Rooftop urbain nuit

```
A confident young woman wearing an elegant gold Venetian masquerade mask, standing on a rooftop at night, city lights and neon signs blurred in the background. Black leather jacket over a fitted top showing silhouette. Dramatic backlit cinematic lighting with violet ambient glow, moody atmosphere. Fashion photography style, shallow depth of field, 9:16 portrait. Hyper-realistic, photographic quality, no text, no watermarks.
```

### Variation 4 — Gros plan masque (pour thumbnails)

```
Close-up portrait of a confident young woman wearing an ornate black and gold Venetian masquerade mask. Only face and upper shoulders visible, bare shoulders with thin strap detail. Intense seductive eye contact through the mask. Dramatic Rembrandt lighting with subtle cyan neon accent on one side, dark background. Studio fashion photography, extreme shallow depth of field, 9:16 portrait. Hyper-realistic, photographic quality, no text, no watermarks.
```

### Variation 5 — Assise / pose décontractée

```
A confident young woman wearing an elegant Venetian masquerade mask, sitting in a dark setting, legs crossed, one arm resting casually. Fitted dress accentuating curves, subtle cleavage. Dark interior with violet and cyan neon accent lights in background. Editorial fashion photography, cinematic mood, shallow depth of field, 9:16 portrait. Hyper-realistic, photographic quality, no text, no watermarks.
```

---

## Négatif prompt (à utiliser systématiquement)

```
cartoon, anime, illustration, painting, drawing, 3D render, CGI, watermark, text, logo, deformed, ugly, blurry, low quality, oversaturated, bright background, smiling broadly, teeth showing, childlike, costume party, carnival, cheap mask, plastic mask, nudity, explicit, NSFW, lingerie, underwear, bikini, corporate suit, blazer, formal business attire
```

---

## Checklist qualité après génération

- [ ] Le masque vénitien est clairement visible et élégant (pas un masque de carnaval cheap)
- [ ] Le regard passe à travers le masque avec intensité
- [ ] L'éclairage est dramatique et cinématique
- [ ] Le fond est sombre et non distrayant
- [ ] Pas de déformations visibles (mains, doigts, masque asymétrique)
- [ ] Le personnage a l'air réaliste (pas d'uncanny valley)
- [ ] Le format est bien en portrait (9:16)
- [ ] Aucun texte ou watermark dans l'image
- [ ] La tenue est élégante et cohérente avec le personnage

---

## Seeds à conserver

Quand un résultat est particulièrement réussi, noter le seed ici pour pouvoir le reproduire ou le varier.

| Seed | Variation utilisée | Description | Qualité |
|------|--------------------|-------------|---------|
| | | | |

---

## Notes de production

- **Générer en batch** : produire 5-10 images à la fois, sélectionner les meilleures.
- **Varier les poses** : éviter de toujours avoir la même pose. Le viewer doit voir de la diversité.
- **Varier l'apparence** : comme défini dans `01-foundation/PERSONA.md`, l'ethnie, la couleur de cheveux, et le teint changent à chaque vidéo. Ajouter des modifiers au prompt : "dark-skinned", "East Asian features", "light brown skin", "pale skin with freckles", "dark curly hair", "straight platinum blonde hair", etc. Le masque est le seul élément fixe — tout le reste varie.
- **Tester les nouvelles versions FLUX** : quand fal.ai met à jour le modèle, re-tester le prompt maître.
- **L'image est le point de départ de la vidéo** : une bonne image = une bonne vidéo Kling. Ne pas tricher sur la qualité.
