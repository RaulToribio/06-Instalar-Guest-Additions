# 06-Instalar-Guest-Additions

# Introducción

Las Guest Additions en VirtualBox son un conjunto de controladores y herramientas adicionales que se instalan en la máquina virtual Ubuntu para mejorar la interacción entre el sistema operativo invitado (Ubuntu) y el sistema operativo anfitrión (el sistema operativo en el que está ejecutando VirtualBox).

Entre las características que se añaden con las Guest Additions de Ubuntu en VirtualBox se incluyen:

- Mejora en el rendimiento gráfico: Las Guest Additions permiten acelerar la velocidad de gráficos en la máquina virtual, lo que permite una mejor experiencia visual en la máquina invitada.
- Compartir archivos y carpetas: permite compartir archivos y carpetas entre la máquina anfitriona y la invitada, lo que facilita el trabajo y la transferencia de datos.
- Control de pantalla: permite ajustar automáticamente el tamaño de pantalla de la máquina virtual para adaptarse a la pantalla del anfitrión, lo que permite una mejor visualización.
- Control de ratón: permite el uso de la función de "ratón integrado" entre la máquina anfitriona y la invitada, lo que significa que el cursor del ratón se moverá automáticamente entre ambas pantallas.

# Material Necesario

- [VirtualBox](https://github.com/RaulToribio/01-Instalar-VirtualBox)
- [Ubuntu 22.04.1 LTS](https://github.com/RaulToribio/02-Descargar-Ubuntu)
- [Crear Máquina Virtual](https://github.com/RaulToribio/03-Crear-Maquina-Virtual)
- [Configurar Máquina Virtual](https://github.com/RaulToribio/04-Configurar-Maquina-Virtual)
- [Instalar Ubuntu](https://github.com/RaulToribio/05-Instalar-Ubuntu)

# Material de Referencia

- [Instalación de Ubuntu 20.04 en VirtualBox Windows (Codigo IoT)](https://edu.codigoiot.com/course/view.php?id=812)

# Instrucciones

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(1).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(1).png)

Seleccionar el usuario creado cuando se realizó la instalación del sistema operativo.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(2).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(2).png)

Ingresar la contraseña para dicho usuario.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(3).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(3).png)

Clic en “Next”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(4).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(4).png)

Clic en “Next”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(5).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(5).png)

Clic en “Next”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(6).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(6).png)

Clic en “Done”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(7).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(7).png)

Nos encontramos en el escritorio.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(8).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(8).png)

Abrir la terminal con la combinación de teclas “Ctrl + Alt”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(9).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(9).png)

Actualizar la lista de paquetes disponibles en el sistema operativo con la línea de comando `sudo apt-get update`.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(10).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(10).png)

Ingresar contraseña.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(11).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(11).png)

Comenzará a actualizarse la lista de paquetes disponibles en el sistema operativo.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(12).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(12).png)

Actualizar los paquetes instalados en el sistema a las versiones más recientes disponibles con la línea de comando `sudo apt-get upgrade`.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(13).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(13).png)

Confirmar la operación escribiendo “*Y*”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(14).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(14).png)

Se empezará a mejorar el sistema.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(15).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(15).png)

Se habrá actualizado y mejorado el sistema operativo.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(16).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(16).png)

Clic en “Dispositivos”.

Clic en “Insertar Imagen CD de las «Guest Additions»”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(17).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(17).png)

Clic en el ícono “VBox_GAs_7.0.4”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(18).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(18).png)

Seleccionar “autorun.sh”.

Clic derecho para desplegar el menú de opciones.

Clic en “Run as a Program”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(19).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(19).png)

Ingresar contraseña.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(20).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(20).png)

Se comenzará la instalación.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(21).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(21).png)

Habrá terminado la instalación.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(22).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(22).png)

Ingresar la línea de comando `sudo apt install gcc perl make`.

- GCC es el acrónimo de "GNU Compiler Collection", es un conjunto de compiladores de lenguaje de programación de código abierto desarrollado por la Fundación GNU. GCC incluye compiladores para varios lenguajes de programación, como C, C++, Objective-C, Fortran, Ada, y otros. Es uno de los compiladores más utilizados en sistemas operativos Linux y Unix.
- Perl es un lenguaje de programación de alto nivel, con un enfoque en la manipulación de texto y una sintaxis similar al lenguaje de programación de shell. Es muy utilizado en tareas de automatización de sistemas, análisis de datos, y desarrollo web.
- Make es una herramienta de automatización de construcción de software, que se utiliza para controlar el proceso de compilación y enlazado de un programa. Make se basa en un archivo de configuración llamado "makefile" que contiene las reglas y las dependencias necesarias para construir un programa. Make se utiliza comúnmente en sistemas operativos Linux y Unix para automatizar la compilación de programas y aplicaciones de código abierto.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(23).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(23).png)

Confirmar la operación escribiendo “*Y*”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(24).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(24).png)

Se mostrará el progreso de la operación.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(25).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(25).png)

La operación habrá concluido.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(26).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(26).png)

Clic derecho en el ícono “VBox_GAs_7.0.4”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(27).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(27).png)

Abrir el menú “Power Off / Log Out”.

Clic en “Restart”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(28).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(28).png)

Clic en “Restart”.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(29).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(29).png)

Seleccionar usuario.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(30).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(30).png)

Ingresar contraseña.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(31).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(31).png)

Tendremos acceso a nuestro escritorio.

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(32).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(32).png)

Nuestro sistema operativo estará listo para adaptarse a la escala de una ventana maximizada o cualquier otro tamaño que tome la ventana de VirtualBox.

# Evidencias

![https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(32).png](https://raw.githubusercontent.com/RaulToribio/06-Instalar-Guest-Additions/main/Im%C3%A1genes/Instalar%20Guest%20Additions%20(32).png)

# Créditos

> [José Raúl Toribio Gabriel](https://github.com/RaulToribio)
> 

> [Codigo IoT](https://github.com/codigo-iot)
>