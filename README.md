🔹 1. Crear el entorno virtual
Ubícate en la carpeta donde tienes tus notebooks y ejecuta:

python3 -m venv .venv

Esto crea la carpeta .venv/ que contendrá todo el Python aislado.

🔹 2. Activar el entorno
En macOS:

source .venv/bin/activate

Cuando esté activado vas a ver (.venv) al inicio de tu terminal.
Si luego querés salir:

deactivate

🔹 3. Instalar dependencias
Con el entorno activo, instala las librerías que necesitas:

pip install -r requirements.txt

⚠️ tkinter normalmente ya viene instalado con Python en macOS. Si te diera error, tendrías que instalarlo con Homebrew:
brew install python-tk

🔹 4. Ejecutar Jupyter Notebook
Ya con todo instalado, abre tus notebooks:

jupyter notebook

o si prefieres la nueva interfaz:

jupyter lab

