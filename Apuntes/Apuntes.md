[LINK](http://jamj2000.github.io/entornosdesarrollo/1/diapositivas#/)

## Tipos de software
* De sistema (sistemes operatius, drivers)
* De aplicación (navegador, edició d'imatge, aplicaciones de ofimatica,etc)
* De desarrollo (editores, compialdores, etc.)

## Relación hardware-software

+ **Disco duro:** es donde se almacenan los archivos ejecutables y los archivos de datos para usarlos.
+ **Memoria RAM:** al ser una memoria volátil, se almacena de forma temporal el código binario de los archivos ejecutables y de los archivos de datos necesarios.
+ **CPU:** es la encargada de leer y ejecutar las instrucciones que se han almacenado en la RAM.
+ **E/S:** recoge los datos nuevos desde los dispositivos de entrada, se leen/guardan a disco.

## Códigos fuente

+ **Código fuente:** Es un archivo de texto escrito por un humano para poder ser comprendida.
+ **Código objeto:** Es el archivo binario (0,1), no ejecutable.
+ **Código ejecutable:** Es el archivo binario (0,1), convertido para poder ser ejecutable.

## Desarrollo de software
Las fases principales són:

+ **Análisis:** se identifica la necesidad del cliente y se determina los requisitos que tiene que cumplir el software para cumplir con estas necesidades.
+ **Diseño:** se organiza el sistema para poder desarrollar cada parte por separado.
+ **Codificación:** se programa/se escribe el código fuente del programa.
+ **Pruebas:** el objetivo con las pruebas es conseguir que el programa funcione incorrectamente y se consiga descubrir los defectos.
+ **Mantenimiento:** mientras se va usando el programa, hay que ir realizando cambios ocasionales para arreglar cosas que no se descubrieron durante la fase de pruebas, o para sacar mejoras para el programa. Hay diferente tipos de mantenimiento:
  + **Correctivo:** simplemente se corrigen errores del programa
  + **Perfectivo:** se mejora la funcionalidad del programa
  + **Evolutivo:** se añaden funciones que antes no tenía el programa
  + **Adaptivo:** se adapta a nuevos sistemas operativos o a nuevos entornos en las que podrá ser ejecutado el programa
  
### Resultado obtenido después de cada fase de desarrollo

+ **Ingeniería de sistemas:** Se definen las especificaciónes del sistema
+ **Análisis:** Se definen los requisitos del software
+ **DISEÑO arquitectónico:** Se crea un esquema esqueletico de como funcionara el programa
+ **DISEÑO detallado:** Se definen los módulos y las funciones
+ **Codificación:** És el codigo fuente del programa que se habrá escrito
+ **PRUEBAS de unidades:** Se prueban los módulos que se van a usar
+ **PRUEBAS de integración:** Se prueba que se pueda instalar y funcionar correctamente sobre el sistema que esta pensado el programa
+ **PRUEBAS del sistema:** Se mirará de ver si se acepta o no el sistema recomendado
+ **Documentación:** Se crea la documentación tanto técnica como la del usuario
+ **Mantenimiento:** Se generan los informes de errores y los controles de cambio.

## Tipos de desarrollo de software

+ **Modelo clásico:** Este tipo de modelo, tiene dos tipo de modelos dentro, el **Modelo en cascada**, el cual és el modelo más viejo y el menos usado, ya que en este modelo no puedes avanzar al siguiente punto hasta no acabar el punto en el que estas. És también muy malo en cuanto a cambios, ya que si queremos modificar algo de un punto anterior tenemos que deshacer todo los puntos hasta ese.  
También está el **Modelo en V**, en la que en el brazo izquierdo se hace todo el análisis, el diseño el desarrollo y por último la implantación de todo el programa, en canvio en el brazo derecho, se hacen todas las pruebas del programa que iran relacionadas con las partes del brazo izquierdo:

![image](http://jamj2000.github.io/entornosdesarrollo/1/assets/v.png)

+ **Modelo de construcción de prototipos:** és un modelo que se basa en crear prototipos durante la fase de análisis para usuarios que no saben que tiene que tener el programa, e ir probando junto al cliente las cosas que le gustan e ir mejorando las que no quiere o sacar-las del todo.  
Hay diferentes tipos de prototipos, el **prototipo rápido**, que simplemente consiste en crear prototipos para que el cliente lo vea, con el lenguaje de codificación que sea, estos prototipos podrán ser desechadas en el programa final.  
También está el **prototipo evolutivo**, que és el primer prototipo que se desarrolla y se irá mejorando, el producto final se basará en este prototipo.

+ **Modelos evolutivos o incrementales:** este modelo como el modelo clásico tiene dos variantes, el **modelo en espiral** y las **metodologias ágiles**.

El **modelo en espiral**, se dedica a hacer una primera comunicación con el cliente para saber que es lo que quiere, luego planificar como harás el producto, ir analizando los riesgos del programa, hacer la ingenieria dle programa, construir o programar y por último una evaluación del cliente para saber que opina del producto, todo esto lo iremos repetiendo 4 veces para al final dar el producto final:

![image](http://jamj2000.github.io/entornosdesarrollo/1/assets/espiral.png)

  
Las **metodologias ágiles**, són las más nuevas, que se basan en el desarrollo incremental del software. Ir haciendo cada parte del trabajo por partes pequeñas y con una fecha límite. Este tipo de trabajos suele ser con un equipo organizado para ir avanzando rápidamente la faena. Las metodologías más conocidas son: **Kanban**, **Scrum** y **XP (eXtreme Programming)**
