##  Circuito de prueba para un contador de 4 bits con un display para visualizar la salida empleando los integrados 7493 y 4511 mediante el Software de Simulación Tinkercad

<br>

<br>

**1. PLANTEAMIENTO DEL PROBLEMA**

Se desconoce el funcionamiento, diseño y conexión de un circuito contador de 4 bits utilizando los  integrados 7493 y 4511, que se visualice en un display implementado en Thinkercad, para lo cual se formularon las siguientes preguntas: 

•	¿Cómo se diseña un circuito contador de 4 bits?

•	¿Cómo funciona un display?

•	¿Cómo funcionan los integrados 7493 y 4511?

**2. OBJETIVOS**


**Objetivo general**

Implementar en Thinkercad un circuito de prueba para un contador de 4 bits.

**Objetivos específicos**

•	Comprender la estructura básica de funcionamiento del software de simulación Thinkercad.

•	Entender el funcionamiento de un circuito contador.

•	Identificar los principales parámetros de funcionamiento del integrado 4511 y 7493. 


**3. ESTADO DEL ARTE**

<br>

En 2019, Thilanka Munasinghe, Evan W. Patton y Oshani  Seneviratne del Instituto Politécnico Rensselaer, Departamento de Tecnologías de la Información y Ciencia Cibernética en Estados Unidos, desarrollaron aplicaciones loT usando MIT App Inventor para recopilar y analizar datos de sensores de bajo costo, algoritmos de aprendizaje que han permitido la toma de decisiones basadas en sistemas a gran escala. La plataforma de desarrollo de MIT App Inventor permite crear aplicaciones utilizando varios sensores y plataformas de IoT como Raspberry Pi 2 y Android Things fáciles de programar con un enfoque en la recopilación de datos de sensores conectados en un solo ambiente (Munasinghe, 2019, p.1) [1].

Ruanqianqian Huang y Franklyn Turbak del Wellesley College, Department of Computer Science en 2019 implementaron un diseño para la conversión bidireccional entre bloques y texto para App Inventor mediante fragmentos de código visual que evitan errores semánticos sintácticos y estáticos y reducen la carga cognitiva para este fin diseñaron un sistema de modo dual para MIT App Inventor que admite representaciones textuales para bloques, espacios de trabajo, pantallas y proyectos completos que permiten la conversión bidireccional entre bloques isomórficos y representaciones de texto, permitiendo que individuos de varios niveles de experiencia en programación se relacionen con la interfaz (R. Huang,F. Turbak,2019)[2].

Lance A. Allison y Mohammad Muztaba Fuad del Departamento de Cienecias de la Computación de la Universidad Estatal de Salem en 2016, basaron su estudio en la comunicación entre aplicaciones de Android desarrolladas en App-Inventor y Android  Studio  para proporcionar diferentes funcionalidades específicas de cada plataforma al dispositivo, en Android pueden desarrollarse usando App Inventor 2 (AI) del MIT o usando IDEs como Android Studio (AS) con la ayuda del SDK de Android, la versión del App Inventor original de Google, que es un entorno de desarrollo basado en un navegador web para una forma más sencilla de desarrollar aplicaciones de Android. Con poco o ningún conocimiento de programación, uno puede desarrollar e implementar una aplicación de Android usando AI,  la mayoría de las aplicaciones desarrolladas en AI tienen que seguir una plantilla de diseño específica (Lance,2006,p.1) [3]. 

Para el trabajo de investigación presente, se utilizó el entorno de desarrollo de software MIT App Inventor dirigido a la Conversión de un "NÚMERO DECIMAL A CÓDIGO BCD" (Munasinghe,2019,p.1), el entorno de programación para el aplicativo se hizo sobre la base de MIT App Inventor (Lance,2006,p.1). El sistema tiene la capacidad de proyectar un número decimal de salida  en la pantalla del dispositivo android simulando la proyección de un display de 7 segmentos (R. Huang,F. Turbak,2019).

<br>

<br>

**4. MARCO TEÓRICO**

**TINKERCAD**

ThinkerCad es un programa o software gratuito y online creado para el desarrollo y modelado de objetos en 3D de una manera sencilla, ofrece también una posibilidad realmente interesante de montar, programar y simular circuitos incluso con Arduino al disponer de una interfaz de trabajo simple y atractiva. TinkerCAD ha sido creado por la empresa AutoDesk. 
Como ventajas se podría destacar que es sencillo de usar, tiene un aspecto atractivo y con unas pocas horas de uso se puede adquirir mucha destreza. Por otro lado, como desventaja se puede señalar que es necesario tener una cuenta de correo para darse de alta como usuario y que sólo posee una versión online. 
Para esto se debe crear una cuenta de usuario y acceder seleccionando la opción “Circuits” para empezar a crear circuitos .

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img1.png)

**CONTADORES**

Los circuitos contadores son circuitos secuenciales compuestos por biestables que tienen una entrada de cuenta de impulsos (CLK) y un número de salidas que representan en cada momento, el número de impulsos que le llegan a la entrada de reloj en un código binario. Los circuitos divisores de frecuencia son circuitos que poseen una entrada por la que llega un tren de impulsos a una determinada frecuencia y disponen de una salida por la que se obtiene una frecuencia de valor n veces menor. Estos circuitos son muy utilizados en las aplicaciones que conllevan la cuenta de eventos o medición de tiempos, como es el caso de los relojes digitales, contadores de impulsos, frecuencímetros, controladores digitales y autómatas finitos.

**Características**

•	Un contador es un circuito en el que sus salidas siguen una secuencia fija que cuando acaba vuelve a empezar, o circuitos que reciben sus datos en forma serial ordenados en distintos intervalos de tiempo. 

•	Los pulsos de entrada pueden ser pulsos de reloj u originarse en una fuente externa y pueden ocurrir a intervalos de tiempo fijos o aleatorios. 

•	El número de salidas limita el máximo número que se puede contar.

**Circuito integrado 7493**

El circuito integrado 7493 contiene en su interior cuatro flip-flops JK que permiten utilizarlo como un contador ascendente de cuatro bits, es decir, puede realizar un conteo binario desde cero hasta quince.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img2.png)

Este integrado tiene catorce pines. Los pines catorce y uno son las entradas de reloj A y B, respectivamente. Las entradas de reinicio están conformadas por los pines dos y tres, cuyos nombres son R0(1) y R0(2), respectivamente. Estos pines son las entradas a una compuerta NAND interna en el circuito integrado y cuya salida se encuentra enlazada a las entradas de reset de los cuatro flip-flops internos. Para que se efectúe un reinicio en la cuenta, R0(1) y R0(2) deben recibir una señal lógica alta. Por el contrario, si uno o ambos pines reciben una señal lógica baja, el conteo seguirá.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img33.jpg)

Los pines once, ocho, nueve y doce son nombrados QD, QC, QB y QA, respectivamente. Estas cuatro salidas se emplean para visualizar el conteo binario de cuatro bits. La salida QD es la que corresponde al bit más significativo del dato, seguido de QC, luego QB y finalmente QA como el bit menos significativo. 

Respecto a la alimentación del circuito, al pin 5 se conecta la parte positiva de la fuente de alimentación, cuyo rango debe estar entre 4.75 V y 5 V, mientras que en el pin 10, llamado GND, se conecta a la parte negativa de la fuente. Los pines restantes no requieren algún tipo de conexión.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img4.png)

Para realizar un contador ascendente de 0 a 15 utilizando el circuito integrado 7493 deben replicarse las conexiones. Primordialmente hay que conectar la entrada B a la salida QA, de esta manera todos los flip-flops estarán conectados entre sí, ya que inicialmente sólo se encuentran conectados tres de ellos. 

Utilizando una fuente de voltaje de 5V, se conecta el pin Vcc a la parte positiva y el pin GND a la parte negativa de ésta. Es necesario no dejar sin conexión los pines R0(1) y R0(2) para que la cuenta no se esté reiniciando constantemente, por lo que dichas entradas van conectadas también a la parte negativa de la fuente.La entrada A necesita una señal de reloj que genere los cambios de valor en la cuenta. Esta señal puede ser generada con un oscilador astable, como un circuito 555, o con una señal de salida que oscile, generada en un microcontrolador. Los cambios de la cuenta se generan durante los flancos de bajada de la señal. A cada una de las salidas, se conecta una resistencia de 330 Ω y un diodo led para visualizar el conteo(ejemplo).

**Circuito integrado 4511**

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img5.jpg)

El display de 7 segmentos es un componente bastante empleado en el mundo de la electrónica, ya que permite que sea muy simple la exhibición de valores numéricos. Pudiendo representar cifras de 0 a 9 

Puede ser aplicado también en ambientes industriales para ejecutar funciones como:

•	Exhibir la cuenta de piezas en un determinado proceso.

•	Exhibir la temperatura de un alto horno en la fundición de metales.

•	Exhibir las rpm de una máquina.

•	Mostrar la cantidad de aceite lubricante restante en un reservorio.

Los display de 7 segmentos son empleados la mayoría de las veces a partir de circuitos digitales como circuitos integrados, microcontroladores y otros procesos que trabajan en sistema binario, cuyo sistema y representación es apenas realizado por dos niveles lógicos 0 y 1 denominados bits. Resultando la parejas cd4511 y display 7 segmentos una herramienta muy útil para estos casos, tambien es comun el duo cd5411 y cd4510.

En el mercado se encuentra con diversos codificadores y decodificadores. Cada uno posee características específicas y limitaciones de uso, basta saber a partir de su hoja de datos cuál de ellas es la más adecuada para el proyecto.
Uno de los decodificadores bcd más utilizado para mostrar números de 0 a 9 en display de 7 segmentos cátodo común es el CD 4511.

El CD4511 es un decodificador bcd de 4 bits para display cátodo común, que utiliza tecnología cmos. Recibe en los Pines de entrada a ABCD los datos en código binario y los decodifica a código decimal, siendo posible su exhibición en los display de 7 segmentos.

 Es necesario conocer sus características físicas y limitaciones de uso que están disponibles por sus fabricantes a través de sus respectivas hojas de datos.
 
Las características más importantesn son:

•	Tensión de operación: 3V a 18V de corriente continua.

•	Corriente de salida: 10mA.

•	Temperatura de operación: -55ºC a 125ºC.

**Configuración de pines**

Cada pin de salida corresponde a un segmento del display, basta con hacer las conexiones y enviar las informaciones binarias a las entradas, luego CD4511 decodifica el código bcd y escribe la información en cifras decimales en el display.

Este Circuito integrado es especifico para trabajar con diplay de 7 segmentos de cátodo comuún, en el caso de querer usar el CD 4511 con ánodo común se debe recurrir a un circuito inversor o usar otro circuito integrador decodificador.

Se tiene a disposición 3 Pines del CD4511 que pueden tener gran aplicación en diversos proyectos, brindando funciones como:

•	Economizar Batería.

•	Registrar el ultimo dígito exhibido en el display.

•	Testear los segmentos del display, para validar su funcionamiento y el cableado.

Estos pines y su funcionamiento son:

•	Lamp Test LT(Pin 3): Este pin  sirve para probar todos los segmentos. Debido a que es una entrada inversora, para tener un funcionamiento normalizado esta entrada debe estar en 1. Cuando la entrada toma un valor lógico 0 prende todos los segmentos del display para testear el funcionamiento.

•	Blank Input BI(Pin 4): Apaga todos los segmentos, tener en cuenta que esto es una entrada inversora, por lo tanto para tener un funcionamiento normal del CI esta entrada precisa estar en 1.

•	Lath Enable LE(Pin 5): Congela el último dígito exhibido en el display 7 segmentos después de recibir un 1 lógico. Para obtener un funcionamiento normal del CD4511 esta entrada precisa estar en 0.

**TEMPORIZADOR 555** 

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img10.gif)

El temporizador 555 es un circuito integrado (chip) que se utiliza en la generación de temporizadores, pulsos y oscilaciones. El flip flop 555 puede ser utilizado para proporcionar retardos de tiempo, como un oscilador y como un circuito integrado . Sus derivados seleccionados hasta cuatro circuitos de sincronización en un solo paquete.

**Modos básicos de funcionamiento**

•	ASTABLE: Forma de onda cuadrada.

•	MONOESTABLE: Salida un solo pulso de un ancho establecido por el diseñador (tiempo duración).

**Aplicaciones**

•	Temporizador.

•	Oscilador

•	Divisor de frecuencia.

•	Modulador de frecuencia.

•	Generador de señales.

**Configuración Astable**

•	La señal de salida tiene un nivel alto por un tiempo T1 y un nivel bajo por T2.

•	Los tiempos de duración dependen de R1, R2 y C1

**Configuración Monoestable**

•	Entrega a su salida un solo pulso Talto de un ancho establecido por el diseñador.

•	Depende de R1 y C1.


**5. DIAGRAMAS**

<br>

**Diagramas Esquemático**

Explicación:


**Diagramas Eléctrico**

Explicación:
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img36.png)


**Diagrama de bloques**

Explicación:
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img36.ng)

**6. LISTA DE COMPONENTES**

<br>

•	Laptop 

Procesador: Intel Core i5-7200U CPU @ 2.50Ghz

Memoria instalada (Ram): 8 Gb 

Tipo de sistema: 64 bits. 

Sistema operativo: Windows 8.0 en adelante. 
 
•	Software de Simulación Thinkercad 

•	Especialmente del circuito:

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img22.jpeg)


**7. MAPA DE VARIABLES**

<br>

Contenido......



<br>

<br>

**8. EXPLICACIÓN DEL CIRCUITO**

El circuito se a dividido en cuatro etapas:

**Generador de pulsos**

Se utilizó el circutio integrado 555 que genera pulsos en configuración multivibrador astable es decir  mediante una onda cuadrada que se repite de forma continua siendo el estado alto 1 y el estado bajo 0, la amplitud de la onda se puede modificar mediante el potenciómetro.El esquema de conexión que se utilizó es el siguiente:

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img26.jpg) ![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img27.png)

La señal de salida tiene un nivel alto por un tiempo TH y en un nivel bajo un tiempo TL. Los tiempos de duración en segundos dependen de los valores de Ra, Rb y C.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img23.jpg)

La frecuencia con que la señal de salida oscila está dada por la fórmula:

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img24.jpg)

El 555 tiene dos entradas de control adicionales. Una entrada de reposición (RESET) que para inmediatamente la salida y la pone a nivel bajo, y una entrada de tensión de control (Cv) que puede utilizarse para variar la anchura del impulso de salida variando la tensión continua a ella aplicada, y que varía la frecuencia de oscilación.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img25.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img28.jpeg)

**Contador 7493**

Este circuito integrada codifica a BCD del o en BCD(0000) al 9 en BCD (1001) solo cuando se envía pulsos es decir se tomará en cuenta los estados bajos "0" enviados del 555 y los estados altos"1" como una espera y el tiempo que se demore en estado "1" es igual al tiempo que estará mostrando el número en el display.
Entonces el número que aparecerá en el display es la cantidad de estados bajos que ha contado en ese momento.

El esquema de conexión que se utilizó es el siguiente:

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img3.gif)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img31.jpeg)

Tabla de verdad

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img29.png)

En donde Count son la cantidad de estados bajos que ha contado provenientes del IC555 y Output son las cuatro salidas del Circuito Integrado 7493.

L= Low – Bajo – 0 lógico 

H= High- Alto – 1 lógico

En la siguiente imagen se puede apreciar los 3 pulsos negativos que ha enviado el IC555 hasta el momento, por lo tanto la salida Q0=1, Q1=1, Q2=0 y Q3=0 este es el código en BCD del número 3 es decir “0011”.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img30.png)

**Decodificador BCD a 7 segmentos**

El 4511 es un decodificador de BCD a 7 segmentos. Recibe como entradas los 4 bits de salida del contador 7493 que forman un dígito codificado en binario (BCD, Binary Coded  Digit)  y da como salida el  mismo número (dígito)  presentado en  el display de 7 segmentos.

Tabla de verdad:

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img32.jpg)

El esquema de conexión que se utilizó es el siguiente:

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img34.jpeg)![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img9.gif)

**Display 7 segmentos**

Finalmente se puede observar en el número en el display de siete segmentos con sus resistencias de protección de cada diodo.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img37.png)

Para mejor comprensión se describe el envío del CI7493 un código en BCD del número 3 que sería "0011", para verificar observar en la tabla de verdad del CI4511,el código 0011 en las entradas, estaría en estado ALTO, es decir, un 1 logico, los segmentos A, B, C, D ,G. y en estado BAJO “0 logico” los segmentos E y F.

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img38.jpeg)

Nota:Los led se utilizan para saber si el circuito integrado 555 está funcionando correctamente y solo se activan con los pulsos en estado alto.

**9. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN**

<br>

Tener una cuenta de Google o una cuenta institucional en este caso la cuenta de Mi ESPE, debido a que la verificación y creación de la cuenta en Tinkercad será a partir de esta. 

Es esencial tener una conexión estable a internet, debido que será necesario para la creación del circuito en el simulador. 
Los sistemas operativos de los computadores en los cuales funciona Tinkercad son: 

•	Macintosh (con procesador Intel): Mac OS X 10.5, 10.6

•	Windows: Windows XP, Windows Vista, Windows 7

•	GNU / Linux: Ubuntu 8 +, 5 + Debian

<br>

Tener un computador con todas las actualizaciones necesarias, como también nuestro navegador deberá tener las siguientes especificaciones: 

•	Mozilla Firefox 3.6 o superior

•	Apple Safari 5.0 o superior

•	Google Chrome 4.0 o superior

•	Microsoft Internet Explorer 7 o superior

<br>

El circuito creado en Tinkercad puede funcionar en cualquier servidor si se le da el atributo de público y se comparte el enlace que se genera, dicho enlace será la única forma en la que se pueda acceder y editar el diseño del circuito.


<br>

<br>

**10. APORTACIONES**

Implementación en físico del circuito contador

![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img12.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img13.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img14.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img15.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img16.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img17.jpeg)
**11. CONCLUSIONES**

<br>

En conclusión:

•	

•

•	

<br>

<br>

**12. RECOMENDACIONES**

<br>

•	

•

•

•

•

<br>

<br>

**13. CRONOGRAMA**

<br>

contenido....

<br>

<br>

**14. BIBLIOGRAFÍA**

[1]Marin, J. (20-12-20). Contados Ascendente. BlogSpot. http://jmaarin.blogspot.com/2017/12/contador-ascendente-con-ci-7493.html

[2]Monroy, M. (2018, 26 diciembre). Temporizador. Medium.com. https://medium.com/@m.monroyc22/temporizador-555-243abcb933a5

[3]Gonzales, R. (2019, 7 abril). Contador Binario. Electrónica Digital. https://personales.unican.es/manzanom/Planantiguo/EDigitalI/CONTG5.pdf

[4]Fuente, F. (2017, 24 enero). Decodificador bcd a 7 segmentos. Wilaeba Electronica. https://wilaebaelectronica.blogspot.com/2017/01/decodificador-bcd-a-7-segmentos.html

**15. ANEXOS**


**15.1 MANUAL DE USUARIO**


**15.2 HOJAS TÉCNICAS**
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img18.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img19.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img20.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/TRABAJO-DE-INVESTIGACION-2/blob/master/img/img21.jpeg)

