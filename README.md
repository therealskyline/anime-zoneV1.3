
# AnimeStream

Site de streaming d'anime avec une interface moderne et une grande collection d'anime.

## Caractéristiques

- Navigation intuitive dans les séries d'anime
- Interface moderne et responsive
- Découverte de nouvelles séries 
- Système de compte utilisateur
- Progression de visionnage sauvegardée
- Liste de favoris personnalisée
- Recherche et filtrage avancés
- Support multi-langues (VOSTFR/VF)

## Installation

1. Clonez le dépôt
2. Installez les dépendances : `pip install -r requirements.txt`
3. Lancez l'application : `python run.py`

Le site sera accessible à l'adresse : http://0.0.0.0:8080

## Structure du projet

- `app.py` : Application principale Flask
- `run.py` : Script de démarrage
- `static/` : Ressources statiques (CSS, JS, images)
- `static/data/` : Base de données locale des animes
- `templates/` : Templates HTML
- `API/` : API Anime-Sama pour la récupération des données

## Développement

Pour lancer le serveur en mode développement :

```bash
python run.py
```

## Licence

Ce projet est sous licence MIT.
