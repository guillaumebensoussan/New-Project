# Basic Dashboard (Dash)

Petit projet Python qui affiche un tableau de bord minimal avec [Dash](https://dash.plotly.com/).

## Fonctionnalités

- Page unique avec un titre et un texte de bienvenue
- Serveur de développement lancé en mode debug

## Prérequis

- Python 3.9+ (recommandé)
- `pip`

## Installation

1. Cloner le dépôt puis se placer dans le dossier.
2. (Recommandé) Créer et activer un environnement virtuel :

```bash
python -m venv .venv
source .venv/bin/activate
```

3. Installer les dépendances :

```bash
pip install dash
```

## Lancer l’application

```bash
python dashboard.py
```

Ensuite, ouvrir l’URL affichée dans le terminal (par défaut `http://127.0.0.1:8050/`).

## Structure du projet

- `dashboard.py` : application Dash (layout + lancement du serveur)
- `test.py` : script de test simple (“Hello World”)

## Notes

- Le serveur est lancé avec `debug=True` (pratique en dev, à désactiver en production).

## Licence

À définir (ex. MIT).
