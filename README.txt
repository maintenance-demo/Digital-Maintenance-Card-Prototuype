DIGITAL MAINTENANCE CARD – VERSION TEST

Contenu :
- index.html : application web
- data.json : données extraites du fichier Excel (Machines, Gammes, Taches_Gammes)

Mise en ligne GitHub Pages :
1. Ouvrir le dépôt GitHub du projet.
2. Remplacer l'ancien index.html par celui de ce dossier.
3. Ajouter data.json dans le même dossier que index.html (à la racine du dépôt si Pages publie la racine).
4. Valider / Commit les changements.
5. Ouvrir l'application avec une URL de ce type :
   https://VOTRE-SITE/index.html?machine=SEW-SNL-FDM-NSNT110461

Pour chaque machine, remplacer la valeur après machine= par son Machine_ID.

Important :
- Tous les QR Codes doivent pointer vers l'URL de l'application avec le Machine_ID correspondant.
- Cette version de test sauvegarde les validations dans le navigateur/appareil utilisé (localStorage).
- Les données ne sont pas encore centralisées entre plusieurs appareils.
- Pour tester en local, utiliser un petit serveur web ou GitHub Pages ; l'ouverture directe file:/// peut bloquer le chargement de data.json.
