# CEIA - Procesamiento del Lenguaje Natural I

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Repositorio para el curso de Procesamiento del Lenguaje Natural I de la Carrera de Especialización en Inteligencia Artificial (CEIA) - FIUBA.

## Submódulo
El repositorio incluye un submódulo con el contenido del curso:

```
procesamiento_lenguaje_natural/  (rama: set_2026)
└─ https://github.com/FIUBA-Posgrado-Inteligencia-Artificial/procesamiento_lenguaje_natural
```

Para inicializar y descargar el submódulo después de clonar el repositorio:

```bash
git submodule update --init --recursive
```

## Entorno y dependencias (uv)

Este repo usa [uv](https://docs.astral.sh/uv/) para gestionar las dependencias a nivel de proyecto usando `pyproject.toml`.

Requisitos previos:
- Python 3.10 o superior
- uv instalado (ver https://docs.astral.sh/uv/)

Pasos típicos:
- Instalar dependencias principales:
  ```bash
  uv sync
  ```
- Instalar también las herramientas de desarrollo (Jupyter):
  ```bash
  uv sync --extra dev
  ```
- Ejecutar un notebook (desde la raíz del repo):
  ```bash
  uv run jupyter notebook
  ```

Nota: uv creará un entorno virtual dentro del proyecto (`.venv/`).

## Licencia

Este proyecto está licenciado bajo Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Para más detalles, consulta el archivo [LICENSE](LICENSE).
