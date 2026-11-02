# 🏭 L'Usine Linguistique • English Factory (PWA)

> **Application d'apprentissage incrémental de l'anglais** basée sur le modèle d'ingénierie cognitive et grammaticale *« Monde Linguistique »* (Fiches 1 à 25 + Synthèses A/B + Correctifs Critiques).

---

## 🌟 Présentation de l'Application

L'application s'articule autour de **3 piliers complémentaires** :

1. **L'Atelier Logique (Chemin 1) :**
   - **9 Paliers Incrémentaux** avec **27 défis interactifs** d'assemblage de briques syntaxiques et de diagnostics linguistiques.
   - **Scanner 3 Niveaux (Fiche A) :** Atomes (Nature N1) ➔ Boîtes (Syntagmes N2) ➔ Usine (Métiers N3).
   - **Encyclopédie Intégrale :** Consultation des **25 fiches techniques**, des synthèses et des **4 correctifs critiques** avec moteur de recherche et filtres.

2. **L'Entrepôt des Boîtes (Chemin 2) :**
   - **6 Boîtes Thématiques (144 briques au total)** : *Cuisine, Maison, Voyage, Travail, Nature, Pensée & Connecteurs*.
   - **3 Modes d'acquisition :** Inspection & Catalogue, Flashcards 3D interactives, Frappe Rapide avec indices et suivi de séries.
   - Possibilité d'ajouter ses propres briques personnalisées dans chaque boîte.

3. **Le Laboratoire Sonore (Chemin 3) :**
   - **12 Chaînes Évolutives (60 Dictées Poupées Russes)** : on commence par 2 ou 3 mots, puis plus on avance, plus la phrase s'allonge avec de nouvelles briques.
   - **Moteur d'Écoute Haute Fidélité :** Vitesse normale (1.0x), vitesse ralentie pour l'oreille (0.75x) et mode **Mot à Mot**.
   - Diagnostic vocal et orthographique en temps réel mot par mot.

---

## 🚀 Comment mettre ce dossier sur GitHub en 1 minute

### Méthode 1 : Directement sur le site GitHub (Sans rien installer - Recommandé !)
1. Rendez-vous sur [github.com](https://github.com/) et connectez-vous.
2. Cliquez sur le bouton vert **« New »** pour créer un nouveau dépôt (*Repository*).
3. Donnez-lui un nom (par exemple : `usine-linguistique` ou `english-factory`).
4. Choisissez **Public**, ne cochez *pas* "Add a README" (le dossier en a déjà un), puis cliquez sur **« Create repository »**.
5. Sur la page qui s'affiche, cliquez sur le lien bleu **« uploading an existing file »** (*téléverser un fichier existant*).
6. **Glissez-déposez TOUS les fichiers** du dossier `Usine_Linguistique_PWA` dans la fenêtre GitHub :
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `README.md`
   - `.gitignore`
7. Cliquez sur le bouton vert en bas : **« Commit changes »**. C'est en ligne !

### Méthode 2 : Avec GitHub Desktop
1. Ouvrez **GitHub Desktop**.
2. Allez dans `File` > `Add Local Repository...`
3. Sélectionnez le dossier : `Usine_Linguistique_PWA`.
4. Cliquez sur **Create a Repository** si demandé, puis sur **Publish repository**.

---

## 🌐 Comment activer l'hébergement gratuit (GitHub Pages)

Pour que l'application fonctionne comme un site web et puisse être **téléchargée comme une vraie application** sur votre téléphone :

1. Sur votre dépôt GitHub, cliquez sur l'onglet **Settings** (Paramètres ⚙️) en haut.
2. Dans le menu de gauche, descendez et cliquez sur **Pages**.
3. Dans la section **Build and deployment** :
   - Source : laissez **Deploy from a branch**.
   - Branch : sélectionnez **main** (ou **master**) et le dossier **/ (root)**.
   - Cliquez sur **Save**.
4. Patientez 1 minute puis rafraîchissez la page : GitHub vous donne votre lien HTTPS personnel, par exemple :  
   👉 `https://VOTRE-PSEUDO.github.io/usine-linguistique/`

---

## 📲 Comment télécharger & installer l'application sur votre appareil

L'application est une **Progressive Web App (PWA)** complète. Elle s'installe sur votre écran d'accueil avec sa propre icône, fonctionne en plein écran et sans les barres de navigateur :

### 📱 Sur Android (Google Chrome, Brave, Edge, Samsung Internet)
1. Ouvrez votre lien GitHub Pages dans le navigateur de votre téléphone.
2. Cliquez sur le bouton **« Installer l'Appli »** directement dans l'application,  
   *OU* appuyez sur le menu (les **3 petits points ⋮**) en haut à droite.
3. Choisissez **« Installer l'application »** ou **« Ajouter à l'écran d'accueil »**.
4. L'icône de l'Usine Linguistique apparaît sur votre écran d'accueil !

### 🍏 Sur iPhone & iPad (Safari)
1. Ouvrez votre lien GitHub Pages dans **Safari**.
2. Appuyez sur le bouton **Partager** (le carré avec la flèche pointant vers le haut ⬆️ en bas de l'écran).
3. Faites défiler vers le bas et touchez **« Sur l'écran d'accueil »** (Add to Home Screen).
4. Appuyez sur **Ajouter** en haut à droite.
5. L'application est installée comme une appli de l'App Store !

### 💻 Sur Ordinateur (PC Windows / Mac / Linux)
1. Ouvrez votre lien dans Chrome ou Edge.
2. Cliquez sur le bouton **« Installer l'Appli »** dans la barre du haut,  
   *OU* sur la petite icône d'ordinateur/écran qui apparaît tout à droite de la barre d'adresse.
3. Cliquez sur **Installer**. L'application a sa propre fenêtre indépendante !

---

## 📁 Contenu du Dossier

```
Usine_Linguistique_PWA/
├── index.html           # L'application complète autonome (9 Paliers, 25 Fiches, Boîtes, Audio)
├── manifest.json        # Fichier d'identité PWA (nom, couleurs, icônes)
├── sw.js                # Service Worker (mise en cache et mode hors-ligne)
├── icon-192.png         # Icône HD 192x192 pour mobiles
├── icon-512.png         # Icône HD 512x512 haute résolution
├── .gitignore           # Fichiers ignorés
└── README.md            # Guide complet de déploiement et d'installation
```

---

*Développé selon le modèle architectural « Monde Linguistique » — Tous droits réservés.*
