# Proyecto Python-a-z

Este proyecto está configurado con un entorno virtual Conda llamado `ENV2` y está preparado para ciencia de datos, notebooks, y desarrollo modular en Python.

## Estructura
- `notebooks/`: análisis y pruebas en Jupyter
- `src/`: código fuente principal
- `data/`: datasets (locales o descargados)
- `environment.yml`: entorno reproducible

## Activación del entorno
```bash
conda activate ENV2

#### ✅ `.gitignore`
```gitignore
# Ignorar archivos temporales de Python
__pycache__/
*.pyc

# VS Code
.vscode/

# Jupyter
.ipynb_checkpoints/

# Entornos
env/
ENV2/
.venv/

# Datos
data/
*.csv
*.json

# Otros
*.env
.DS_Store