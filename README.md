# Mini Robot con Arduino

Proyecto para construir un mini robot controlado por gestos utilizando un Arduino Nano. Cuando se pasa la mano hacia la izquierda por delante del sensor el robot se mueve hacia la izquierda, lo mismoa hacia la derecha, arriba y abajo.

![image](https://github.com/electrodeuna/car-gesture-arduino/assets/85527788/1990d4ca-9ed6-4b94-9ec1-e3658b36cfc0)

## Video

https://www.youtube.com/watch?v=inUxp2acXcg

## Lista de Materiales

- Arduino Nano
- Servomotores rotación continua (x2)
- Ruedas para servomotor (x2)
- Baterias 3.7v (x2)
- Pantalla Oled 0.96''
- Sensor de gestos ADPS-9960
- Placa experimental
- Cables

## Diagrama de Conexiones

| Arduino Nano | Pin en el Servo                 |
| ------------ | ------------------------------- |
| D3	         | Pin de señal Servo 1 (amarillo) |
| D4	         | Pin de señal Servo 2 (amarillo)  |
| 5V	         | Pin de alimentación (rojo)      |
| GND	         |Pin de tierra (negro)            |

## Librerías

Para que el código funcione correctamente hay que instalar las siguientes librerías:

- Arduino_APDS9960
- Adafruit_GFX
- Adafruit_SSD1306
