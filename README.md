# Portfolio Web – HOUDA RIYAD

Mini Projet 1 – Développement Web | HTML5 & CSS3

---

## Présentation

Portfolio web personnel conçu dans le cadre du Mini Projet 1.  
Le site présente mon parcours académique, mes compétences techniques et mes projets réalisés durant ma formation en Développement Web , Intelligence Artificielle et Systèmes Distribués.

---

## Structure du projet

```
portfolio/
├── index.html
├── styles.css
└── ma_photo.png
```

---

## Sections

- **Hero** – Photo de profil, titre et description courte
- **Expertise Technique** – Compétences organisées par domaine
- **Projets de Master** – Projets réalisés avec description et technologies
- **Parcours Académique** – Timeline des formations
- **Contact** – Email, LinkedIn, GitHub, Téléphone

---

## Choix techniques CSS

**Flexbox** utilisé pour :
- La barre de navigation
- La section hero
- Les boutons de contact

**Grid** utilisé pour :
- La grille des compétences (`skills-wrapper`)
- La grille des projets (`grid-container`)

**Palette de couleurs** (3 couleurs) :
- `#0b0d17` — fond principal
- `#00d2ff` — couleur accent (cyan)
- `#161b22` — fond des cartes

**Responsive design** :
- Media query `@media (max-width: 768px)` → menu hamburger pur CSS, grille en colonne
- Media query `@media (max-width: 480px)` → ajustements mobile

---

## Fonctionnalités

- Navigation sticky avec scroll fluide
- Menu hamburger responsive (pur CSS)
- Animation `fadeInUp` au chargement de la page
- Effets hover sur les cartes, la timeline et les boutons
- Timeline interactive avec effet au survol

---

## Technologies utilisées

- HTML5 sémantique
- CSS3 (Flexbox, Grid, animations, media queries)

---

## Auteur

**Houda Riyad**  
Master en Systèmes Distribués et Intelligence Artificielle – ENSET Mohammedia  
[LinkedIn](https://www.linkedin.com/in/houda-riyad-76a958211/) • [GitHub](https://github.com/houdariyad-etu-gif)
