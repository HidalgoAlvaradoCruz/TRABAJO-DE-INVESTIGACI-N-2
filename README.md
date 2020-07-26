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

**CONTADORES**

Los circuitos contadores son circuitos secuenciales compuestos por biestables que tienen una entrada de cuenta de impulsos (CLK) y un número de salidas que representan en cada momento, el número de impulsos que le llegan a la entrada de reloj en un código binario. Los circuitos divisores de frecuencia son circuitos que poseen una entrada por la que llega un tren de impulsos a una determinada frecuencia y disponen de una salida por la que se obtiene una frecuencia de valor n veces menor. Estos circuitos son muy utilizados en las aplicaciones que conllevan la cuenta de eventos o medición de tiempos, como es el caso de los relojes digitales, contadores de impulsos, frecuencímetros, controladores digitales y autómatas finitos.

**Características**

•	Un contador es un circuito en el que sus salidas siguen una secuencia fija que cuando acaba vuelve a empezar, o circuitos que reciben sus datos en forma serial ordenados en distintos intervalos de tiempo. 

•	Los pulsos de entrada pueden ser pulsos de reloj u originarse en una fuente externa y pueden ocurrir a intervalos de tiempo fijos o aleatorios. 

•	El número de salidas limita el máximo número que se puede contar.

**Circuito integrado 7493**

El circuito integrado 7493 contiene en su interior cuatro flip-flops JK, tal como se observa en la figura 1, que permiten utilizarlo como un contador ascendente de cuatro bits, es decir, puede realizar un conteo binario desde cero hasta quince.



**5. DIAGRAMAS**

<br>

**Diagramas Esquemático**

<br>


Contenido......

<br>

**Diagramas Eléctrico**

<br>


Contenido......

<br>

**Diagrama de bloques**

<br>


Contenido......


<br>

**6. LISTA DE COMPONENTES**

<br>

•	Laptop 

Procesador: Intel Core i5-7200U CPU @ 2.50Ghz

Memoria instalada (Ram): 8 Gb 

Tipo de sistema: 64 bits. 

Sistema operativo: Windows 8.0 en adelante. 
 
•	Software de Simulación Thinkercad 

Link: 

<br>

<br>

**7. MAPA DE VARIABLES**

<br>

Contenido......



<br>

<br>

**8. EXPLICACIÓN CÓDIGO FUENTE**

<br>

Contenido......


<br>

<br>

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

<br>

contenido...

<br>

<br>

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

<br>

contenido....




<br>

<br>

**15. ANEXOS**

<br>

contenido....





<br>

<br>

**15.1 MANUAL DE USUARIO**

<br>

contenido....

<br>

<br>

**15.2 HOJAS TÉCNICAS**





