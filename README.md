# Autolink - Projet Laravel

## Description
Autolink est une application développée avec le framework Laravel...

---

## Prérequis
Avant d’installer le projet, assure-toi d’avoir :
- PHP >= 8.2
- Composer
- SQLite ou MySQL
- Node.js & npm
- Git

---

## Installation

1. Cloner le dépôt :
```bash
git clone https://github.com/HenriJoel03/autolink.git
cd autolink
```

2. Installer les dépendances PHP :
```bash
composer install
```

3. Configurer l'environnement :
```bash
cp .env.example .env
```

4. Générer la clé d'application :
```bash
php artisan key:generate
```

5. Créer la base de données SQLite et lancer les migrations :
```bash
type nul > database\database.sqlite
php artisan migrate
```

6. Installer et compiler les dépendances front-end :
```bash
npm install
npm run dev
```

---

## Lancement du projet

Démarrer le serveur local Laravel :
```bash
php artisan serve
```
Le projet sera accessible sur `http://127.0.0.1:8000`.

---

## Tests

Exécuter la suite de tests :
```bash
php artisan test
```

---

## Structure du projet
- `app/` - Logique métier de l'application
- `database/` - Migrations, factories et base SQLite
- `resources/views/` - Vues Blade et interface utilisateur
- `routes/` - Définition des routes web et API
- `tests/` - Tests unitaires et d'intégration

---

## Collaborateurs
- Henri Joel