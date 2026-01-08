# 🐘 Intégration Continue (PHP & MySQL)

Ce projet est un exercice pratique sur la mise en place de tests unitaires et d'intégration connectés à une base de données **MySQL** via l'interface **PDO** (PHP Data Object).

L'objectif est de valider le fonctionnement des requêtes SQL et la logique métier associée dans un contexte d'**Intégration Continue** (CI).

## 🛠️ Stack Technique

* **Langage** : PHP 7.4
* **Base de données** : MySQL
* **Tests Unitaires** : PHPUnit 9.4.2
* **Gestionnaire de paquets** : Composer

## 🚀 Installation

Assurez-vous d'avoir **PHP**, **Composer** et **MySQL** installés sur votre machine.

1. Clonez ce dépôt.
2. Installez les dépendances du projet :

```bash
composer install
```

> **Note :** Si un fichier de configuration de base de données (ex: `config.php` ou `.env`) est nécessaire, pensez à le configurer avec vos identifiants MySQL locaux avant de lancer les tests.

## ✅ Lancer les tests

Pour exécuter la suite de tests automatisés, lancez la commande suivante à la racine du projet :

```bash
vendor/bin/phpunit --bootstrap vendor/autoload.php test
```

---

*Travail pratique réalisé dans le cadre du cours d'**Expertises Digitales et Logicielles** à la **Faculté Polytechnique de l'Université de Mons (UMONS)**.*
