# Palette de couleurs du portfolio

> ⚠️ **Palette active (depuis juillet 2026)** — inspiration « retail minimal » :
> fond blanc cassé `#F7F5F2` (token `pale`), pêche doux `#F7DCD1` (`sky`),
> anthracite `#222B38` (`night`, textes), corail `#EE7A5C` (`navy`, accents/boutons),
> gris-bleu `#8A93A3` (`steel`), anthracite profond `#26303E` (`petrol`), corail clair `#F2A48F` (`lagoon`).
> Polices : Plus Jakarta Sans (titres) + DM Sans (texte).
> La palette de bleus ci-dessous est conservée en référence — pour y revenir, il suffit de
> remettre ces valeurs dans le bloc `tailwind.config` des pages.

Palette de référence (dégradé de bleus, du plus sombre au plus clair).

| Aperçu | Code hex | Nom suggéré | Usage recommandé |
|---|---|---|---|
| 🟦 | `#001D39` | Bleu nuit | Fond sombre (remplace `shell #171717`), footer, texte sur fond clair |
| 🟦 | `#0A4174` | Bleu marine | Titres, boutons principaux, liens au survol |
| 🟦 | `#49769F` | Bleu acier | Texte secondaire (remplace `muted`), sous-titres |
| 🟦 | `#4E8EA2` | Bleu pétrole | Accents, bordures d'images, icônes |
| 🟦 | `#6EA2B3` | Bleu lagon | Éléments décoratifs, arrière-plans de sections |
| 🟦 | `#7BBDE8` | Bleu ciel | Pastilles/boutons ronds, surlignage |
| 🟦 | `#BDD8E9` | Bleu pâle | Fonds clairs de sections, séparateurs (remplace `line`) |

## Lisibilité (contraste)

- Texte **blanc** lisible sur : `#001D39`, `#0A4174`, `#49769F`
- Texte **sombre** (`#001D39`) lisible sur : `#7BBDE8`, `#BDD8E9`, blanc
- Éviter le texte sur `#4E8EA2` et `#6EA2B3` sauf en gros caractères

## Intégration Tailwind

À coller dans le bloc `tailwind.config` des pages HTML :

```js
colors: {
  page: '#ffffff',
  shell: '#001D39',   // fond sombre
  ink: '#001D39',     // texte principal
  muted: '#49769F',   // texte secondaire
  line: '#BDD8E9',    // bordures et séparateurs
  accent1: '#0A4174', // bouton/pastille 1 (ex-or)
  accent2: '#4E8EA2', // bouton/pastille 2 (ex-rouge)
  accent3: '#7BBDE8'  // bouton/pastille 3 (ex-turquoise)
}
```

> Palette actuelle du site (avant migration) : or `#e2a400`, rouge `#ef4b2d`, turquoise `#94e1e6`, noir `#171717`.
