# Lab-3-Teorema-de-superposicion-

--------Teorema de Superposicion 

---------(Circuitos Electricos)-------

Objetivos

Generales: 

•	Explicar y demostrar teórica y prácticamente el teorema de superposición 

•	Realizar el análisis de los diferentes circuitos con el teorema e superposición tomando en cuenta el uso de fuente corriente o voltaje 

•	Mostrar prácticamente la función del circuito en un simulador e utilizar los instrumentos de medición ya sea para amperaje o voltaje

  
Específicos:

•	Construir en el simulador Tinkercad el circuito guiándonos en el diagrama previamente establecido

•	Verificar los procesos donde aplicamos que una fuente de voltaje se cierra o cortocircuita y una fuente de corriente se abre  

•	Comprender el uso del multímetro ya sea para medir amperaje o voltaje siendo asi un método de comprobación para los cálculos realizados a mano con los valores de voltaje e intensidad de corriente mostrados en la tabla 

  
----Requisitos previos----

•	Se requiere el análisis analítico del circuito mostrado en la figura 4.1., aplicando el Teorema de Superposición. 

•	Obtenga los valores de VA e IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan y anote los resultados en la tabla 4.1. y 4.2. según corresponda.
  
  
----MarcoTeorico---

La superposición o teorema de superposición es una técnica muy útil para añadir a tu conjunto de herramientas que sirve para analizar circuitos. Usa la superposición cuando tengas un circuito con entradas múltiples o múltiples fuentes de poder.
	Describir un circuito como una función
El principio de superposición se define usando notación funcional, así que aquí hablamos un poco acerca de cómo los circuitos se pueden representar como funciones. ¿Cómo podrías representar un solo resistor usando la notación de una función matemática? Aquí no está pasando nada extraordinario, solo hablamos de la ley de Ohm usando terminología de funciones. Empezamos por identificar tres cosas: las entradas, lo que hace la función y las salidas.
Tomamos el voltaje v_i, será la entrada de nuestra función del resistor. Podemos suponer que la entrada v_i se genera por alguna cosa que produce voltaje que no estamos mostrando. Designamos la salida como la cosa interesante que queremos conocer. Para esta función, la salida es la corriente i en el resistor.
El voltaje de entrada se les aplica a los dos círculos pequeños (los círculos le indican el puerto de entrada a nuestra función). La propia función viene del resistor, por medio de la ley de Ohm. La salida de nuestra función será la corriente, i, medida por algún medidor de corriente no mostrado.
 
Escrito como una función, nuestro resistor es
 
Con esta notación, vemos al resistor como una función que toma como entrada un voltaje y tiene como salida una corriente.
	Un resistor es una función lineal
Al ver nuestra función para el resistor, observamos que tiene la propiedad de escalamiento: la salida i , equivale a la entrada, v , escalada por una constante R. Eso significa que el resistor es lineal. La propiedad de linealidad es lo que dispara nuestra habilidad de usar la superposición para ayudarnos a resolver un circuito.
	Usar superposición para ayudarnos a resolver un circuito
Para entender mejor utilizaremos este ejemplo, suponemos que la entrada de nuestra función consiste de dos voltajes en serie:
 
 
La entrada para nuestra función consiste de dos baterías en serie:
 
La función es 
 
La salida de la función no ha cambiado; todavía es i=f(v)
Ahora resolvemos este circuito de dos maneras: primero por medio de un análisis convencional, y después usando el principio de superposición.
	Solución convencional
Para resolver por medios convencionales, escribimos las ecuaciones de la LVK alrededor del lazo:
 
y despejamos i:
 
 (solución convencional)
	Solución usando el principio de superposición
El principio de superposición se aplica a una función lineal, f.
 

Entonces tenemos dos entradas superpuestas, (x_1+ x_2), puedes aplicar una entrada a la vez,  (x_1) seguida de 〖(x〗_2) y después sumar los resultados individuales para obtener la respuesta completa.
Ahora usemos el principio de superposición para resolver el circuito. Como modelamos nuestro circuito como una función, podemos decir que:
 
es lo mismo que
 
Esto sugiere una posibilidad interesante. Dice que podemos calcular la corriente de salida de la manera convencional al aplicar las entradas combinadas  f(Vs1+Vs2), o podríamos obtener la misma respuesta al calcular la función con entradas individuales f(Vs1) y f(Vs2) sumando los resultados. 
	Suprimir entradas
Para aplicar la superposición necesitamos aplicar las entradas una a la vez. Eso significa que tenemos que apagar todas las entradas excepto una. Cuando apagamos una entrada decimos que está suprimida.
¿Qué significa apagar una fuente de voltaje? Significa que hacemos V =0 Esto es lo mismo que reemplazar la fuente de voltaje o la batería con un cortocircuito.

 

¿Qué significa apagar una fuente de corriente? Significa que hacemos I = 0 Es lo mismo que reemplazar la fuente de corriente con un circuito abierto.
 
	Usar superposición
En los siguientes dos esquemas, se apagó (suprimió) una de las entradas de voltaje al reemplazarla con un cortocircuito.
 
Cuando igualamos a cero o suprimimos una entrada, reemplazamos una de las entradas con 000, permitiendo que la entrada que queda brille por sí sola.
 
Ahora resolvemos cada circuito de manera individual:
 


donde i_1 es la corriente causada por la fuente Vs1 e i_2   es la corriente causada por la fuente Vs2.
La corriente total viene de sobreponer (sumar) las corrientes de cada circuito.
 
 (solución por superposición)
Como podemos observar la solución por superposición es igual a la solución convencional obtenida anteriormente.
Lo que hicimos aquí se llama la superposición lineal de dos circuitos.

----Material o Equipo requerido----
