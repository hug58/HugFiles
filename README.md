

# HugFiles 

<a href="https://twitter.com/hug588"> twitter.com/hug588 </a>
<p> HugFiles sincroniza las carpetas de los clientes con el servidor como dropbox o megasync </p>
<img src='https://github.com/hug58/HugFiles/blob/master/capture.png' >

## Requisitos
<p> Se necesita python 3.6 min para las funciones async/await </p>

## Modulos
<p>El proyecto está dividido en 2 repositorios, el cliente y el servidor, git trae los modulos por defecto vacios asi que para actualizarlos/descargarlos: </p>

```
git submodule init
git submodule update
```
## Setup
<p> todas las dependencias requeridas vienen en requirement.txt, para instalar: </p>

```python
pip install -r requirements.txt
```

Por el momento no hay opciones de sincronizacion de las carpetas del servidor(lo traerá todo).

## Arranque

### Servidor
Inicia en una terminal por separado  ```  app.py y main.py ```

aunque lo ideal seria ejecutarlo en cron(unix)

### Cliente
Con  ```  client.py  ``` es suficiente


### Cliente web

Comprobamos la dirección pública de la api
<img src='https://github.com/hug58/HugFiles/blob/master/app.PNG' >
<br>
Ingresamos (por los momentos solo se puede descargar desde el cliente web)
<br>
<img src='https://github.com/hug58/HugFiles/blob/master/client_web.PNG' >



