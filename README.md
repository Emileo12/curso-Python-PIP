# Mi primer proyecto en el curso de Python PIP
# Game Project

Para correr el juego debes seguir las siguientes instrucciones
en la terminal:

``` sh
cd game
python 3 main.py

```
Pagina para librerias en PIP: https://pypi.org/

``` sh
git clone
cd game
python3 -m venv env
source env/Scripts/activate
pip3 install -r requirements.txt
```

### para crear un requirements: pip3 freeze > requirements.txt
 
# web-server

Para cargar la pagina web
```sh
cd web-server
uvicorn main:app --reload
```
Y copiamos el link que nos da y pegamos en nuestro navegador