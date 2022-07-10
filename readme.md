# Textdraw Mapa GPS para SAMP
Este mod nos muestra un minimapa en el juego que muestra la ubicación de nuestro personaje, checkpoint y lugares que agreguemos
##### Funciones:
* Menú de configuración para cambiar las id de los textdraw y la tecla para abrir el mapa
* Menú de agregar iconos para agregar iconos del hud.txd al mapa gps

# Instrucciones de uso
* Tecla: M : Abre y cierra el Mapa GPS, esta tecla se puede cambiar en el menú de configuración
* /mapconfig : Abre el menú de configuración del mod que permite cambiar la tecla de abrir el mapa y las id de los textdraw que utiliza el mapa
* /mapicons : Nos permite agregar iconos al Mapa GPS, los iconos son leidos desde el archivo hud.txd\
### Agregando un Icono al Mapa
Abrimos el menú con el comando **/mapicons** y seleccionamos la opción **+ Agregar nuevo**\
\
![](https://i.ibb.co/5WQyGX5/men.png)\
Se abrira este dialogo en donde debemos ingresar un nombre para el icono que se agregara a la lista y asi podamos diferenciarlo de otros\
![](https://i.ibb.co/zJLv42W/gas.png)\
Seleccionamos un icono de la lista. en total hay 63 iconos y son leidos desde el archivo **hud.txt**\
![](https://i.ibb.co/89pS1Tx/icons.png)\
Por último ingresamos el ID del textdraw [0-2304] debemos evitar repetirlo por los que reserva el mapa gps o otros que hemos agregado en la lista\
![](https://i.ibb.co/8K8BL1T/textdraw.png)\
Los id de los iconos que agreguemos al mapa deben ser mayor que la id del mapa de lo contrario no se agregara y nos dira que la id debe ser mayor\
![](https://i.ibb.co/JFdQwLf/error.png)\
Y en el caso de que el id este en uso por el servidor o ya este en la lista nos dira\
![](https://i.ibb.co/Bfw4bcH/error2.png)\
# Video
