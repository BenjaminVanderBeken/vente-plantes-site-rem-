🌿 Celosia Plantes
Site web vitrine pour une boutique de vente de plantes d'intérieur. Projet réalisé en HTML5 et CSS3.
📋 Description
Celosia Plantes est un site e-commerce fictif proposant des plantes d'intérieur avec des conseils d'entretien personnalisés. Le site met en avant une approche éco-responsable avec des producteurs locaux et des emballages recyclés.
🗂️ Structure du projet
celosia-plantes/
├── index.html          # Page d'accueil
├── catalogue.html      # Catalogue des plantes
├── conseils.html       # Conseils d'entretien
├── apropos.html        # Page À propos
├── contact.html        # Formulaire de contact
├── css/
│   ├── style.css       # Styles principaux
│   └── Responsive.css  # Media queries
└── images/             # Images du site
🖥️ Pages du site
PageDescriptionAccueilHero section avec mise en avant des avantages (éco-responsable, livraison, conseils)CatalogueGrille de 4 plantes avec filtres (catégorie, prix) et fiches détailléesConseils3 guides d'entretien : arrosage, lumière, rempotageÀ proposHistoire de l'entreprise et engagementsContactFormulaire complet avec validation
🎨 Technologies utilisées
HTML5

Structure sémantique (<header>, <main>, <footer>, <article>, <section>, <aside>)
Accessibilité avec attributs ARIA (aria-label)
Formulaires avec validation native (required, type="email", type="tel")

CSS3

Variables CSS pour les espacements et rayons
Flexbox pour la navigation et la page À propos
CSS Grid pour les layouts complexes :

Hero : grid-template-columns: 55% 40%
Catalogue : repeat(4, 1fr)
Conseils : repeat(3, 1fr)
Contact : 60% 36%


Unités relatives (rem) pour une meilleure accessibilité

📱 Responsive Design
Le site est entièrement responsive et s'adapte automatiquement aux différentes tailles d'écran :
AppareilBreakpointAdaptationDesktop> 1024pxAffichage complet avec toutes les fonctionnalitésTablette768px - 1024pxLayout adapté pour une consultation confortableMobile< 768pxNavigation optimisée et contenu réorganisé
<details>
<summary>🎯 Clique pour en savoir plus</summary>
Breakpoints CSS
css/* Mobile < 768px */
@media (max-width: 768px) { ... }

/* Tablette 768px–1024px */
@media (min-width: 768px) and (max-width: 1024px) { ... }
Adaptations par section

Hero : Passe de 2 colonnes (55%/40%) à 1 colonne
Catalogue : 4 → 2 → 1 colonne(s)
Conseils : 3 → 2 → 1 colonne(s)
Contact : Formulaire et aside empilés sur mobile

</details>
🎯 Choix techniques
ChoixDescriptionHTML5 sémantiqueUtilisation des balises appropriées (header, nav, main, section, article, aside, footer)CSS purAucune dépendance externe, pas de frameworkArchitecture modulaireCSS organisé en fichiers logiques et réutilisablesMobile-firstApproche responsive prioritaire
<details>
<summary>🌐 Clique pour en savoir plus</summary>
Variables CSS
css:root {
  --space-xxs: 0.25rem;
  --space-xs: 0.5rem;
  --space-s: 0.75rem;
  --space-m: 1rem;
  --space-l: 1.5rem;
  --space-xl: 2rem;
  --radius: 0.5rem;
}
Layouts utilisés

Flexbox : Navigation, page À propos
CSS Grid : Hero, catalogue, conseils, contact, footer

</details>
🌐 Compatibilité navigateurs
Le site est compatible avec :
NavigateurSupportChrome/Edge✅ Dernières versionsFirefox✅ Dernières versionsSafari✅ Dernières versionsOpera✅ Dernières versions
📝 Formulaires
Page Contact

Nom, email, téléphone
Menu déroulant (sujet)
Boutons radio (urgence)
Zone de texte (message)
Case à cocher RGPD

Newsletter (footer)

Champ email avec placeholder
Bouton d'inscription

🌱 Plantes du catalogue
PlantePrixMonstera deliciosa15 €Sansevieria8 €Pilea10 €Ficus elastica15 €
🚀 Installation

Cloner le dépôt :

bashgit clone https://github.com/votre-repo/celosia-plantes.git

Ouvrir index.html dans un navigateur

Aucune dépendance externe requise.
📄 Licence
© 2025 Celosia Plantes — Tous droits réservés.

Projet réalisé dans le cadre d'un cours de développement web.
