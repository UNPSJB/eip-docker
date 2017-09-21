# Material para el curso de Virtualización con Docker 
![](https://www.docker.com/sites/default/files/Whale%20Logo332_5.png)

## Docentes

* Lucy Marticorena
* Nahuel Defossé
    
# Conteindos

* <a href="01 - Usando Dockerfiles.ipynb">Clase 1 - Usando Dockerfiles</a> | [Visor alternativo](https://nbviewer.jupyter.org/github/UNPSJB/eip-docker/blob/master/01%20-%20Usando%20Dockerfiles.ipynb)
* [Clase 2 - Aislación, Contectividad y Red](02 - Aislación, Conectividad y Red.ipynb) | [Visor alternativo](https://nbviewer.jupyter.org/github/UNPSJB/eip-docker/blob/master/02%20-%20Aislaci%C3%B3n%2C%20Conectividad%20y%20Red.ipynb)
* [03 - Contenedores en desarrollo](03%20-%20Contenedores%20en%20Desarrollo.ipynb)
* []()

# Ver este material offline

## Usando Jupyter local

Con el software pip instalar:
```
pip install jupyter
```
y luego:
```
jupyter notebook 
```
en el directorio actual, y hacer click en el link que muestre en la consola.

## Con contenedores

Este material fue elaborado con Jupyter, para visualizarlo (y ejecutarlo)
offline podemos usar el contenedor de Jupyter, utilizando un volumen para
compartir la copia (ya sea descarga del zip o git clone).

Recordar que $(pwd) es un comand de linux y se substituye por la carpeta/directorio actual, en Windows probalemente se obtenga con `%cd%`.

```
docker run -p 8888:8888 -v $(pwd):/home/jovyan                                
``` 
