# Cahier des Charges

## 1. Objectifs du Projet

### 1.1. Objectif Global
Développer un site web météo en plusieurs étapes, permettant de passer progressivement d'un site statique à un site dynamique avec un serveur backend, tout en intégrant des tests fonctionnels et utilisateur.

### 1.2. Objectif Pédagogique
Acquérir des compétences en HTML, CSS, JavaScript, PHP, et en développement d’applications web dynamiques, ainsi qu’en test de logiciels.

## 2. Phases du Projet

### Phase 1 : Création du Site Statique avec HTML et CSS

#### 2.1. Objectif
Développer la structure et le design de base du site météo en utilisant uniquement HTML et CSS.

#### 2.2. Tâches
- **HTML :** 
  - Créer la structure des pages (header, section principale pour l'affichage de la météo, footer).
  - Intégrer un champ de recherche pour la ville.
- **CSS :** 
  - Styliser le site avec un design épuré et moderne (palette de couleurs, typographie, marges, etc.).
  - Rendre le site responsive pour qu'il s'affiche correctement sur différentes tailles d'écran.

#### 2.3. Livrables
- Une page web statique proprement structurée et stylisée.
- Un design responsive pour une meilleure accessibilité sur mobile.

### Phase 2 : Rendre le Site Dynamique avec JavaScript et Requêtes API

#### 2.1. Objectif
Intégrer des fonctionnalités interactives en utilisant JavaScript et récupérer les données météorologiques en temps réel via une API.

#### 2.2. Tâches
- **JavaScript :**
  - Implémenter la fonctionnalité de recherche de ville avec une requête API vers OpenWeatherMap.
  - Afficher dynamiquement les prévisions météo sur la page en fonction de la ville recherchée.
- **API :**
  - Comprendre et utiliser les endpoints de l'API OpenWeatherMap pour récupérer les données météo.
  - Gérer les erreurs de requête (par exemple, ville non trouvée).

#### 2.3. Livrables
- Un site fonctionnel où l'utilisateur peut rechercher une ville et voir les prévisions météo correspondantes.

### Phase 3 : Conception d'un Serveur PHP pour Rendre le Site Accessible

#### 3.1. Objectif
Créer un serveur backend en PHP pour héberger le site et gérer les requêtes côté serveur.

#### 3.2. Tâches
- **PHP :**
  - Configurer un serveur PHP local pour servir les pages du site.
  - Héberger les fichiers HTML, CSS, et JavaScript sur le serveur PHP.
- **Serveur :**
  - Assurer la mise en place d'un environnement de développement local avec un serveur Apache (par exemple, via XAMPP ou MAMP).
  - Gérer les requêtes HTTP pour rendre le site accessible via le serveur.

#### 3.3. Livrables
- Un site hébergé sur un serveur PHP local, accessible via un navigateur.

### Phase 4 : Dynamisation du Site avec Requêtes au Serveur PHP

#### 4.1. Objectif
Déplacer la logique de traitement des données API sur le serveur PHP pour une meilleure gestion et sécurité.

#### 4.2. Tâches
- **PHP :**
  - Créer des scripts PHP pour interroger l'API OpenWeatherMap.
  - Traiter les données reçues de l'API et renvoyer les résultats au frontend via JavaScript.
  - Mettre en place des mesures de sécurité pour protéger les requêtes API.
- **JavaScript :**
  - Adapter le code JavaScript pour envoyer des requêtes au serveur PHP au lieu de directement à l'API.
  - Afficher les résultats traités par le serveur PHP sur la page.

#### 4.3. Livrables
- Un site où les données météo sont récupérées et traitées par le serveur PHP avant d’être envoyées au frontend.

### Phase 5 : Création de Tests Fonctionnels et Utilisateurs

#### 5.1. Objectif
Tester les fonctionnalités du site pour s'assurer qu'elles fonctionnent correctement et offrir une bonne expérience utilisateur.

#### 5.2. Tâches
- **Tests Fonctionnels :**
  - Écrire des scripts de test pour vérifier que chaque fonctionnalité du site fonctionne comme prévu (par exemple, test de la recherche de ville, test des erreurs).
  - Utiliser des outils comme PHPUnit pour les tests côté serveur.
- **Tests Utilisateur :**
  - Créer des scénarios de test pour simuler l'expérience utilisateur (par exemple, recherche de différentes villes, utilisation sur mobile).
  - Recueillir des retours d'utilisateurs réels ou via des outils de test d'utilisabilité.
- **Corrections :**
  - Identifier et corriger les bugs ou problèmes d'expérience utilisateur.

#### 5.3. Livrables
- Un rapport de tests documentant les résultats des tests fonctionnels et utilisateurs.
- Un site corrigé et optimisé en fonction des tests effectués.

