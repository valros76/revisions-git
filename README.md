# Configuration à ajouter au projet
Pour des raisons de sécurité, le fichier de configuration n'est pas inclus dans ce repository.

Pour que le projet fonctionne, merci d'ajouter un dossier **config**, dans le dossier **app**, et d'y ajouter les instructions suivantes : 
```json
{
  "autoloadFolders": [
    "framework",
    "controllers",
    "models",
    "models/entity",
    "models/manager",
    "framework/exceptions",
    "utils"
  ],
  "database": {
    "host": "VOTRE_HOST",
    "dbname": "VOTRE_BDD",
    "username": "VOTRE_USERNAME",
    "password": "VOTRE_PASSWORD"
  },
  "basepath": "app"
}
```

***Pensez à modifier les informations de connexion à la base de données.***