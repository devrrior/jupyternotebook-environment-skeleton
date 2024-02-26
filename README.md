# Instalar Jupyternotebook y preparar el ambiente

1. Crear un ambiente virtual con python

   ```bash
   python3 -m venv venv
   ```

2. Activar el ambiente virtual

   Para MacOs y Linux:

   ```bash
   source venv/bin/activate
   ```

   Para Windows:

   ```bash
   venv\Scripts\activate
   ```

3. Instalar dependencias utiles

   ```bash
    pip install -r requirements.txt
   ```

4. Ejecutar Jupyter Notebook

   ```bash
   jupyter notebook
   ```

   Después de ejecutar el comando, te dará una URL para acceder a Jupyter Notebook. Copia y pega la URL en tu navegador.

5. Desactivar el ambiente virtual

   ```bash
   deactivate
   ```
