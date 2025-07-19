
# Proyecto Web - PokéAPI + API Propia

Este proyecto consiste en una aplicación web que consume datos de la API pública PokéAPI y permite a los usuarios agregar sus propios Pokémon a través de un formulario, almacenando la información en una base de datos local mediante una API creada con FastAPI.

## Tecnologías Utilizadas

- HTML, CSS, JavaScript
- Python 3
- FastAPI
- SQLite
- SQLAlchemy

## Instrucciones para Ejecutar

1. Clona el repositorio:
   ```
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
   ```

2. Instala las dependencias:
   ```
   pip install -r requirements.txt
   ```

3. Ejecuta el servidor de FastAPI:
   ```
   uvicorn main:app --reload
   ```

4. Abre el archivo `index.html` en tu navegador.

## Manual de Usuario

- En la parte superior se muestran los Pokémon obtenidos desde la PokéAPI.
- Debajo se encuentran los Pokémon creados por el usuario mediante el formulario.
- El formulario permite agregar un Pokémon indicando su nombre, descripción e imagen.
# entrega_progra
