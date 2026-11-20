# Digital Bâtiment — Code du site

Version du 20 novembre 2026, incluant le nouvel accueil interactif et la dernière modification de la clôture électrique.

## Ouvrir le site

1. Extraire le ZIP.
2. Ouvrir le dossier dans VS Code.
3. Lancer index.html avec Live Server, ou l’ouvrir directement dans le navigateur.

HTML, CSS et JavaScript purs : aucune commande npm ni base de données nécessaire.

## Mettre sur GitHub

Placer les fichiers de ce dossier à la racine du dépôt : index.html, les autres pages, styles.css, app.js et le dossier assets. Conserver les noms et la structure.

Pour GitHub Pages, sélectionner la branche contenant ces fichiers et le dossier racine dans les paramètres Pages du dépôt.

## Modifier le site

- index.html : accueil
- solutions.html : solutions
- realisations.html : présentation des futures références
- a-propos.html : entreprise
- contact.html : demande de devis
- confidentialite.html : informations sur le formulaire
- styles.css : apparence et adaptation aux écrans
- app.js : navigation, zones interactives, filtres, guide et formulaire
- assets/ : images utilisées
- IMAGE-SOURCES.md : provenance des visuels d’illustration

Le formulaire prépare un message WhatsApp : il ne stocke pas les demandes dans une base de données. Le visiteur doit confirmer l’envoi dans WhatsApp.

Les coordonnées de présentation restent à confirmer : +225 07 02 82 03 26 et digitbat.info@gmail.com. Les photos d’illustration ne constituent pas des réalisations de l’entreprise. Les polices Google Fonts nécessitent Internet ; une police de remplacement est prévue.

Les pages conservent la balise noindex,nofollow de l’aperçu. Pour la version définitive destinée au référencement, supprimer cette balise après validation du contenu.
