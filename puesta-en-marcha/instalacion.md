# ✨ Instalación

## Python

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption><p>Sitio oficial de Python</p></figcaption></figure>

Dependiendo del sistema operativo que utilicemos, hay varias formas de instalar Python. En las distribuciones de Linux suele venir instalado por defecto, pero nos centraremos en la instalación de Windows. No obstante, todos los tópicos de este libro salvo la instalación, son agnósticos del sistema operativo que se utilice.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption><p>Descargar Python del sitio oficial</p></figcaption></figure>

Como podemos observar, las versiones de Python superiores a la 3.9 ya no son compatibles con Windows 7 en adelante. De cualquier forma, yo personalmente utilizo Windows 10 y es probable que en tu caso estes con mi versión, o la más reciente, Windows 11.

Es importante aclarar que la versión indicada en la captura es la 3.11.4, pero quizá si estás mirando este manual en un futuro próximo, esto cambie. No te preocupes, porque los pasos de instalación son los mismos. Y si hay alguna particularidad en versiones posteriores, voy a agregar información al respecto.

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption><p>Instalador Python en Windows</p></figcaption></figure>

Una vez descargado, nos aparecerá este instalador. Debemos presionar en Install Now, pero antes hacer un check en las dos opciones de debajo. La primera es para instalar Python con privilegios de administración; y la segunda es para agregar Python al PATH, lo cual nos permitirá ejecutarlo desde una terminal.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption><p>Python instalándose...</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption><p>Final Instalación</p></figcaption></figure>

El límite de longitud de ruta en Windows es una restricción que limita la cantidad máxima de caracteres permitidos en la ruta de un archivo o directorio. Esta limitación representa un problema por que las rutas de archivos y directorios largos pueden generar errores durante la instalación de paquetes o al ejecutar scripts.

Debemos presionar la opción "Disable path length limit" al finalizar la instalación de Python, para desactivar esta restricción.

## Validar instalación

Para verificar que todo funcionó correctamente, abriremos la consola (Cmd o PowerShell) y ejecutaremos el comando `python`:

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>Consola Cmd</p></figcaption></figure>

Si arranca una terminal de Python (la mía es v3.9.1, pero no importa), entonces la instalación fue exitosa. En caso de que esto no ocurra, verifica los pasos anteriores, es probable que hayas olvidado poner el check en Python PATH.
