# AUTOSTART

## Configuraciones iniciales 





# ----

1. Confifurar el host
   En la terminal ejecutar

```
sudo gedit hosts
```
   Una vez despliega un archivo se configura de la manera siguiente. 
   
2. Copiar las carpetas o descargaslas desde

3.Si se tiene configuradas varias redes de internet se tendría que realizar la siguiente configuración para que cuando esta inicie se conecte automáticamente a la red que se espera.











## Control del turtlebot2 desde la Jetson mediante cable


*********************************************
Turtlebot Fisico
-------------------------------
*****

roscore
cd catkin_ws

Ubicarse en la carpeta donde se tenga instalado el turtlebot
```
source ./devel/setup.bash
roslaunch turtlebot_bringup minimal.launch --screen
roslaunch turtlebot_teleop keyboard_teleop.launch

```
**************************************





# ADICIONALES

## Instlacion de los drives para leer el Lidar desde la Jetson

rplidar a1 Githud       

clonar el git                 

Turtlebot2_src

Turtlebot2$ catkin_make

Verifica el puerto ls/dev/tty*        (en que puerto esta instalado el LIDAR )

sudo chmod 777/dev/ttyUSB0                                                  ← (Se le asigna permiso)

roslaunch rplidar_ros view_rplidar_a1.launch








# Observaciones durante el proceso 

Para conectar la pantalla a la Jetson(conectar sin conversores, Direccto a la HMI(1 cable) )



 --------------------
 en la jetson se debe de levantar el turtlebot 
 --------------------
 NO OLVIDAR EL SOURCE 
  rosrun mov_turtle control_trayectoria_recta.py 
