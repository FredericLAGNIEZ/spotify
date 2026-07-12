# Mkdocs

Installer les paquets nécessaires en paquet système (Python et pip) :

```bash
sudo apt update
sudo apt install python3 python3-pip
```

Installer Mkdocs :

```bash
pip3 install mkdocs
```
Vérifier que l'installation a réussi :

```bash
mkdocs --version
```

Installer les thèmes :

```bash
pip install mkdocs-material pymdown-extensions --break-system-packages
```

Verifier l'installation:

```bash
python3 -c "import material; print('material OK')"
python3 -c "import pymdownx; print('pymdownx OK')"
```