# BW@

Site personnel de suivi en trois onglets : Roadmap & backlog, Conseils, Implémentation.

Tout tient dans `index.html`, sans étape de compilation. Ouvre le fichier dans un navigateur pour l'utiliser.

Le contenu ajouté n'est pas dans ce dépôt public. Il est enregistré dans un dépôt privé séparé, auquel le site accède avec une clé GitHub propre à chaque navigateur.

On peut aussi se connecter avec un identifiant et un mot de passe, créés depuis le site. Le fichier `auth.json` contient la clé GitHub chiffrée par ce mot de passe (PBKDF2 et AES-GCM) ; ni la clé en clair ni le mot de passe ne sont publiés.
