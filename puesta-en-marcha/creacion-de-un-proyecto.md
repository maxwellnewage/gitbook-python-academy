# 🚀 Creación de un Proyecto

## Entorno Virtual

A la hora de crear un proyecto en Python, lo más recomendable es crear un entorno virtual. Si conocen [Docker](https://www.docker.com/), esto sería lo más similar a crear un contenedor específico para cada proyecto.

Básicamente se trata de un conjunto de aplicaciones, entre ellas un gestor de dependencias (pip), que nos permiten correr este proyecto y mantenerlo aislado de los demás entornos.

Utilizaremos virtualenv, que ya viene instalado con Python por defecto. Primero creamos una carpeta donde estará nuestro proyecto (yo voy a usar la terminal):

```
mkdir mi_proyecto
```

Luego crearemos el entorno utilizando el módulo venv y creando una carpeta por el mismo nombre:

```
python -m venv venv
```

Esto puede parecerte complejo de entender, pero en el futuro lo veremos más en detalle cuando creemos nuestros propios módulos. De momento sígueme la corriente 😉.

Luego de crear el entorno, abriemos VSC desde la misma terminal con el comando:

```
code .
```

El comando `code` inicia VSC, y el parámetro punto indica que lo abra en la misma carpeta donde estamos parados, osea `mi_proyecto`.

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>VSC Abierto</p></figcaption></figure>

Ahora crearemos nuestro primer archivo llamando main.py, el cual contendrá este script:

```python
if __name__ == '__main__':
    print("Hola Mundo!")

```

Y lo ejecutamos desde la terminal (podemos abrir la de VSC en el menú Terminal -> New Terminal):

```
python main.py
```

La salida será:

```
Hola Mundo!
```

Entiendo que quizá hayan algunos elementos que te tomaron por sorpresa, ¡pero tranquilo!, aprendemos todo en su momento.

Lo importante es que generaste tu primer script en Python: con la función `print` imprimiste un mensaje en consola. ¡Acabas de dar tu primer paso en el camino del desarrollo!&#x20;
