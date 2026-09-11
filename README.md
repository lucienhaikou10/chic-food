# Chic Food - Site Vitrine One-Page (Bootstrap 5)

**Projet personnel réalisé en totale autonomie (en solo)** en **2025**, en parallèle de ma deuxième année d'université.  
Ce projet a été conçu dans le cadre de mon auto-apprentissage du framework **Bootstrap 5**, avec pour objectif de développer de A à Z un **site vitrine One-Page** moderne, interactif et responsive pour un restaurant gastronomique fictif : **Chic Food**.

---

## Contexte et Objectifs

Ce projet personnel visait à maîtriser par la pratique les compétences fondamentales de l'intégration web moderne :
- **Découverte et apprentissage en solo de Bootstrap 5** : utilisation de la grille à 12 colonnes, des breakpoints responsive et des composants UI natifs.
- **Responsive Web Design (RWD)** : conception d'une interface adaptée aux smartphones, tablettes et ordinateurs de bureau.
- **Surcharge et personnalisation CSS** : personnalisation de la charte graphique par-dessus Bootstrap (palette de couleurs, typographies personnalisées, ombrages, effets *backdrop-filter*).
- **Interactivité front-end** : mise en œuvre des composants interactifs de Bootstrap (onglets dynamiques de la carte, carrousels en boucle, fenêtre modale de réservation, menu burger repliable).
- **Sensibilisation à l'expérience utilisateur (UX)** : structuration d'un parcours client clair (découverte du concept, consultation des variétés et tarifs, formulaire de prise de contact/réservation).

---

## Fonctionnalités Réalisées

1. **Navigation One-Page Responsive :**
   - Barre de navigation fixe (*sticky*) avec effet de flou élégant en arrière-plan.
   - Menu burger optimisé pour les écrans tactiles.
   - Liens d'ancrage avec défilement fluide (*Smooth Scroll*) vers les différentes sections.

2. **Bannière d'Accueil Immersive (Hero Banner) :**
   - En-tête plein écran valorisant l'atmosphère du restaurant.
   - Boutons d'action (*Call-to-Action*) dirigeant directement vers la réservation et la commande.

3. **Section Histoire et Savoir-Faire :**
   - Présentation de la démarche culinaire, des produits frais et de la salle.
   - Carrousel imbriqué présentant les créations du chef.

4. **Carte Interactive avec Onglets :**
   - Système d'onglets dynamiques Bootstrap (`nav-tabs`) permettant de basculer instantanément entre :
     - *Nos Plats Phares*
     - *Entrées et Tapas*
     - *Desserts et Douceurs*
   - Cartes de présentation avec photos, descriptions des ingrédients et tarifs clairs en euros.

5. **Carrousel Grand Format ("Les Délices Interdits") :**
   - Carrousel en fondu (*carousel-fade*) mettant en valeur les spécialités phares et suggestions du chef.

6. **Modale Interactive de Réservation / Commande :**
   - Formulaire pop-up complet (nom, contact, nombre de couverts, date, créneau horaire et demandes particulières).

7. **Pied de Page Complet (Footer) :**
   - Horaires d'ouverture, coordonnées physiques, téléphone, réseaux sociaux et inscription à la newsletter.

---

## Technologies Utilisées

| Technologie | Rôle dans le projet |
| :--- | :--- |
| **HTML5** | Balisage sémantique, structuration et accessibilité |
| **CSS3** | Styles personnalisés, variables et adaptations graphiques |
| **Bootstrap 5.3.5** | Framework responsive, grille, carrousels, onglets et modales |
| **Google Fonts** | Polices de caractères *Merriweather* (sérif) et *Redressed* (cursif) |
| **Font Awesome 6** | Icônes vectorielles pour l'interface |
| **Git et GitHub** | Gestion de versions et publication du code source |

---

## Installation et Visualisation Locale

Le projet étant purement statique, aucune installation lourde n'est requise.

1. **Cloner le projet :**
   ```bash
   git clone https://github.com/<votre-pseudo>/<nom-du-repo>.git
   ```

2. **Lancer le site :**
   - Ouvrez directement le fichier `index.html` dans votre navigateur favori.
   - Ou lancez un mini-serveur local avec Python :
     ```bash
     python -m http.server 8000
     ```
     Puis ouvrez `http://localhost:8000` dans votre navigateur.

---

## Déploiement en Ligne (GitHub Pages)

Ce projet est optimisé pour un hébergement gratuit et rapide via **GitHub Pages** :
1. Dans votre dépôt GitHub, ouvrez **Settings** > **Pages**.
2. Sous **Branch**, sélectionnez `main` et le dossier `/ (root)`.
3. Cliquez sur **Save**.
4. Le site sera accessible en ligne en moins de 2 minutes.

---

## Auteur

- **[Lucien HAIKOU](https://www.linkedin.com/in/lucienhaikou10)**  
  *Développeur web — Projet personnel réalisé en solo (2025, 2ᵉ année d'université).*
