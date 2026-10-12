# Site d'assistance Sereno

Deux pages statiques, sans installation ni compilation :

- `index.html` : assistance et questions frequentes.
- `confidentialite.html` : politique de confidentialite.
- `styles.css`, `logo.png`, `.nojekyll` : presentation et publication.

## Mise en ligne gratuite sur GitHub Pages

1. Creer et activer `sereno.assistance@gmail.com`, puis verifier que la boite recoit les messages.
2. Sur GitHub, creer un nouveau depot **public** nomme `sereno-support` dans le compte `Magiik06`.
3. Via "Add file" > "Upload files", envoyer le contenu de ce dossier a la racine du depot. `index.html` doit etre a la racine, pas dans un sous-dossier `site-assistance`.
4. Enregistrer les fichiers avec "Commit changes". Pour ce site HTML simple, l'absence du fichier cache `.nojekyll` lors d'un envoi manuel n'est pas bloquante.
5. Dans le nouveau depot : "Settings" > "Pages" > "Build and deployment".
6. Choisir "Deploy from a branch", la branche `main` et le dossier `/(root)`, puis "Save".
7. Attendre la publication et ouvrir le lien affiche par GitHub. Verifier les deux pages et le lien de contact.

Le depot est public afin de beneficier de GitHub Pages gratuit. Publier uniquement les fichiers du site dans ce nouveau depot.

## Liens a renseigner dans App Store Connect

Avec le nom de depot et le compte ci-dessus, les liens attendus sont :

- URL d'assistance : https://magiik06.github.io/sereno-support/
- URL de confidentialite : https://magiik06.github.io/sereno-support/confidentialite.html

Ces adresses ne deviennent utilisables qu'apres la publication reussie. Utiliser le lien reel indique dans GitHub Pages si le nom du depot ou du compte differe.

## Dans l'application

Apple demande aussi un lien accessible vers la politique de confidentialite dans l'application. Apres la mise en ligne, ajouter les liens publics dans les Reglages de Sereno puis fabriquer et envoyer un nouveau build avant la soumission App Store.

## Apercu local

Ouvrir `index.html` dans un navigateur. Les pages utilisent uniquement des fichiers locaux et fonctionnent sans serveur.

## Mise a jour

Modifier les fichiers et les envoyer dans le meme depot. GitHub Pages republiera le site. Actualiser la politique si le fonctionnement de l'application change, notamment en cas de synchronisation, de connexion bancaire ou d'ajout de statistiques.

References :

- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://developer.apple.com/app-store/review/guidelines/#privacy
