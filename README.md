# TekFlix 🎬

Bienvenue sur **TekFlix**, une application Angular de gestion et de découverte de films. Cette plateforme permet aux utilisateurs de parcourir une liste de films, de consulter leurs détails et d'ajouter des films à leurs favoris.

## 🚀 Fonctionnalités principales

- 📄 Navigation fluide grâce au **routing** d'Angular
- 🎥 Liste des films avec détails complets
- ⭐ Ajout de films aux favoris
- 🔍 Fonctionnalité de recherche de films
- 🎨 Interface responsive avec **Bootstrap**
- 🎭 Utilisation d'icônes avec **Font Awesome**

## 🛠️ Technologies utilisées

- [Angular](https://angular.io/)
- [Bootstrap](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/)

## ⚙️ Installation du projet

### 1️⃣ Prérequis

Assurez-vous d'avoir installé :
- [Node.js](https://nodejs.org/)
- [Angular CLI](https://angular.io/cli)

### 2️⃣ Cloner le dépôt

```bash
git clone https://github.com/yosriharraby/TekFlix.git
cd TekFlix
```

### 3️⃣ Installer les dépendances

```bash
npm install
```

### 4️⃣ Installer Bootstrap

```bash
npm install bootstrap
```

Ajoutez cette ligne dans le fichier `angular.json` sous **architect > build > options > styles** :

```json
"node_modules/bootstrap/dist/css/bootstrap.css"
```

### 5️⃣ Installer Font Awesome

```bash
npm install @fortawesome/fontawesome-free
```

Ajoutez cette ligne dans le fichier `angular.json` sous **architect > build > options > styles** :

```json
"node_modules/@fortawesome/fontawesome-free/css/all.min.css"
```

## 💻 Lancer l'application

Pour démarrer l'application en local :

```bash
ng serve --open
```

L'application sera accessible à l'adresse : `http://localhost:4200/`

## 🏗️ Structure des composants

- `HeaderComponent`: Barre de navigation en haut de la page
- `FooterComponent`: Pied de page avec icônes et informations
- `HomeComponent`: Page d'accueil
- `MovieListComponent`: Liste des films
- `MovieDetailComponent`: Détails d'un film spécifique
- `FavoritesComponent`: Liste des films favoris
- `SearchComponent`: Fonction de recherche de films

## 📸 Contenu statique

Ajoutez les images nécessaires dans le dossier `src/assets/public/`.

## 📜 Licence

Ce projet est à but éducatif et réalisé dans le cadre d'un TP Angular.

## **Contact**

If you have any questions or suggestions, feel free to reach out:

- **Author**: Yosri Harraby
- **Email**: yosriharrabi92@gmail.com
- **GitHub**: [yosriharraby](https://github.com/yosriharraby)

---

**Bon codage !** 🚀
