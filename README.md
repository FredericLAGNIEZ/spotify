# Mkdocs

Installer les paquets nécessaires en paquet système :

```bash
pip install mkdocs-material pymdown-extensions --break-system-packages
```

Verifieer l'installation:

```bash
python3 -c "import material; print('material OK')"
python3 -c "import pymdownx; print('pymdownx OK')"
```