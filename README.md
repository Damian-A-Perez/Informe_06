# Informe_06

TEMA: PRÁCTICA No. 6 TEOREMA DE LA MÁXIMA TRANSFERENCIA DE POTENCIA.

ESTUDIANTES:  MENESES JARRIN SANTIAGO JAVIER OSEJO CUESTA BRANDON DILLAN PEREZ CEDILLO DAMIAN ALEXANDER 
    
DOCENTE: DARWIN OMAR ALULEMA FLORES 
 
NRC:  8703

En esta practica comprobaremos el teorema de maxima transferencia usando un circuito simple de una fuente de tension conectado en serie a una resistencia fija continua, y a una resistencia extra que varia, para que el teorema de maxima tranferencia se cumpla, debemos seguir varios pasos de entendimiento tanto para el circuito en serie como para la resistencia individual que contiene una variación, usaremos una lista de valores para la resitencia variable, y comprobaremos los resultados. Utilizando herramientas de simulacion digital, diseñaremos el circuito y comprobaremos los calculos establecidos.

1.- PLANTAMIENTO DEL PROBLEMA	

Determinaremos el valor de la pontencia en la resistencia RL para los valores previamente establecidos y determinaremos si se cumple el Teorema de Maxima Transferencia de Potencia en el circuito.

2. OBJETIVO DE LA PRACTICA

Comprobar experimentalmente el Teorema de la Máxima Transferencia de Potencia.

2.1 OBJETIVOS ESPECIFICOS

2.1.1. Determinar cual de los valores dados complementa el teorema de MTP
2.1.2. Observar que diferencia existe entre cada valor de resistencia requerido para los calculos

3. MARCO TEÓRICO

Teorema de Maxima Transferencia de Potencia:
Al principio existio una confusion entre un circuito con la maxima eficiencia y la maxima transferencia de potencia, Gracias  Edison en 1880 se dio a entender que para alcanzar la maxima eficiencia, la resistencia de la fuente debia ser lo mas pequeña posible, por lo contrario. Para la maxima transferencia de pontecia en un circuito tiene lugar cuando la resistencia de carga es igual a la resistencia interna de un generador

Al teorema de Maxima Transferencia de Potencia, tambien se lo reconoce como Ley de Jacobi. Debido a que Moritz von Jacobi fue el primero en descubrir su concepto.

El teorema establece cómo escoger (para maximizar la transferencia de potencia) la resistencia de carga, una vez que la resistencia de fuente ha sido fijada, no lo contrario. No dice cómo escoger la resistencia de fuente, una vez que la resistencia de carga ha sido fijada. Dada una cierta resistencia de carga, la resistencia de fuente que maximiza la transferencia de potencia es siempre cero, independientemente del valor de la resistencia de carga.(H.W.Jackson(1959))

De esta forma se puede concluir que, para hallar la maxima transferencia de pontencia en un circuito “La potencia máxima será desarrollada en la carga
cuando la resistencia de carga RL sea igual a la resistencia interna de la fuente Ri”

El teorema de maxima transferencia de pontencia, es reconocido como un adicional al teorema de thevenin, siendo este el punto de partida para el cual la potencia maxima en un circuito sea encontrada, tomando en cuenta los valores, las relaciones y la calidad del circuito de thevenin previamente obtenido, de esta manera observamos como los metodos de calculo y reduccion de circuitos, se pueden usar variadamente para encontrar toda clase de interrogantes.

![Teorema de Maxima Transferencia](https://github.com/Damian-A-Perez/Informe_06/blob/master/Img/transferencia.jpg)


4. MATERIALES

![Materiales](https://github.com/Damian-A-Perez/Informe_06/blob/master/Img/2020-07-21%20(5).png)

5. PROCEDIMIENTO

5.1 Arme el circuito que se encuentra en la figura

![Circuito A Armar](https://github.com/Damian-A-Perez/Informe_06/blob/master/Img/2020-07-21%20(4).png)

5.1.1 Circuito Armado

![Ci](https://github.com/Damian-A-Perez/Informe_06/blob/master/Img/Dazzling%20Snaget-Waasa.png)

5.2 Mida el voltaje y la corriente para cada valor de RL que se indica en la tabla. Anote los resultados medidos.

5.3 Calcule las potencia consumida por RL, para cada valor dado y anote los resultados en la tabla.

![Cálculos lab 6](https://github.com/Damian-A-Perez/Informe_06/blob/master/Anexos/C%C3%A1lculos%20lab%206.pdf)

|   RL   |Corriente medida (mA)| voltaje medido (V) |Potencia C Experimentalmente| Potencia C Teoricamente|
|:---: |  :---:  | :---:  | :---:   |:---:     |
|220 | 10.6ma | 2.32v| 0.0245|0.0245|
|470 |  8.98ma | 4.22v| 0.0379|0.0379|
|680 |  7.98ma  |5.43v|0.0433|0.0433|
|820 |   7.43ma  | 6.09v|0.0452|0.0452|
|1000  | 6.82ma | 6.82 v| 0.0465|0.0465|
|1500 |   5.56ma | 8.33v|0.0463|0.0463|
|1800    | 5ma  | 9v| 0.045|0.045|
|2200|  4.41ma| 9.71v|0.043|0.0428|
|3900|  2.94ma|  11.5v|0.034|0.0337|
|4700 |   2.54ma  | 11.9v |0.03|0.0304|

![Cálculo del error lab 6](https://github.com/Damian-A-Perez/Informe_06/blob/master/Anexos/C%C3%A1lculo%20del%20error%20lab%206.pdf)

5.4. ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su
respuesta.
En ninguno de los resultados mostrados en la table se cumple el teorema pues rl no se parece a la rth de 1.2k ohm. 

5.5. ¿Cuál fue la potencia máxima en RL? 

0.047 watss = 47mw


5.6. ¿Para qué valor de RL se obtiene la MTP?

Rl debe ser igual a la rth = 1.2k ohm

CONCLUSIONES

Obtenemos una mayor potencia a medida que el valor de la resistencia se acerque mas al valor de la resistencia Thevenin.

Es necesario obtener el voltaje y la resistencia Thevenin para aplicar el teorema de la maxima transferencia de potencia.

RECOMENDACIONES

Recordar usar de manera adecuada el multimetro para evitar una medicion de valores inexistentes o invalidos

Tomar en cuenta los requisitos previos y las observaciones antes de implementar el circuito

CRONOGRAMA

![CRONO6](https://github.com/Damian-A-Perez/Informe_06/blob/master/Img/cronograma%20l6.png)

Bibliografia:

--ElectronicaUnicorn, (2020),Recuperado de:https://unicrom.com/teorema-de-maxima-transferencia-de-potencia/
--H.W. Jackson (1959) Introduction to Electronic Circuits, Prentice-Hall.


