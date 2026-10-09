# Mola

Assistant personnel de bureau, pilotable au clavier ou à la voix : classer,
copier et déplacer des fichiers, ouvrir une application ou un film, créer un
rendez-vous ou une alarme.

Projet en cours de développement.

## Principes

- Le modèle de langage propose une action, le code la valide et l'exécute.
- Toute action destructive demande une confirmation.
- Mola ne dépend d'aucun logiciel précis : il détecte ceux qui sont installés
  et propose d'installer ce qui manque.

## Installation pour le développement

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e ".[dev]"
```

## Vérifications

```bash
ruff check .
ruff format --check .
pytest
```
