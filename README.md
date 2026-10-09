
# 🏋️‍♂️ Élan Fitness - Refonte Multipage

Ce projet s'inscrit dans le cadre de la modernisation de la présence digitale d'**Élan Fitness**. L'objectif principal était de migrer le site web existant (format *one-pager*) vers une architecture **multipage** accessible, responsive, optimisée pour le référencement (SEO) et conforme aux standards W3C.

---

## 🌐 Liens du Projet

- **Dépôt GitHub :** `[Lien vers votre repo GitHub]`
- **Site en ligne (GitHub Pages) :** `[Lien vers votre GitHub Pages]`

---

## 🛠️ Ce qui a été réalisé (Périmètre du projet)

### 🎨 Conception & UI/UX
- **Analyse & Découpage :** Audit de l'ancien one-pager et réorganisation des sections en une arborescence logique de 4 pages principales.
- **Identité Visuelle :** Création et intégration d'un logo moderne pour Élan Fitness avec définition d'une charte graphique cohérente (palette de couleurs, typographie sportive et lisible).
- **Contenu & Médias :** Sélection de visuels libres de droits optimisés et rédaction de contenus orientés conversion pour chaque page.

### 💻 Intégration & Développement Front-End
- **Architecture Multipage :**
  - `index.html` : Page d'accueil percutante avec section Hero, atouts du club et appels à l'action (CTA).
  - `programmes.html` : Présentation détaillée des activités, plannings et formules d'abonnement.
  - `a-propos.html` : Histoire d'Élan Fitness, valeurs de la salle et présentation de l'équipe de coachs.
  - `contact.html` : Formulaire de contact fonctionnel avec contrôles HTML5, coordonnées complètes et carte d'accès intégrée.
- **Système de Navigation :** Barre de navigation transverse indiquant dynamiquement la page active (`aria-current="page"` et classe visuelle dédiée).
- **Design Responsive (Media Queries) :** Adaptation complète sur 4 résolutions :
  - Mobile (≤ 767px)
  - Tablette (768px – 1023px)
  - Ordinateurs portables / Petits écrans (1024px – 1279px)
  - Grands écrans (≥ 1280px)
- **Bonus & Améliorations :**
  - Transitions et animations CSS douces au survol (boutons, cartes d'abonnements).
  - Optimisations SEO : balisage sémantique hiérarchisé (`h1`-`h3`), métadonnées Open Graph, balises `meta description` et attributs `alt` informatifs sur toutes les images.
  - Validation du code HTML et CSS sans erreurs critiques sur le validateur W3C.
  - Respect des critères d'accessibilité WCAG (contrastes de couleurs, navigation au clavier, formulaires étiquetés).

---

## 🧠 Compétences Acquises & Maîtrisées (Skills Acquired)

### 1. Intégration Web & Sémantique HTML5
- Structuration sémantique avancée (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- Conception de formulaires accessibles avec gestion des types d'entrée, placeholders, attributs `required` et labels explicites associatifs (`for`/`id`).
- Intégration de médias et d'iframes externes (cartes interactives) respectant les standards W3C.

### 2. Styling Avancé & CSS3 Moderne
- Utilisation des variables CSS (`:root`) pour assurer la cohérence du design system.
- Maîtrise des modèles de mise en page **Flexbox** et **CSS Grid** pour des alignements fluides et modulaires.
- Écriture de feuilles de styles adaptatives via des **Media Queries** ciblées (approche *Mobile-First*).
- Conception de micro-interactions et transitions fluides pour dynamiser l'expérience utilisateur.

### 3. Accessibilité Web (A11y & WCAG)
- Prise en compte du contraste des couleurs texte/fond selon le standard WCAG AA.
- Structuration du focus pour la navigation au clavier.
- Implémentation des attributs ARIA essentiels (`aria-current`, `aria-label`, rôles de repérage).

### 4. SEO On-Page (Référencement Naturel)
- Configuration des balises d'en-tête `<title>` et `<meta name="description">` personnalisées par page.
- Intégration du protocole Open Graph pour un partage optimal sur les réseaux sociaux.
- Optimisation du ratio texte/image et description textuelle alternative (`alt`).

### 5. Méthodologie & Versioning (Git / GitHub)
- Découpage fonctionnel des tâches via Trello / méthode Agile (User Stories & critères d'acceptation).
- Gestion du cycle de vie du code sous Git (commits clairs et atomiques).
- Déploiement automatisé et hébergement sur **GitHub Pages**.

---

## 📂 Structure du Répertoire

```text
elan-fitness/
├── index.html              # Page d'accueil
├── programmes.html         # Page des cours et tarifs
├── a-propos.html           # Page de présentation du club
├── contact.html            # Page de contact et localisation
├── css/
│   ├── style.css           # Styles principaux et variables
│   └── responsive.css      # Media queries pour mobile/tablette
├── assets/
│   ├── images/             # Images optimisées et illustrations
│   └── logo/               # Logo Élan Fitness (SVG/PNG)
└── README.md               # Documentation du projet et des acquis