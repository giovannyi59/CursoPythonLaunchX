# Kata 2 Crear entorno virtual

Primero creamos un entorno virtual mediante ``venv``
![image](images/1.jpg)
* Ejecutamos en la terminal para activar el entorno virtual ``env\Scripts\activate``
 
![image](images/2.jpg)

# Instalamos una biblioteca
Ahora en el entorno virtual podremos intalarlo y saber que solo existe en el entorno virtual. Ejecutamos el comando ``pip freeze``para ver las bibliotecas instaladas en el entorno

![image](images/3.jpg)

Como vemos no aparece nada aún. Ahora instalaremos un paquete para ver como cambia la salida.

* Ejecutamos el comando ``pip install python-dateutil``, para instalar una biblioteca:

![image](images/4.jpg)

* El mensaje de salida nos indica que ya se intaló correctamente.

* Ejecutamos de nuevo el comando ``pip freeze`` para ver como ha cambiado la lista.

![image](images/5.jpg)

# Desactivar entorno virtual

Y ya por ultimo lo unico que haremos será desactivar el entorno virtual, ejecutando el comando ``deactivate``

![image](images/6.jpg)

Ahora la frase ``eve`` se ha quitado de nuetra terminal.
