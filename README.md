# Steps
## Paso previo en MacOS
para que : code . funcione he arrancado Vscode y he instalado code en el Shell
## Paso 1
crear el archivo : .gitignore Utilizando la página web gitignore.io y configurando los parametros de los sistemas operativos, windows, linux y macOS, además del lenguaje python. Obtenemos el codigo y generamos el archivo.

## Paso 2
crear este mismo archivo README.md para el repositorio de Github donde documentaré los pasos realizados

## Paso 3
Conectar Github con el directorio del proyecto en nuestra maquina:
git remote add origin git@github.com:jrgsanta/curso-python-pip.git

## Paso 4
Subir los dos archivos al repositorio de github usando las siguientes instrucciones en el terminal:
git add .
git commit -m "comentario"
git push origin main

## Game

para ejecutar el juego ejecuta
```sh
cd game
python main.p
```
# Ambientes virtuales
Se trata de diferentes entornos en la instalación de Python de forma que en cada uno de ellos podemos tener unas versiones diferentes de cada una de las librerias
## Para activar un ambiente virtual debemos de ejecutar la siguiente instrucción dentro del directorio
```sh
python3 -m venv env 
```
(el último env es el nombre del entorno virtual
```sh
source env/bin/activate 
pip3 install matpltlib==3.5.0
```
(activa el entorno virtual) una vez activado podemos instalar dependencias especificas que podemos ver con
```sh
pip3 freeze
```
Para desactivar el entorno simplemente escribimos
```sh
deactivate
```
# instalación de dependencias
1. Generar las dependencias en un fichero
2. Recrear las dependencias

```sh
pip3 freeze > requirements.txt 
pip3 install -r requirements.txt
```

# App Project
```sh
git clone
cd game
python3 -m venv env-game 
source env-game/bin/activate
pip3 install -r requirements.txt
python3 main.py
```
