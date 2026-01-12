# nice-green-mobility

Étude et site web sur les transports non polluants à Nice.

Ce dépôt contient le site web finalisé dans `www/s106/` (pages publiques, questionnaires et ressources CSS/images).

## Table des matières

- Description
- Contenu du dépôt
- Aperçu local
- Déploiement
- Validation
- Où modifier le site
- Auteurs
- Licence

## Description

Le site présente :

- un questionnaire (différentes tranches d'âge) ;
- la méthodologie d'enquête et les pages de résultats ;
- des fiches descriptives des acteurs (sociétés, opérateurs) ;
- les styles et ressources pour le rendu public.

## Contenu du dépôt

- `www/s106/` : site web à copier sur le serveur (page d'accueil : `www/s106/index.html`).
- `www/s106/css/` : feuilles de style (globales et QCM).
- `www/s106/QCM/` : questionnaires HTML et pages de résultats.
- `www/s106/pages-societes/` : pages descriptives des sociétés étudiées.
- `auteurs.txt` : nom du groupe (1ère ligne) puis chaque membre sur une ligne.
- `LICENSE` : licence du projet.

## Aperçu local (rapide)

Si vous voulez prévisualiser le site localement, ouvrez un terminal dans le dossier `www/s106` et lancez un serveur HTTP simple :

```bash
# depuis la racine du dépôt
cd www/s106
# servir sur http://localhost:8000
python3 -m http.server 8000
```

Ensuite ouvrez `http://localhost:8000/index.html` dans votre navigateur.

## Déploiement

Copiez le dossier `www/s106` sur le serveur de production (FTP/SFTP). Le dossier distant doit idéalement s'appeler `s106` si le serveur attend ce nom.

## Validation

- Validez le HTML avec https://validator.w3.org/.
- Validez le CSS avec https://jigsaw.w3.org/css-validator/.
- Vérifiez que toutes les images ont un attribut `alt`.
- Testez l'impression (export PDF) pour vous assurer que la feuille de style d'impression masque les éléments décoratifs.

## Où modifier le site

- Contenu HTML : `www/s106/index.html`, `www/s106/pages-societes/`, `www/s106/QCM/`.
- Styles : `www/s106/css/style.css` et `www/s106/css/qcm.css`.
- Images : `www/s106/css/img/` et `www/s106/QCM/resultat qcm/img/`.

## Auteurs

La liste des membres du groupe se trouve dans `auteurs.txt` à la racine du dépôt.

## Licence

Voir le fichier `LICENSE` à la racine du dépôt pour les informations de licence.
