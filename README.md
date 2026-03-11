# 🍒 CherryPick Bible

> Source de vérité du projet CherryPick — AI influencer persona ciblant la communauté dev/indie hacker.
> Ce repo contient toute la stratégie, le contenu, l'identité visuelle, les process et le business.
> Le code technique (pipeline de génération image/vidéo, automatisation) vit dans le repo séparé `cherrypick-engine`.

## Quickstart

1. Lire `01-foundation/PERSONA.md` — comprendre qui est CherryPick
2. Lire `01-foundation/STRATEGY.md` — comprendre comment on exécute
3. Lire `06-operations/DAILY_CHECKLIST.md` — savoir quoi faire aujourd'hui

## Structure du repo

```
cherrypick-bible/
│
├── 01-foundation/                 # LA BIBLE — source de vérité stratégique
│   ├── PERSONA.md                 # Identité, voix, ton, personnage, masque vénitien
│   ├── ALGORITHM_TIKTOK_2026.md   # Mécanique de distribution TikTok 2026
│   ├── STRATEGY.md                # Playbook d'exécution multi-plateforme
│   └── MONETIZATION.md            # Sources de revenus, projections, timeline
│
├── 02-content/                    # CONTENU — machine à production éditoriale
│   ├── HOOKS_DATABASE.md          # 50+ text overlays classés par pattern
│   ├── CONTENT_CALENDAR.md        # Planning hebdo + tracking publication
│   ├── CAPTIONS_TEMPLATES.md      # Templates de captions TikTok / YouTube / Instagram
│   └── CONTENT_IDEAS_BACKLOG.md   # Pipeline d'idées à produire
│
├── 03-visual/                     # IDENTITÉ VISUELLE — cohérence image
│   ├── VISUAL_GUIDE.md            # Palette, fonts, style, règles visuelles
│   ├── PROMPTS_IMAGE.md           # Prompts FLUX pour générer les personnages
│   └── PROMPTS_VIDEO.md           # Prompts Kling Motion Control + paramètres
│
├── 04-technical/                  # PIPELINE — comment produire concrètement
│   ├── PIPELINE.md                # Workflow step-by-step de la trend au post
│   ├── TOOLS_AND_ACCOUNTS.md      # Inventaire outils, comptes, accès
│   └── CROSS_POSTING.md           # Règles d'adaptation par plateforme
│
├── 05-business/                   # BUSINESS — tout ce qui génère de l'argent
│   ├── MEDIA_KIT.md               # Kit de prospection brand deals
│   ├── AFFILIATE_REGISTRY.md      # Programmes d'affiliation, liens, commissions
│   └── BRAND_TARGETS.md           # CRM des marques cibles + statut prospection
│
└── 06-operations/                 # OPS — exécution quotidienne
    ├── DAILY_CHECKLIST.md         # Routine quotidienne de publication
    ├── WEEKLY_REVIEW_TEMPLATE.md  # Template review hebdo (métriques + décisions)
    └── TROUBLESHOOTING.md         # Guide de résolution des problèmes
```

## Conventions

- **Un fichier = un sujet.** Pas de duplication d'information entre fichiers.
- **Les fichiers `01-foundation/` sont la source de vérité.** Les autres fichiers peuvent y faire référence mais ne doivent jamais contredire.
- **Chaque fichier a une date de dernière mise à jour** en haut du document.
- **Les décisions stratégiques** sont documentées avec un `[DÉCISION]` tag et la date.
- **Les chiffres et projections** sont toujours sourcés ou marqués comme estimations.

## Repos liés

| Repo | Description | Accès |
|------|-------------|-------|
| `cherrypick-bible` | Ce repo — stratégie, contenu, business | Fabrice (+ Romain en lecture) |
| `cherrypick-engine` | Pipeline technique — scripts Python, API, automatisation | Fabrice uniquement |

## Ownership

- **CherryPick est un projet autonome.** Il n'est structurellement lié à aucun autre projet.
- Toute connexion future avec d'autres projets (funnel, cross-promo) sera documentée dans `01-foundation/STRATEGY.md` comme décision stratégique, pas comme dépendance technique.

---

> Dernière mise à jour : 1 mars 2026
