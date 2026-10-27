# Personal Bank Sync — pages légales pour Enable Banking

## Personnalisation indispensable
Remplacer toutes les occurrences de `CONTACT_EMAIL_A_REMPLACER` dans `privacy/index.html` et `terms/index.html` par votre adresse de contact.
Lire et adapter les textes à votre stockage et vos pratiques réels : ce sont des modèles, pas un avis juridique.

## Publication gratuite sur GitHub Pages
1. Créez un dépôt GitHub **public** nommé `bank-sync` (le nom peut changer).
2. Décompressez le ZIP ; importez **le contenu** du dossier `bank-sync-pages` à la racine du dépôt (trois éléments : `index.html`, `privacy/`, `terms/`).
3. Ouvrez Settings > Pages > Build and deployment. Choisissez **Deploy from a branch**, branche `main`, dossier `/ (root)` puis Save.
4. Une fois les pages publiées, utilisez :
   - `https://VOTRE-PSEUDO.github.io/bank-sync/privacy/`
   - `https://VOTRE-PSEUDO.github.io/bank-sync/terms/`
5. Testez chaque URL dans un navigateur avant de l'inscrire dans Enable Banking.

## Sécurité
N'envoyez **jamais** votre clé RSA privée `.pem`, token API ou données bancaires sur GitHub. Le dépôt public ne doit contenir que ces fichiers HTML statiques.

## Note
Ce site d'information ne remplace pas le callback OAuth (l'URL de redirection de l'application Enable Banking) ; ce dernier doit être configuré séparément avec l'URL exacte de votre application.
