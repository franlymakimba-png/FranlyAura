# Mettre FRANLY-AURA (démo) en ligne

Ce dossier contient un site complet en un seul fichier : `index.html`.
Il n'a besoin d'aucun serveur ni d'aucune base de données. Il suffit de le déposer chez un hébergeur de sites statiques.

| Fichier | Rôle |
|---|---|
| `index.html` | Le site : application complète, ruban « Démo », guide de test, formulaire d'avis |
| `_headers` | Facultatif. En-têtes de sécurité, lus par Netlify et Cloudflare. Les autres hébergeurs l'ignorent |

## Le plus simple : Netlify Drop

1. Décompressez le zip. Vous obtenez un dossier `franly-aura-demo-public`.
2. Ouvrez https://app.netlify.com/drop dans votre navigateur.
3. Glissez le dossier dans la zone indiquée. Le site reçoit tout de suite une adresse en `netlify.app`.
4. Sans compte, le site reste temporaire. Créez un compte gratuit et « réclamez » le site pour le garder.
5. Ouvrez l'adresse sur votre téléphone, puis envoyez-la à vos proches.

## Autres options

| Plateforme | Où | Ce qu'il faut savoir |
|---|---|---|
| Vercel Drop | https://vercel.com/drop | Compte obligatoire. Accepte un fichier HTML, un dossier ou un zip. Adresse en `vercel.app` |
| Cloudflare Drop | https://cloudflare.com/drop | Glissez le dossier ou le zip. Site temporaire tant que vous ne l'avez pas réclamé avec un compte |
| GitHub Pages | https://github.com | Créez un dépôt public, ajoutez `index.html`, puis Settings > Pages > « Deploy from a branch » > `main` / `(root)`. Adresse en `votrepseudo.github.io/nom-du-depot/` |

Les offres gratuites existent chez ces plateformes. Vérifiez leurs conditions actuelles avant de partager largement.

## Mettre à jour plus tard

- **GitHub** : ouvrez le dépôt, cliquez sur `index.html`, puis sur le crayon (« Edit ») ou, plus simple, sur « Add file > Upload files ». Glissez le nouvel `index.html` (et ce fichier `LISEZ-MOI.md`), écrivez un message de validation (« commit »), puis « Commit changes ». GitHub Pages republie le site en une à deux minutes.
- **Netlify** : onglet Deploys, glissez le nouveau dossier.
- Après une mise à jour, rechargez la page deux fois (ou ouvrez-la en navigation privée) pour être sûr de voir la nouvelle version.
- Les comptes et invitations déjà créés par vos testeurs sont conservés dans leur navigateur : les anciens événements restent utilisables.

## Nouveautés de cette version

- **Catégories personnalisables** : bouton « Gérer » à côté du menu Catégorie pour ajouter, renommer, recolorer ou supprimer les catégories de l'événement.
- **Civilité facultative** (M., Mme, Mlle, Dr, Me, Pr, M. et Mme, et vos propres civilités) à l'ajout et à la modification d'un invité. Elle apparaît sur la carte et dans les messages. Téléphone et e-mail restent facultatifs.
- **Cadre élégant pour les photos** de l'invitation : rectangle aux coins arrondis ou cercle, bordure dorée et lumineuse assortie au thème.
- **Page « Partage & envoi » simplifiée** : plus de lien unique de groupe ni de QR code sur cette page (le QR est au bas de la carte de chaque invité). La liste de tous les invités passe en tête : « Envoyer » propose WhatsApp ou e-mail, et un bouton en bas envoie à tous par WhatsApp.

## Ce qui est différent de la version dans Claude

- Les avis arrivent uniquement par WhatsApp : le bouton « Envoyer par WhatsApp » ouvre une conversation avec +243 84 94 97 444, avec l'avis déjà rédigé. Il n'y a pas de boîte à avis dans la page.
- L'impression, l'ajout à l'agenda (.ics), l'export CSV des réponses et les liens d'images fonctionnent normalement.
- Le site porte `noindex` : les moteurs de recherche ne le référencent pas.
- Chaque nouveau compte reçoit 15 Tokens de bienvenue (démo seulement).

## À savoir avant de rendre le site public

- Le numéro WhatsApp est écrit dans le code de la page : toute personne qui ouvre le site peut le lire.
- Comptes, invitations, listes et Tokens sont enregistrés dans le navigateur de chaque visiteur. Rien n'est envoyé à un serveur, et vous ne voyez pas ce que font les visiteurs.
- Cette version sert à essayer l'application. Pour un vrai lancement avec comptes, Tokens et paiements, il faudra un serveur : un navigateur permet à son propriétaire de modifier ses propres données.
- Les identifiants Super Admin de démonstration s'affichent à l'écran de connexion : ne les utilisez pas pour de vrais événements.

## Vérifier après la mise en ligne

1. Ouvrez l'adresse sur un téléphone, en données mobiles.
2. Créez un compte avec un mot de passe inventé, puis un événement.
3. Téléchargez la liste d'exemple depuis le ruban « Démo > Guide », puis importez-la.
4. Touchez « Donner mon avis » et vérifiez que WhatsApp s'ouvre avec votre numéro.
