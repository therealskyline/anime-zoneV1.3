# AnimeZone - Site de Streaming Anime

## Structure du Projet (Reorganisee)

```
anime-zone/
├── api/                      # API Anime-Sama (unique, sans doublons)
│   └── anime_sama_api/       # Module Python pour l'API
│       ├── catalogue.py      # Gestion du catalogue
│       ├── episode.py        # Gestion des episodes
│       ├── season.py         # Gestion des saisons
│       ├── top_level.py      # Point d'entree principal
│       └── ...
├── static/                   # Ressources statiques
│   ├── css/                  # Feuilles de style
│   ├── js/                   # Scripts JavaScript
│   ├── images/               # Images
│   └── data/                 # Donnees JSON (anime.json)
├── templates/                # Templates HTML Jinja2
├── instance/                 # Base de donnees SQLite
├── app.py                    # Application Flask principale
├── main.py                   # Point d'entree
├── data_discover.json        # Donnees pour la decouverte
├── requirements.txt          # Dependances Python
└── replit.md                 # Cette documentation
```

## Changements apportes lors de la reorganisation

1. **Consolidation des dossiers API** : Les deux dossiers identiques `API/` et `src/api/` ont ete fusionnes en un seul dossier `api/` a la racine.

2. **Suppression des fichiers en double** :
   - `src/core/app.py` (supprime, garde celui a la racine)
   - `src/main.py` (supprime)
   - `src/core/web_scraper.py` (supprime)
   - `src/config/` (supprime)
   - `src/scripts/` (supprime)
   - `src/core/static/` (supprime)

3. **Nettoyage de requirements.txt** : Suppression des doublons de dependances.

4. **Mise a jour des chemins** : Les imports dans `app.py` ont ete mis a jour pour pointer vers `api/` au lieu de `API/`.

## Demarrage

L'application demarre automatiquement avec le workflow configure sur le port 5000.

Pour demarrer manuellement :
```bash
python main.py
```

## Technologies

- **Backend** : Flask, SQLAlchemy, Flask-Login
- **Frontend** : HTML/CSS/JavaScript
- **Base de donnees** : SQLite
- **API externe** : anime-sama-api
