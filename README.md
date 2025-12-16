# nice-green-mobility

Étude et site web sur les transports non polluants à Nice. Ce dépôt contient le site finalisé dans le dossier `www/s106` ainsi que les pages du questionnaire et des analyses.

## Table des matières

- Description
- Contenu du dépôt
- Démarrage rapide
- Déploiement
- Validation
- Où modifier le site
- Auteurs
- Licence

## Description

Le site présente :

- un questionnaire destiné aux habitants et aux touristes ;
- la méthodologie d'enquête et la justification de la taille d'échantillon ;
- une analyse des besoins et des propositions de solutions de mobilité durable ;
- une estimation sommaire des coûts pour les solutions proposées.

## Contenu du dépôt

- `www/s106/` : site web à déposer sur le serveur (page d'accueil : `www/s106/index.html`).
- `www/s106/css/` : feuilles de style.
- `www/s106/QCM/` : questionnaire et pages liées.
- `www/s106/pages-societes/` : pages descriptives des acteurs.
- `auteurs.txt` : fichier obligatoire indiquant le nom du groupe (1ère ligne) puis chaque membre sur une ligne.
- `www/s106/methodologie.html` : page décrivant la méthodologie d'enquête (taille d'échantillon, échantillonnage, collecte via Google Forms).

## Démarrage rapide

1. Ouvrir `www/s106/index.html` dans un navigateur moderne (Chrome, Firefox, Edge).
2. Parcourir les pages via le menu (Sociétés, Questionnaire).
3. Pour tester l'impression : Fichier → Imprimer → Enregistrer en PDF.

## Déploiement

Transférez le dossier `www/s106` sur le serveur de rendu via FTP/SFTP (FileZilla). Le dossier distant doit s'appeler `s106` conformément aux consignes du cours.

## Validation

- Valider le HTML (https://validator.w3.org/) et le CSS (https://jigsaw.w3.org/css-validator/).
- Vérifier que toutes les images ont un attribut `alt`.
- Vérifier le rendu à l'impression (PDF) et s'assurer que les éléments décoratifs n'apparaissent pas sur les pages imprimées.

## Où modifier le site

- Contenu : `www/s106/index.html`, `www/s106/pages-societes/`, `www/s106/QCM/`.
- Styles : `www/s106/css/style.css` et `www/s106/css/qcm.css`.

## Auteurs

La liste des membres du groupe se trouve dans `auteurs.txt` à la racine du dépôt.

## Licence

Consultez le fichier `LICENSE` pour les informations de licence.

```

```
