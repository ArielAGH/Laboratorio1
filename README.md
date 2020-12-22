# Laboratorio 1: Leyes de Kirchhoff
Integrantes: Caillamara Leonardo, González Ariel
## 1. OBJETIVOS

### Objetivo general:
* Evidenciar las leyes de Kirchhoff mediante el análisis de voltajes y corrientes en el circuito propuesto por medio de la plataforma Tinkercad.

### Objetivos específicos:
* Encontrar los valores de corriente y voltaje de cada uno de los elementos utilizando la ley de Ohm.
* Determinar los valores de corriente y voltaje haciendo uso del simulador de Tinkercad.

## 2. MARCO TEÓRICO

Para la realización de esta práctica de laboratorio es necesario conocer acerca de las leyes de Kirchhoff, las cuales son dos igualdades que tienen como principal fundamentación la conservación de la energía y también la carga de los circuitos electrónicos. Es importante saber, además, que las leyes planteadas por Kirchhoff se utilizan para hallar corrientes y/o tensiones en cualquier punto a lo largo de un circuito eléctrico.

La primera ley de Kirchhoff, conocida generalmente por sus siglas LCK, es llamada ley de nodos, la misma que nos dice que:

>En cualquier nodo, la suma de las corrientes que entran en ese nodo es igual a la suma de las corrientes que salen. De forma equivalente, la suma de todas las corrientes que pasan por el nodo es igual a cero.

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Captura%20de%20pantalla%20(12).png)

Dentro de un circuito eléctrico es frecuente que se generen nodos de corriente entre los distintos elementos de una malla. Para entender mejor lo antes dicho, es importante definir qué es un nodo. Un nodo es un punto del circuito en donde se une más de un terminal (elemento) de un componente eléctrico.

De esta ley se puede deducir también que la sumatoria de las corrientes que fluyen hacia un nodo es igual a la suma de las corrientes que salen del mismo, tal como se encuentra mencionado anteriormente, lo que se puede representar de la siguiente forma:

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Captura%20de%20pantalla%20(13).png)

Es totalmente posible entender de forma intuitiva por qué esta ley se cumple si se considera que la corriente eléctrica se da por la circulación de electrones de un punto de un circuito a otro punto. Pues, dependiendo de las resistencias que se utilicen en la malla, los electrones se separaran hacia un lado u otro, pero siempre manteniendo constante su cantidad.

Por otro lado, Kirchhoff mencionó también una segunda ley conocida como ley de las tensiones, la que nos dice que:

>En un círculo cerrado, la suma de todas las caídas de tensión es igual a la tensión total suministrada. De forma equivalente, la suma algebraica de las diferencias de potencial eléctrico en un circuito es igual a cero.

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Captura%20de%20pantalla%20(14).png)

Tal como se dijo al inicio de este marco teórico, Kirchhoff se basó en la conservación de la energía para realizar sus leyes y, es precisamente esta, la que trata el tema. Es por eso que podemos decir que, dada una diferencia de potencial, una carga que ha completado un lazo cerrado no gana ni pierde energía al regresar al potencial inicial.

Aun cuando en el circuito existen resistencias, esta ley sigue vigente considerando que una carga no regresa a su punto de partida, por lo que, en lugar de terminar en el terminal positivo, únicamente llegará al negativo, lo que significa que toda la energía dada ha sido consumida por la resistencia. Por lo que en resumidas cuentas podemos decir que la segunda ley de Kirchhoff no tiene nada que ver con la ganancia o pérdida de energía de los componentes eléctricos como resistencias, capacitores, entre otro, puesto que es una ley relacionada con el campo potencial generado por fuentes de tensión o corriente eléctrica.

## 3. EQUIPOS Y MATERIALES

* **Tinkercad:** Es un programa gratuito de modelado en 3D en línea que se ejecuta en un navegador web. Este programa nos permitirá simular los materiales siguientes que se requieren para la realización de la presente práctica de laboratorio.

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Tikercad.jpg)

* **Protoboard:** Es una placa de pruebas en la que se pueden insertar elementos electrónicos y cables con los que se arman circuitos sin la necesidad de soldar ninguno de los componentes.

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Protoboard.jpg)

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/ProtoboardTc.png)

* **Resistencias eléctricas:** Una resistencia es una medida de oposición al flujo de corriente de un circuito eléctrico.

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Resistencias.png)

* **Cables puente:** Es un cable con un conector en cada punta (a veces sin ellos), que se usa para interconectar entre sí los componentes en una placa de pruebas, una protoboard, por ejemplo.

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/CablesPuente.jpg)

* **Multímetro:** Es un instrumento eléctrico portátil que se usa para medir directamente magnitudes eléctricas activas.

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Multímetro.jpg)

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/MultímetroTinkercad.png)

* **Batería o fuente energética:** Es un dispositivo que consiste en una o más celdas electroquímicas que pueden convertir química almacenada en corriente eléctrica.

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Batería.jpg)

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/BateríaTc.png)

## 4. PROCEDIMIENTO

* Para realizar esta práctica es necesario tener una cuenta en la plataforma Tinkercad, pues con ella simularemos los materiales de laboratorio necesarios para el cometido.
* Abrir Tinkercad y en la parte superior izquierda dar click en en la pestaña "Circuits", la misma que nos permitirá seleccionar los distintos elementos eléctricos.

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Paso1.png)

* Una vez seleccionado "Circuits" damos click en "Crear nuevo circuito".

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Paso2.png)

*	Aquí escogeremos los elementos necesarios para simular las mallas que se encuentran detalladas en la guía de este laboratorio con los multímetros correctamente colocados tanto para calcular los voltajes como las diferentes corrientes.

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Paso3.png)

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Paso4.png)

*	Finalmente damos click en la opción “Iniciar simulación” para así poder obtener los valores medidos de la práctica.

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Paso5.png)

![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Paso6.png)

## 5. TABLAS DE MEDICIÓN Y CÁLCULOS

### Tabla 1.1 Resultados obtenidos de voltaje y corriente en cada elemento del circuito.
![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Captura%20de%20pantalla%20(11).png)

### Tabla 1.2 Verificación de la LVK.
![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Captura%20de%20pantalla%20(9).png)

### Tabla 1.3 Verificación de la LCK.
![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Captura%20de%20pantalla%20(10).png)

## 6. ANÁLISIS DE RESULTADOS

Para el respectivo análisis utilizaremos la fórmula para calcular el error que existe entre los datos medidos y los datos calculados, lo que nos permitirá saber si las leyes de Kirchhoff se cumplen.

En el caso de los voltajes:
#### * Trayectoria 1
![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Captura%20de%20pantalla%20(15).png)

#### * Trayectoria 2
![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Captura%20de%20pantalla%20(16).png)

#### * Trayectoria 3
![](https://github.com/ArielAGH/Laboratorio1/blob/master/Img/Captura%20de%20pantalla%20(17).png)

Al igual que en la trayectoria anterior, el error nos da un valor elevado debido a los decimales empleados, sin embargo, cuando nos fijamos en los valores teórico tanto como calculado, podemos observar que son valores que tienden a 0, lo que nos indica que la ley de Kirchhoff es totalmente práctica.

En el caso de las corrientes:

#### * Nodos 1, 3 y 5

En estos nodos por simple inspección podemos observar que tanto el valor calculado como el medido es 0 en todos y cada uno, por lo que los errores nos darán un valor igual al 0%.

#### * Nodos 2 y 4

Podemos observar que en estos nodos el valor teórico es igual a 0, por lo que realizar los cálculos con la fórmula propuesta para el error no sería posible, sin embargo, podemos observar cómo los valores siguen tendiendo a 0, lo que nuevamente comprueba las leyes de Kirchhoff.

## 7. CONCLUSIONES

Por los análisis anteriormente realizados es posible concluir que la sumatoria de los valores comprendidos en un lazo será cero y la suma de las corrientes que ingresan a un nodo son iguales a la sumatoria de las corrientes que salen. Esto corresponde a las leyes de Kirchhoff respecto al voltaje y la corriente, respectivamente. Cabe aclarar que los errores observados tienden a ser un número alto debido a la manipulación de datos extremadamente pequeños, pero esto no quiere decir que las leyes de Kirchhoff no se cumplan, al contrario, podemos observar que las leyes se cumplen a cabalidad en cada una de las tablas de valores presentadas a lo largo de esta práctica de laboratorio.

## 8. BIBLIOGRAFÍA Y CITAS

* Ayllón Fandiño, E. (1987). Fundamentos de la teoría de los circuitos eléctricos II.La Habana: Pueblo y Educación.
* Kerchner, R. M., Corcoran, G. F. (1975). Circuitos de corriente alterna. La Habana: Pueblo y Educación.
* Redondo, F., Redondo, R. (2005). Redes eléctricas de Kirchhoff. REVIDE S. L.
* Ernst, A. (1959). Introducción a la teoría de los circuitos. Editorial Reverte. 


