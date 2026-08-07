# 🎀 Prévent'Invaders — Défendez votre santé

> Mini-jeu arcade HTML5 Canvas de sensibilisation au dépistage du cancer du sein — **Octobre Rose**
> Intégré à [PréventIA-LaB](https://laurebonnefond.github.io/PreventIA-LaB)

---

## 🎯 Concept

Un jeu de tir inspiré des classiques de l'arcade, entièrement dédié à la **prévention du cancer du sein**.

Le joueur incarne une **infirmière de santé au travail** sur une plateforme volante. Il doit **neutraliser les facteurs de risque évitables** (alcool, tabac, sédentarité, malbouffe, surpoids, travail de nuit) tout en **protégeant les gestes de prévention** (dépistage, activité physique, mammographie, consultation…).

**Tirer sur un bonus = malus.** Le joueur doit distinguer risques et actions protectrices.

---

## 🕹️ Gameplay

| Action | Clavier | Mobile |
|--------|---------|--------|
| Déplacer | ← → ou A/D | Boutons ◀ ▶ |
| Tirer | Espace / ↑ / W | Bouton 🎀 |

- **Vagues progressives** : plus rapides, plus denses, nouveaux ennemis
- **Boss tous les 5 niveaux** : Baron Tabac, Monstre Alcool, Roi Sédentarité, Géant Désinformation, Titan Travail de Nuit
- **Système de combo** : enchaîner les éliminations multiplie le score
- **Messages pédagogiques** (sources INCa / Santé publique France) affichés à chaque ennemi neutralisé

---

## 🎨 Direction artistique

- Palette **Octobre Rose** : rose, violet, bleu nuit, turquoise, doré
- Fond **parallaxe animé** : ciel étoilé, nébuleuses, rubans flottants, skyline urbaine
- **Pixel art chibi** : infirmière casque rose, ruban, croix médicale
- **Particules** : explosions roses, étoiles, confettis, traînées lumineuses
- **Canvas Retina** (`devicePixelRatio`) pour rendu HD/4K

---

## 📋 Facteurs de risque (ennemis)

| Sprite | Facteur | Source |
|--------|---------|--------|
| 🍷 | Alcool | INCa — risque augmenté même à faible dose |
| 🚬 | Tabac | INCa — facteur majeur de nombreux cancers |
| 🛋️ | Sédentarité | SPF — favorise le surpoids |
| 🍔 | Alimentation déséquilibrée | INCa — alimentation riche en graisses |
| ⚖️ | Surpoids | INCa — risque accru post-ménopause |
| 🌙 | Travail de nuit | CIRC — groupe 2A (probable) |

## 🛡️ Gestes protecteurs (bonus)

| Icône | Action | Points |
|-------|--------|--------|
| 🎀 | Dépistage | +200 |
| 🏃 | Activité physique | +150 |
| 🥦 | Fruits et légumes | +150 |
| 📋 | Mammographie | +250 |
| 🩺 | Consultation | +200 |
| 🤱 | Allaitement | +200 |
| ❤️ | Sensibilisation | +150 |

---

## ⚙️ Caractéristiques techniques

- **Fichier HTML unique** — zéro dépendance externe
- **Canvas 2D** avec support Retina (`devicePixelRatio`)
- **Audio** : Web Audio API (tir, explosion, bonus, malus, boss, victoire, défaite)
- **Responsive** : PC, tablette, smartphone (contrôles tactiles)
- **60 FPS** avec système de particules optimisé
- **Scores** enregistrés en `localStorage`
- **~1 350 lignes** de code commenté

---

## 🚀 Intégration

### Option 1 — Page autonome
Placer `prevent-invaders.html` à la racine du repo et y accéder via :
```
https://laurebonnefond.github.io/PreventIA-LaB/prevent-invaders.html
```

### Option 2 — Lien depuis index.html
Ajouter dans la section « Apprendre en s'amusant » de la homepage :
```html
<a href="prevent-invaders.html">🎀 Prévent'Invaders — Défendez votre santé</a>
```

---

## 📚 Sources scientifiques

- **INCa** — Institut National du Cancer : facteurs de risque et de protection du cancer du sein
- **Santé publique France** — Programme national de dépistage organisé
- **CIRC/IARC** — Classification du travail de nuit (groupe 2A)
- **HAS** — Recommandations dépistage 50–74 ans

---

## 📜 Licence

Projet éducatif non commercial — **PréventIA-LaB** · Octobre Rose 🎀

*Créé par Laure Bonnefond — IDE-ST & Préventrice — SPSTI 23/87*
