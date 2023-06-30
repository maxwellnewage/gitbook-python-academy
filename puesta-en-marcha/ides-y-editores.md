# 🐝 IDEs y Editores

## Concepto y Distinción

Un **IDE** (Entorno de Desarrollo Integrado) y un **editor de texto** son herramientas utilizadas en programación, pero tienen **diferencias significativas** en cuanto a funcionalidad y características.

Un **editor de texto** es una aplicación que se utiliza para crear y editar archivos de texto sin formato. Proporciona **funciones básicas** como resaltado de sintaxis, búsqueda y reemplazo; y puede ser utilizado para editar código fuente. Los editores de texto suelen ser ligeros y rápidos de usar, y son adecuados para tareas de edición sencillas. Algunos ejemplos populares de editores de texto son Sublime Text, Atom, Notepad++ y **Visual Studio Code** (este es el que utilizaremos en el manual).

Por otro lado, **un IDE es un entorno de desarrollo completo** que combina un editor de texto con herramientas y características adicionales diseñadas para facilitar y agilizar el desarrollo de software. Además de las funcionalidades de edición de texto, un IDE suele ofrecer capacidades de depuración, autocompletado de código, integración con sistemas de control de versiones, compilación y ejecución de programas, administración de proyectos y más. Los IDEs **son más pesados** y proporcionan un conjunto completo de herramientas para el desarrollo de aplicaciones. Algunos ejemplos conocidos de IDEs son PyCharm, Visual Studio, Eclipse y IntelliJ IDEA.

En resumen, mientras que un editor de texto es una herramienta básica para editar código fuente y archivos de texto, un IDE ofrece un conjunto más completo de características y herramientas para facilitar el desarrollo de software, desde la escritura de código hasta la depuración y la administración del proyecto. La elección entre un editor de texto y un IDE depende del tipo de proyecto, las necesidades del desarrollador y las preferencias personales.

## PyCharm

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p>Editor abierto</p></figcaption></figure>

[Tengo un curso de Udemy](https://www.udemy.com/course/desarrollo-de-sitios-web-con-python-3-con-django/?referralCode=A491B0944C634BFAA48C) donde explico cómo desarrollar web utilizando Python y Django; y en el mismo me centro en trabajar con el IDE [PyCharm](https://www.jetbrains.com/es-es/pycharm/). La razón simplemente radica en que me sentía cómodo con este editor. El problema es que tiene [dos versiones](https://www.jetbrains.com/products/compare/?product=pycharm\&product=pycharm-ce): una paga (Profesional) y otra gratuita (Comunitaria). Yo estaba usando la comunitaria, pero encontré muchas limitaciones marcadas que me hicieron decantar por terminar utilizando [Visual Studio Code](https://code.visualstudio.com/).

Sin embargo, lo considero una excelente herramienta para desarrollar en Python, y pueden seguir este libro sin ningún problema si deciden elegir este IDE.

## Visual Studio Code

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption><p>Editor abierto</p></figcaption></figure>

Probablemente el editor de código más amado del planeta. VSC se destaca por su flexibilidad a la hora de preparar un entorno acorde a las necesidades que tengamos. Recomiendo descargarlo desde su [sitio oficial](https://code.visualstudio.com/):

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption><p>Sitio oficial VSC</p></figcaption></figure>

Es importante aclarar que el sitio detecta el sistema operativo, por lo cual si estas utilizando Linux o Mac, aparecerán opciones distintas. Una vez descargado (en el caso de Windows), es cuestión de darle al botón "Siguiente" hasta finalizar.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption><p>Instalador VSC</p></figcaption></figure>

Una vez finalizada la instalación y abierto el edtiro, recomiendo instalar una serie de extensiones que nos facilitarán la vida (escribir los IDs en la sección Extensions):

* **Flake8** (_ms-python.flake8_): Revisor de código que sigue las normas del PEP8, lo veremos más adelante.
* **Material Icon Theme** (_PKief.material-icon-theme_): Le da iconos a nuestros archivos, es bonita.
* **Python** (_ms-python.python_): Extensión oficial de Python.

Seguramente en el futuro cuando tratemos un tema muy específico, agregaremos nuevas extensiones. De momento con las anteriores estaremos completamente cubiertos.
