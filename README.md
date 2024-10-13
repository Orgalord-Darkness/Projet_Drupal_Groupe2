# Installation de Drupal 11 avec XAMPP

## Prérequis
- **XAMPP** (Assurez-vous qu'il est à jour ou installez-le si nécessaire).
- **Composer** pour la gestion des dépendances PHP.

## Installation

### Étape 1 : Installer ou mettre à jour XAMPP
- Téléchargez et installez [XAMPP](https://www.apachefriends.org/fr/index.html) si ce n'est pas déjà fait.
- Vérifiez que la version de PHP et de MariaDB fournie par XAMPP est compatible avec Drupal 11. 

### Étape 2 : Télécharger Drupal 11
- Rendez-vous sur le site officiel de Drupal et téléchargez la version ZIP de Drupal 11 à l'adresse suivante :  
  [Télécharger Drupal 11](https://www.drupal.org/download).

### Étape 3 : Extraire Drupal dans le répertoire `htdocs`
- Une fois le fichier ZIP téléchargé, extrayez-le dans le répertoire `htdocs` de votre installation XAMPP (par défaut, cela devrait être `C:\xampp\htdocs` sous Windows).
- Renommez le dossier extrait si nécessaire, par exemple `drupal`.

### Étape 4 : Installer Composer
- Si Composer n'est pas encore installé, téléchargez-le et installez-le depuis [le site officiel de Composer](https://getcomposer.org/download/).
- Une fois installé, naviguez dans le répertoire du projet Drupal (par exemple `C:\xampp\htdocs\drupal`) et exécutez `composer install` pour installer les dépendances nécessaires.

### Étape 5 : Lancer Drupal dans le navigateur
- Ouvrez votre navigateur et rendez-vous à l'adresse suivante : http://localhost/NOM_DU_DOSSIER_DRUPAL
(Remplacez `NOM_DU_DOSSIER_DRUPAL` par le nom du dossier où vous avez extrait Drupal, par exemple `drupal`).

- Suivez les instructions de l'installation standard de Drupal. Assurez-vous que la version de PHP et de MariaDB utilisées sont compatibles avec Drupal 11. Drupal vérifiera automatiquement ces prérequis pendant l'installation.

---

## Utilisation

1. Une fois l'installation terminée, vous pouvez accéder à votre site Drupal en allant à l'URL suivante : http://localhost/NOM_DU_DOSSIER_DRUPAL

Vous serez redirigé vers la page d'accueil de votre site Drupal.

2. Pour administrer votre site, connectez-vous avec les informations d'identification définies lors de l'installation.

---

## Notes supplémentaires

- **Mises à jour :** Utilisez Composer pour mettre à jour Drupal et ses modules : composer update


- **Environnement local :** Si vous travaillez en local, pensez à configurer les permissions du répertoire pour éviter des problèmes d'écriture avec les fichiers temporaires et le cache.

Pour plus de détails, consultez la documentation officielle de Drupal sur [drupal.org](https://www.drupal.org/documentation).
