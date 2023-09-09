# Robotica_2023_Lab1
## Integrantes
### 1.  Descripcion de la solucion plan



teada.
### 2. Diagrama de flujo de acciones del robot
![](./Diagrama%20de%20flujo/Flowchart.jpg)
###Figura 2.1 Diagrama de flujo.
### 3. Plano de planta de la ubicacion de cada uno de los elementos.
### 4. Descripcion de las funciones utilizadas.
### 5. Diseno de la herramienta.

Para la práctica se requiere diseñar y hacer una herramienta de grabado el cual permite montas y desmontar un marcador.
El marcador debe permitir el cambio de posición vertical de tal manera que pueda adaptarse a los cambios de nivel de la superficie en la que está dibujando.
Adicional a ello se debe tener en cuenta que la forma de la herramienta debe tener una orientación tal que no quede alienada con el tercer eje, con el fin de que el robot no entre en singularidades en ninguno de los ejes.
Por esta razón se plantea el diseño de la herramienta formando un ángulo de inclinación de 130 grados como se muestra en la figura 5.1 continuación donde el soporte se tiene el soporte que se acopla a la brida del robot, seguido de un cilindro con una inclinación de 40 grados en e l cual se monta el marcador.

![](https://github.com/jcardenash99/Robotica_2023_Lab1/blob/main/Dise%C3%B1o%20de%20herramientas/Angulo%20herramienta.png)
###Figura 5.1 Angulo de la heramienta.

Teniendo en cuenta las condiciones del laboratorio y los errores que se pueden generar tanto en la calibración de la herramienta y la definición del workobjet, se propone un diseño en el cual el marcador permita moverse en los cambios de nivel de la superficie. El diseño consiste en dejar el mercador dentro del cilindro de manera libre, amortiguado con un resorte el cual mantiene la punta del marcador siempre afuera de tal manera que al encontrar un cambio de nivel el resorte se comprime permitiendo que el marcador ingrese en el cilindro. Una vez superado el cambio de nivel el resorte hace que retorne a su posición inicial, permitiendo así que la punta del marcador y el cuerpo de la herramienta no sufra daños.
![](https://github.com/jcardenash99/Robotica_2023_Lab1/blob/main/Dise%C3%B1o%20de%20herramientas/Dise%C3%B1o%20amortiguado.png)
###Figura 5.2 Cilindro internamente.

En la figura 5.2 se muestra como está construido el cilindro el cual es escalonado en la parte inferior que no permite que el marcador se salga, una vez el marcador ingresa se coloca un resorte y luego un tornillo brístol sin cabeza que rosca en la parte superior, cerrando el cilindro sin permitir que el marcador se salga y su vez permitiendo la compresión del resorte para el movimiento libre del marcador.
### 6. Codigo en RAPID del modulo utilizado para el desarrollo de la practica.
### 7. Video que contenga la simulacion en RobotStudio asi como la implementacion de la practica con los robotsreales.
[![Video Plano](./Simulacion%20Robot%20Studio/Objeto%20Plano.mov)
![Video Plano](./Simulacion%20Robot%20Studio/Plano%20inclinado.mov)
](https://github.com/jcardenash99/Robotica_2023_Lab1/assets/61796945/45ac2377-12f2-4768-b934-019e1a6f6831



https://github.com/jcardenash99/Robotica_2023_Lab1/assets/61796945/0bdce6fe-05aa-4da9-bf31-913585bcf2ac)https://github.com/jcardenash99/Robotica_2023_Lab1/assets/61796945/45ac2377-12f2-4768-b934-019e1a6f6831



https://github.com/jcardenash99/Robotica_2023_Lab1/assets/61796945/0bdce6fe-05aa-4da9-bf31-913585bcf2ac
