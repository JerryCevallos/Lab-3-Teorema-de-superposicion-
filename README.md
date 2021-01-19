# Lab-3-Teorema-de-Superposicion-

--------Teorema de Superposicion -------

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

![1](https://user-images.githubusercontent.com/75337022/104976231-baf7cd00-59ca-11eb-96e3-94e07303f14a.png)
 
Escrito como una función, nuestro resistor es

![2](https://user-images.githubusercontent.com/75337022/104976238-c21edb00-59ca-11eb-8cec-fe5bc02c2508.png)
 
Con esta notación, vemos al resistor como una función que toma como entrada un voltaje y tiene como salida una corriente.

	Un resistor es una función lineal
	
Al ver nuestra función para el resistor, observamos que tiene la propiedad de escalamiento: la salida i , equivale a la entrada, v , escalada por una constante R. Eso significa que el resistor es lineal. La propiedad de linealidad es lo que dispara nuestra habilidad de usar la superposición para ayudarnos a resolver un circuito.

	Usar superposición para ayudarnos a resolver un circuito
	
Para entender mejor utilizaremos este ejemplo, suponemos que la entrada de nuestra función consiste de dos voltajes en serie:

![3](https://user-images.githubusercontent.com/75337022/104976254-c814bc00-59ca-11eb-9d28-f73be0f5d957.png)

  
La entrada para nuestra función consiste de dos baterías en serie:
 
 ![4](https://user-images.githubusercontent.com/75337022/104976263-cf3bca00-59ca-11eb-95d8-1dd62de087a0.png)
 
La función es 

![5](https://user-images.githubusercontent.com/75337022/104976279-d662d800-59ca-11eb-9740-faa5c58d107c.png)
 
La salida de la función no ha cambiado; todavía es i=f(v)
Ahora resolvemos este circuito de dos maneras: primero por medio de un análisis convencional, y después usando el principio de superposición.

	Solución convencional
	
Para resolver por medios convencionales, escribimos las ecuaciones de la LVK alrededor del lazo:

![6](https://user-images.githubusercontent.com/75337022/104976291-de227c80-59ca-11eb-85c9-06a45a0398d7.png)

y despejamos i:

![7](https://user-images.githubusercontent.com/75337022/104976303-e7134e00-59ca-11eb-8867-f0e26d4289f7.png)
 
 (solución convencional)
 
	Solución usando el principio de superposición
	
El principio de superposición se aplica a una función lineal, f.

![8](https://user-images.githubusercontent.com/75337022/104976312-eed2f280-59ca-11eb-936f-dc10796abb40.png)
 
Entonces tenemos dos entradas superpuestas, (x_1+ x_2), puedes aplicar una entrada a la vez,  (x_1) seguida de 〖(x〗_2) y después sumar los resultados individuales para obtener la respuesta completa.

Ahora usemos el principio de superposición para resolver el circuito. Como modelamos nuestro circuito como una función, podemos decir que:

![9](https://user-images.githubusercontent.com/75337022/104976325-f5616a00-59ca-11eb-8afe-91433b81a01b.png)
 
es lo mismo que

![10](https://user-images.githubusercontent.com/75337022/104976335-fe523b80-59ca-11eb-9783-99892c18ef18.png)
 
Esto sugiere una posibilidad interesante. Dice que podemos calcular la corriente de salida de la manera convencional al aplicar las entradas combinadas  f(Vs1+Vs2), o podríamos obtener la misma respuesta al calcular la función con entradas individuales f(Vs1) y f(Vs2) sumando los resultados. 

	Suprimir entradas
	
Para aplicar la superposición necesitamos aplicar las entradas una a la vez. Eso significa que tenemos que apagar todas las entradas excepto una. Cuando apagamos una entrada decimos que está suprimida.

¿Qué significa apagar una fuente de voltaje? Significa que hacemos V =0 Esto es lo mismo que reemplazar la fuente de voltaje o la batería con un cortocircuito.

![11](https://user-images.githubusercontent.com/75337022/104977188-f09db580-59cc-11eb-93ee-ca620075a987.png)

¿Qué significa apagar una fuente de corriente? Significa que hacemos I = 0 Es lo mismo que reemplazar la fuente de corriente con un circuito abierto.

![12](https://user-images.githubusercontent.com/75337022/104977199-f7c4c380-59cc-11eb-9ba1-eb6bbb50fad7.png)
 
	Usar superposición
	
En los siguientes dos esquemas, se apagó (suprimió) una de las entradas de voltaje al reemplazarla con un cortocircuito.

![13](https://user-images.githubusercontent.com/75337022/104977215-fe533b00-59cc-11eb-854f-d3fa73163703.png)
 
Cuando igualamos a cero o suprimimos una entrada, reemplazamos una de las entradas con 000, permitiendo que la entrada que queda brille por sí sola.

![14](https://user-images.githubusercontent.com/75337022/104977227-057a4900-59cd-11eb-943c-3015d64076ed.png)
 
Ahora resolvemos cada circuito de manera individual:

![15](https://user-images.githubusercontent.com/75337022/104977243-0f03b100-59cd-11eb-8ef5-cc0b42d181ca.png)


donde i_1 es la corriente causada por la fuente Vs1 e i_2   es la corriente causada por la fuente Vs2.
La corriente total viene de sobreponer (sumar) las corrientes de cada circuito.

![16](https://user-images.githubusercontent.com/75337022/104977251-16c35580-59cd-11eb-81ad-973701aca17c.png)
 
 (solución por superposición)
 
Como podemos observar la solución por superposición es igual a la solución convencional obtenida anteriormente.
Lo que hicimos aquí se llama la superposición lineal de dos circuitos.

----Material o Equipo requerido----

![Material o equipo](https://user-images.githubusercontent.com/75337022/104977489-a8cb5e00-59cd-11eb-8517-56036614a4f6.png)

----Diagramas----

![Diagrama](https://user-images.githubusercontent.com/75337022/104977556-cf899480-59cd-11eb-8d2c-737e733ed77c.png)

----Tabulacion de datos---

![Tabulacion de datos](https://user-images.githubusercontent.com/75337022/104977566-d6b0a280-59cd-11eb-9e95-8e42f5ab3dfc.png)

----Calcul y errores----

![Calculo fuente 1](https://user-images.githubusercontent.com/75337022/104977596-e5975500-59cd-11eb-9b10-6a16c65db8c4.png)

![Calculos fuente 2](https://user-images.githubusercontent.com/75337022/104977615-ecbe6300-59cd-11eb-9168-e744093c13d2.png)

![Errores voltaje y corriente](https://user-images.githubusercontent.com/75337022/104977623-f2b44400-59cd-11eb-9d8f-a53aaab2e60e.png)

![Errores ix y va](https://user-images.githubusercontent.com/75337022/104977636-f942bb80-59cd-11eb-8743-80a09c63ac63.png)

----Conclusiones----

•	Al momento realizar la practica hemos llegado a la conclusión de que al utilizar el teorema podemos trabajar con circuitos que tengan más de una fuente de carga conectada a él, pues estos pueden ser separados y al momento de sumarlos se puede dar cuenta que existe una precisión muy grande entre ellos 

•	Podemos comprobar con las tablas comparativas que este teorema es como una propiedad matemática viéndolo desde otro punto de vista el cual señala que la suma de los factores es igual a el factor total.

---Recomendaciones----

•	Realizar ejercicios donde se tenga que trabajar con circuitos que tengas más de dos fuentes ya que como sabemos el número de fuentes será el número de sub-circuitos con os que vamos a trabajar mejorando nuestra comprensión y elaboración de las ecuaciones para hallar los valores previamente solicitados

•	Tomar en cuenta que cuando tenemos una fuente de voltaje esta mismo se cierra o en otras palabras se cortocircuita y cuando tenemos una fuente de corriente esta se abre

---Bibliografia----

Khan Academy, 2021, Ciencia, Ingeniería Eléctrica, Análisis de circuitos, Análisis de circuitos de corriente directa: 
https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-

Ing. Darwin, 2019, TEOREMA DE SUPERPOSICIÓN (circuitos eléctricos) - EJEMPLO 1: https://www.youtube.com/watch?v=Ygx2dQIwe7Q

----Axenos----
