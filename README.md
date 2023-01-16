# HealthBox

Puesto que con este proyecto se pretende crear una manera interactiva de medir una serie de parámetros vitales de manera que los pacientes no tengan la necesidad de acudir al hospital y así se alivie la carga de éstos, los objetivos principales son tres: crear un dispositivo portátil y cómodo de usar, realizar de forma precisa la medida de cuatro constantes vitales y generar un informe detallado con los resultados para el usuario y para el médico. A continuación, detallamos cada uno de ellos en profundidad.

## Instrucciones de uso:

1- Descargar el proyecto en un archivo .zip

2- Crear una cuenta en arduino cloud y seguir los pasos de preparación y creación de cuentas de Arduino Cloud: https://cloud.arduino.cc/

3- Crear un "thing"

4- Importar el .zip al editor de arduino

5- Crear las variables en el thing (con la misma sintaxis que apartece en el archivo thingPropierties.h) que serán las 5 variables compartidas entre el cloud y nuestro microcontrolador. 

6- Enlazar las variables y configurar la red (network). En este proyecto se incluye el archivo "secrets" vacío para ser configurado. 

7- Montar físicamente el circuito tal y como se muestra en los esquemáticos. 

NOTA: no se han incluido en los esquemáticos ni los cables de conexión del ecg "jack-electrodo" ni los parches de gel para mejorar la conductividad superficial. 

8- Cargar el código a la placa ESP32 y el nano.ino a la ardunio nano

