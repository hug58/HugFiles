# HugFiles
<p> HugFiles sincroniza las carpetas de los clientes con el servidor como dropbox o megasync </p>

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
pip install requirements.txt
```

Por el momento no hay opciones de sincronizacion de las carpetas del servidor(lo traerá todo).

## Arranque

### Servidor
Inicia en una terminal por separado  ```  apy.py y main.py ```

aunque lo ideal seria ejecutarlo en cron(unix)

### Cliente
Con  ```  client.py  ``` es suficiente
  
