# Manual de Practicas 
## practica 1 
En esta práctica desarrollamos un programa en donde se tienen que sumar dos números, para esto tuvimos que poner un ciclo while para que el programa sea cíclico. Pusimos dos constantes con un rango de 0 a 10 y lo enlazamos a un bloque llamado ADD en donde su función es sumar y el resultado obtenido lo manda a un componente llamado indicador en el cual su función es mostrar el resultado de dicha suma
Esto se muestra a continuación 

<img src="1.PNG">

La forma de conexión del sistema queda de esta manera donde podemos visualizar la forma en que se conecta cada componente:
<img src  ="2.PNG">

Posteriormente vemos el funcionamiento de dicho sistema 

<img src="3.PNG">

#Práctica 2
En la práctica numero 3 realizar un programa donde calcula el Índice de Masa Corporal, para esto tuvimos que adquirir la fórmula para obtener el resultado (peso/altura^2). Tuvimos que poner 3 constantes para que el usuario pusiera sus datos, de este modo la conexión de los mismos será a la de la formula. Además, colocamos un termómetro como indicador para que nos señale si tenemos un peso normal, si tenemos sobrepeso o tenemos bajo peso. Esto se muestra a continuación.


<img src="4.PNG">

La conexión virtual del sistema es muy sencilla, esto se muestra a continuación:

<img src="5.PNG">

Nuestro programa funcionando queda de la siguiente manera :

<img src ="6.PNG">

##Práctica 3
En esta práctica realizamos la conexión de un led en el cual parpadea cada medio segundo. 
La forma de conexión virtual queda de la siguiente manera, donde podemos observar que funciona mediante un ciclo  repetitivo y de esta manera jamas se detenga asta que el operador lo detenga:

<img src="8.PNG">

Nuestro panel que ve el operador es de esta manera:

<img src="7.PNG">

La forma en que funciona este sistema se muestra a continuación. Observe que solo se muestra el un led virtual y un botón de paro.

<img src = "9.PNG">

##Prática 4 
En esta práctica desarrollamos un sistema en donde se conecta un termómetro junto con un led, donde su principal función es que si se pasa del límite establecido el led prende, este límite se controla mediante un controlador en donde el usuario puede poner el límite que desee. Todo esto funciona mediante un ciclo repetitivo para que no se pare el programa a cada rato.

<img src ="16.PNG">

Como vemos en la imagen anterior aparece la conexión interna del programa en donde el usuario no podrá verlo, en la imagen que aparece a continuación se muestra lo que el usuario vera y podre manipular, que en este caso solo será el límite de temperatura para que prenda y apague el led.

<img src ="15.PNG">

La forma final del programa de esta manera:

<img src ="17.PNG">

##Práctica 5 
En la práctica 5 desarrollamos una interfaz con la placa de adquisición llamada arduino, la forma de conexión es diferente ya que se tiene que enlazar arduino con nuestro programa. La función de esta práctica es el prender un led y apagarse constantemente. La conexión virtual se desarrolla de esta manera:

<img src ="12.PNG">

Para la conexión de arduino tenemos que señalar el puerto en que está conectado, de esta manera se podrá realizar la interfaz, también se colocara la salida que se está manejando en arduino, en este caso es el pin 13. Esto se muestra a continuación:

<img src="11.PNG">

Nuestra conexión con arduino queda de esta manera, también pudiendo observar que el led esta prendido y apagado.

<img src ="13.PNG">

<img src ="14.PNG">

#Práctica 6
Para desarrollar esta práctica necesitamos realizar la interfaz de arduino con lavbiew, de esta manera podremos trabajar adecuadamente. La función de esta práctica es que cuando se presione un interruptor conectada al arduino mande una señal para que esta mande un pulso y prenda un foco virtual y ala ves mande una señal senoidal y al volver a presionar el botón este pare.
Para esto realizamos una conexión en protoboard y en la salida manda un pulso en el pin 8 del arduino, con esto hace que prenda el foco y con esto manda la orden de marcar la onda senoidal. Esto se muestra a continuación:

<img src="18.PNG">

<img src ="19.PNG">

La conexión del protoboard está de esta manera:

<img src ="20.PNG">

#Práctica 7 
En la práctica número 7 se realizó un sistema de prendido y apagado de un led con la diferencia que este tiene que parpadear al momento de presionar el botón. 
Se tuvo que conectar en la tablilla protoboard un foco led con un apagador. Una de las salidas del apagador va a la entrada 8 del arduino para que este mande la señal en lavbiew. La otra entrada que manda arduino es la del led, que va conectada en la entrada 4. La forma de conexión en lavbiew es de esta manera:

<img src="21.PNG">

En el sistema de bloques que ve el usuario es de esta manera, note que solo se visualiza el foco virtual.

<img src="22.PNG">

Y por último la conexión de la tablilla protoboard es de esta manera:

<img src="23.PNG">

<img src="24.PNG">

##Practica 8 
