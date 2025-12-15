# Instructions pour lancer AnimeZone

Pour démarrer le site web AnimeZone, suivez ces instructions simples :

## 1. Lancer le site original

```bash
python run.py
```

Cette commande va :
- Arrêter les serveurs existants (si nécessaire)
- Démarrer l'application sur le port 8080
- Précharger les animes populaires
- Créer la base de données si nécessaire

## 2. Accéder au site

Une fois le serveur démarré, vous pourrez accéder au site à l'adresse :
http://localhost:8080 ou http://0.0.0.0:8080

## 3. Se connecter

- Créez un compte en utilisant la page de Register
- Connectez-vous avec vos identifiants

## 4. Profiter des fonctionnalités

- Parcourez les animes disponibles
- Regardez des épisodes
- Téléchargez des épisodes
- Marquez vos favoris

---

Le site est organisé de manière simple avec :
- `app.py` : Application principale Flask
- `run.py` : Script pour démarrer le serveur
- `static/` : Dossier contenant CSS, JS et données
- `templates/` : Dossier contenant les pages HTML
- `requirements.txt` : Liste des dépendances

Si vous rencontrez des problèmes, vérifiez les messages d'erreur dans la console.