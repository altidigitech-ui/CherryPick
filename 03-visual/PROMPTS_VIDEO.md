# 🍒 CherryPick — Prompts de Génération Vidéo (Kling Motion Control)

> Paramètres et prompts pour animer les images CherryPick via Kling Motion Control (fal.ai).
> Input : une image générée avec les prompts de `03-visual/PROMPTS_IMAGE.md` + une vidéo de référence (trend TikTok).
> Output : une vidéo 5-10s du personnage CherryPick reproduisant le mouvement de la trend.
>
> Dernière mise à jour : 1 mars 2026

---

## Configuration API Kling Motion Control

| Paramètre | Valeur recommandée |
|-----------|-------------------|
| Modèle | Kling v2.6 Standard (ou dernière version) |
| Mode | Motion Control (image + vidéo de référence) |
| Durée | 5 secondes (Format A/B) / 10 secondes (Format E, combiner 2 clips) |
| Résolution | 1080x1920 (9:16) |
| FPS | 24 fps |

---

## Comment ça marche

```
INPUT 1 : Image CherryPick (générée via FLUX)
     +
INPUT 2 : Vidéo de référence (trend TikTok téléchargée)
     ↓
KLING MOTION CONTROL
     ↓
OUTPUT : Vidéo du personnage CherryPick reproduisant le mouvement de la trend
```

Le Motion Control extrait le mouvement/la pose de la vidéo de référence et l'applique au personnage de l'image source. C'est ce qui permet de faire "danser" CherryPick sur les trends sans motion capture.

---

## Prompt vidéo standard

Le prompt vidéo guide Kling sur le style d'animation souhaité. Il complète le Motion Control.

### Pour les trends danse (Format A)

```
A confident seductive woman in a Venetian mask performing smooth dance movements. Cinematic lighting with subtle neon accents, dark background. Fluid natural motion, realistic body movement. Professional quality, no artifacts.
```

### Pour les mouvements lents / walk (Format A)

```
A confident seductive woman in a Venetian mask walking slowly toward camera with authority. Dramatic lighting with neon rim light, dark background. Smooth natural movement, subtle head tilt. Professional quality, no artifacts.
```

### Pour le format éducatif statique (Format E)

```
A confident seductive woman in a Venetian mask, subtle slow movements, slight head turns, gentle gestures. Studio setting with neon accent lights, dramatic lighting. Minimal motion, composed and authoritative. Professional quality, no artifacts.
```

---

## Workflow de génération

### Étape 1 : Préparer la vidéo de référence

1. Télécharger la trend TikTok (SnapTik, SSSTik, sauvegarde manuelle)
2. Couper les 5 premières secondes (la partie la plus reconnaissable du mouvement)
3. S'assurer que le format est 9:16 et la qualité correcte
4. Si la trend fait >5s, découper en segments de 5s

### Étape 2 : Choisir l'image source

1. Sélectionner une image CherryPick depuis le batch généré (voir `03-visual/PROMPTS_IMAGE.md`)
2. L'image doit avoir une pose compatible avec le mouvement de la trend
3. Éviter les images trop serrées (gros plan) pour les trends avec mouvement du corps

### Étape 3 : Générer la vidéo

1. Uploader l'image source + la vidéo de référence dans Kling Motion Control
2. Ajouter le prompt vidéo adapté (voir ci-dessus)
3. Lancer la génération (temps estimé : 3-6 minutes)
4. Vérifier le résultat (voir checklist ci-dessous)

### Étape 4 : Pour le Format E (1-2 min)

Le Format E nécessite des vidéos plus longues que les 5-10s standard de Kling.

**Méthode : combiner plusieurs clips**

1. Générer 2-3 clips de 5-10s avec des poses/mouvements légèrement différents
2. Utiliser des images source différentes (même personnage, pose différente)
3. Assembler en post-production (CapCut) avec des transitions
4. Ajouter les écrans de texte entre les transitions
5. Le résultat donne une vidéo de 1-2min avec des changements de plan naturels

---

## Checklist qualité vidéo

- [ ] Le masque reste en place pendant tout le mouvement (pas de déformation)
- [ ] Le mouvement est fluide (pas de saccades ou de glitches)
- [ ] Le visage ne se déforme pas (pas d'uncanny valley)
- [ ] Les mains sont correctes (pas de doigts en trop ou déformés)
- [ ] Le vêtement suit le mouvement naturellement
- [ ] L'éclairage reste cohérent pendant toute la vidéo
- [ ] Le format est bien 9:16 / 1080x1920
- [ ] Pas de watermark fal.ai ou Kling visible

---

## Problèmes courants et solutions

| Problème | Cause probable | Solution |
|----------|---------------|----------|
| Masque qui disparaît ou se déforme | Mouvement trop rapide ou complexe | Choisir un segment de trend avec des mouvements plus lents |
| Visage uncanny valley | Image source de qualité insuffisante | Regénérer l'image FLUX avec un guidance scale plus élevé |
| Mouvement rigide | Prompt trop vague | Ajouter des détails de mouvement dans le prompt |
| Artefacts visuels | Résolution trop basse ou modèle surchargé | Relancer la génération (les résultats varient) |
| Mains déformées | Problème classique des modèles génératifs | Recadrer pour masquer les mains ou regénérer |
| Durée trop courte | Kling limité à 5-10s | Combiner plusieurs clips (méthode Format E) |

---

## Paramètres API (pour cherrypick-engine)

```json
{
  "model": "kling-v2.6-standard",
  "mode": "motion_control",
  "duration": 5,
  "resolution": "1080x1920",
  "fps": 24,
  "image_url": "<URL_IMAGE_FLUX>",
  "reference_video_url": "<URL_VIDEO_TREND>",
  "prompt": "<PROMPT_ADAPTÉ>",
  "negative_prompt": "deformed, blurry, low quality, watermark, text, glitch, artifact, uncanny valley"
}
```

*Les scripts d'appel API sont dans le repo `cherrypick-engine`.*
