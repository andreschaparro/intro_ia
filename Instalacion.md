1. Python `3.10.11` (no olvidar marcar el checkbox `Add python.exe to PATH`).
2. Extensiones de VCS:
    - `vscode-icons`.
    - `Prettier - Code formatter`.
    - `Palenight Theme`.
    - `Pylint`.
    - `Black Formatter`.
3. Abrir la extension `Palenight Theme`.
4. Click en `Set Color Theme`.
5. Elegir `Palenight Theme`.
6. Abrir una terminal del tipo `Command Prompt`:
7. Ejecutar `python -m pip install --upgrade pip`.
8. Instalar los linters ejecutando:
    - `pip install bandit`.
    - `pip install flake8`.
    - `pip install mypy`.
    - `pip install prospector`.
    - `pip install pycodestyle`.
    - `pip install pydocstyle`.
    - `pip install pylama`.
    - `pip install pylint`.
9. Instalar los fixers ejecutando:
    - `pip install pytest`.
    - `pip install pre-commit`.
    - `pip install black`.
10. `File > Preferences > Settings` marcar `format on save`.
11. Crear el entorno virtual ejecutando:
    - `pip install -U virtualenv`.
    - `virtualenv ia-venv`.
12. Ejecutar `ia-venv\Scripts\activate` para activar el entorno virtual.
13. Ejecutar `ia-venv\Scripts\deactivate` para desactivar el entorno virtual.
14. Instalar los siguientes paquetes en el entorno virtual ejecutando:
    - `pip install numpy`.
    - `pip install scipy`.
    - `pip install statsmodels`.
    - `pip install pandas`.
    - `pip install -U matplotlib`.
    - `pip install seaborn`.
    - `pip install -U scikit-learn`.
    - `pip install torch torchvision torchaudio`.
    - `pip install jupyterlab`.
    - `pip install -U pygame`.
15. Ejecutar `pip freeze > requirements.txt`.
16. Para reinstalar ejecutar `pip install -r requirements.txt`.
17. Ejecutar `jupyter lab`.
