# Material para el curso de Virtualización con Docker 
![](https://www.docker.com/sites/default/files/Whale%20Logo332_5.png)

## Docentes

* Lucy Marticorena
* Nahuel Defossé
    
# Conteindos

[Visualizar en Visor liviano de **nbviewer**](https://nbviewer.jupyter.org/github/UNPSJB/eip-docker/tree/master/)

* <a href="01 - Usando Dockerfiles.ipynb">Clase 1 - Usando Dockerfiles</a> | [Visor alternativo](https://nbviewer.jupyter.org/github/UNPSJB/eip-docker/blob/master/01%20-%20Usando%20Dockerfiles.ipynb)
* [Clase 2 - Aislación, Cnecitivdad y Red](02%20-%20Aislación%2C%20Conectividad%20y%20Red.ipynb) | [Visor alternativo](https://nbviewer.jupyter.org/github/UNPSJB/eip-docker/blob/master/02%20-%20Aislaci%C3%B3n%2C%20Conectividad%20y%20Red.ipynb)
* [Clase 3 - Contenedores en Desarrollo](03%20-%20Contenedores%20en%20Desarrollo.ipynb) | [Visor alternativo](https://nbviewer.jupyter.org/github/UNPSJB/eip-docker/blob/master/03%20-%20Contenedores%20en%20Desarrollo.ipynb)
* [Clase 4 - Construcción automática y puesta en producción](04%20-%20Construcción%20automática%20y%20puesta%20en%20Producción.ipynb) | [Visor alternativo](https://nbviewer.jupyter.org/github/UNPSJB/eip-docker/blob/master/04%20-%20Construcci%C3%B3n%20autom%C3%A1tica%20y%20puesta%20en%20Producci%C3%B3n.ipynb)




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
