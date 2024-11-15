# Practico Especial
TP de Calidad agua del rio de la plata - Fundamentos de la ciencia de datos.


# Requisitos

1_ Tener python 3.12.5 instalado. (Se puede verificar al ingresar en una terminal el codigo "python --versión" sin las comillas.)

2_ Tener Git Instalado.

3_ Tener un IDE instalado (De preferencia Visual Studio Code).

4_ Tener Jupyter o Jupyterlab instalado .


# Creación del entorno (Necesario antes de intentar abrir el archivo .ipynb)
Pasos:
1_ Elegir la carpeta en donde se descargara el repositorio

2_ Dentro de la carpeta destino hacer click derecho y seleccionar "git bash here", se debería abrir una consola de comandos.

3_ Dentro de la consola colocar los comandos "git init" y "git clone https://github.com/SOAgustin/PracticaEspecial.git" para iniciar y clonar el repositorio en la carpeta destino

4_ Abrir el IDE a usar (Por ejemplo: Visual Studio Code).

5_ Desde el IDE buscar la sección de archivos y luego la de abrir una carpeta. La carpeta a abrir debe ser la descargada del repositorio (en este caso se llama "PracticaEspecial").

6_ Aun dentro del IDE abrir una terminal (Verificar que la terminal se encuentre sobre la carpeta abierta. Debería verse algo similar a esto: "PS C:\<Direccion de la ubicación de la carpeta descargada>\PracticaEspecial>") y colocar el siguiente comando comprendido entre las comillas dobles: "python -m venv PracticaEspecialVenv". Esto creara un entorno virtual dentro de la carpeta descargada (Una nueva carpeta llamada PracticaEspecialVenv).

7_ Ingresar el comando encerrado entre comillas ".\PracticaEspecialVenv\Scripts\activate" si estás trabajando sobre windows, si es en mac ingresa este otro "source PracticaEspecialVenv/bin/activate". Este paso activara el entorno provocando que ahora la terminal se vea similar a esto: "(PracticaEspecialVenv) PS C:<Direccion de la ubicación de la carpeta descargada>\PracticaEspecial> "

8_ Ingresar el comando encerrado entre comillas: "python install -m requirements.txt". Al hacerlo se comenzaran a instalar todas la librerías necesarias para la normal ejecución del archivo "PracticoEspecial.ipynb". (Se debe esperar a que todas las librerias se instalen correctamente, notificado en la terminal de una manera similar a "Successfully installed package-<Listado de paquetes instalados>")

9_ Ahora ya puede navegar sobre el archivo "PracticoEspecial.ipynb".
