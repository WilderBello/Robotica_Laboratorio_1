
# Entrega Laboratorio 1

El laboratorio 1 de la materia Robótica tiene como objetivo enseñar el uso y funcionamiento de la herramienta Robot Studio que permite el manejo de robots ABB.

## Autores

- [Wilder Ofrey Bello Herrera](https://github.com/WilderBello)
- [Javier Eduardo Gutierrez Serrano](https://github.com/jaegutierrezser)


## Solución

Tomando como base la herramienta utilizada por los brazos industriales de soldadura, se realizó un modelado de una herramienta con una inclinación de 45 grados, de tal manera que al bajar el brazo robótico no se chocara con el tablero.
![](https://thumbs.dreamstime.com/z/brazo-industrial-del-robot-de-soldadura-con-el-modelo-la-antorcha-ot-electrodo-mig-aislado-en-fondo-blanco-trayectoria-recortes-o-142568943.jpg)

[Brazo industrial del robot de soldadura](https://es.dreamstime.com/brazo-industrial-del-robot-de-soldadura-con-el-modelo-la-antorcha-ot-electrodo-mig-aislado-en-fondo-blanco-trayectoria-recortes-o-image142568943)

## Archivos 

Para el desarrollo del presente trabajo se realizó el modelado en CAD de la herramienta para poder acoplarla correctamente al robot en el software Robot Studio, así como la implementación en robots reales.

![](https://i.postimg.cc/PpJ1tvfP/Modelo-CAD-Base.jpg)

Posteriormente se realizó la impresión en 3D de la base que se ajusta al porta herramienta del Robot ABB 140 y se unieron las partes que componen la herramienta.

![](https://i.postimg.cc/2ykwcVYp/Base.jpg)
![](https://i.postimg.cc/05nZ6dG9/herramienta.jpg)

![](https://i.postimg.cc/d359zwQh/Herramienta-completa.jpg)

Para el manéjo de la herramienta, se procedio a realizar el modelo en RobotStudio para poder manejar el programa sin errores.

![](https://github.com/WilderBello/Robotica_Laboratorio_1/blob/main/Imagenes/Modelado_Herramienta.png)

La base que se utilizó para definir la trayectoria se puede ver a continuación:

![](https://i.postimg.cc/B6GNFmwn/Base-escritura.jpg)

Luego se ubicaron cada una de las trayectorias que debía seguir el robot y así se obtuvo el código en RAPID.

![](https://github.com/WilderBello/Robotica_Laboratorio_1/blob/main/Imagenes/Trayectorias.png)

Por medio de la implementación de las trayectorias que sigue el manipulador ABB, se realiza la respectiva programación del codigo en RAPID, el cual, se implementa en el Robot real.

- [Codigo RAPID de la secuencia](https://github.com/WilderBello/Robotica_Laboratorio_1/tree/main/Codigo%20RAPID_Lab_01_Robotica)


Se realizó la simulación de la trayectoria que debía seguir el robot en Robot Studio.

- [Video simulación de la trayectoria en el plano de 30°](https://github.com/WilderBello/Robotica_Laboratorio_1/blob/main/Videos/RobotStudio%209-2_1.mp4)

La implementación de la trayectoria dada se puede observar en el siguiente video:

- [Video de la trayectoria en el plano 1](https://github.com/WilderBello/Robotica_Laboratorio_1/blob/main/Videos/Escritura%20en%20plano%201.mp4)

## DESCRIPCIÓN DE LA SOLUCIÓN PLANTEADA
La implementación anteriormente documentada nos permite observar como es un acercamiento inicial con base en la programación de los robots industriales, ademas, de ser intuitiva y poco compleja una vez se toma experiencia. Se puede observar que la herramienta planteada es robusta y permite un correcto funcionamiento e implementación en el manipulador ABB 140, ademas de que permite una adecuada integración lo que permite bajos errores en el conjunto herramienta - manipulador.

