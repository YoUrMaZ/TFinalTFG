## Índice
- [1. Introducción](#introduccion) 																
- [2. Tecnologías escogidas y justificación](#tecnologias_escogidas)  						       	   	  
  - [2.1. Tecnologías FrontEnd](#tecnologias_escogidas_1)
  - [2.1. Tecnologías FrontEnd](#tecnologias_escogidas_2) 
- [3. ¿Por qué he elegido este proyecto?](#por_que_elegir)
  - [3.1. ¿Cómo está el mercado respecto a este tipo de proyecto que se desea desarrollar?](#mercado_desarrollo) 
  - [3.2. Objetivo del proyecto](#objetivo)  	
  - [3.3. Planificación](#planificacion)  					    		  
- [4. Diseño de la aplicación](#diseno)  										  
  - [4.1. Diagrama de flujo](#casos_uso) 								     	  
  - [4.2. Prototipo de pantallas](#prototipo) 

  - [4.3. Inserción del código](#modelo) 
					    	  						 
- [5. Implementación y documentación](#arquitectura)   						         	   		 
  - [5.1. Estructura del proyecto](#estructura)  						         		 
  - [5.2. Recursos externos](#recursos)  	

  - [5.3. Implementación del diseño responsive](#recursos)

   - [5.3.1 Funcionamiento](#recursos)	
		
- [6. Manual de la aplicación](#despliegue)   

- [6. Despliegue de la aplicación](#despliegue)   	

- [6. Resultados y discusión](#despliegue)   	

- [6. Conclusiones](#despliegue)   	
	  									       
<a name="introduccion"></a>						     		
## 1. Introducción 	
La propuesta consiste en el desarrollo de una aplicación web destinado a crear una 
plataforma de videos de forma estática, donde podrás navegar a diferentes sitios y a 
diferentes categorías, con una gran variedad de videos. 
Está pensado para que el usuario conozca contenido que no sabía que iba a ver y que les 
salga contenido relacionado con lo que está viendo, de la misma temática, con lo que es 
importante centrarse en eso, y en que sea lo más interactiva posible.
Esta aplicación se desarrollará en la web, lo que quiere decir que no es necesario instalar 
ningún tipo de software en su equipo informático y con el único requisito de tener un 
acceso a internet y un navegador web.


<a name="tecnologias_escogidas"></a>						     		
## 2. Tecnologías escogidas y justificación

<a name="tecnologias_escogidas_1"></a>
### 2.1 Tecnologias FrontEnd

Son aquellas que se utilizan en el lado Cliente, las que se utilizan en los diferentes dispositivos que utilizamos para conectarnos con el servidor a través de internet. Las tecnologías usadas son:

- HTML5

HTML, siglas de HyperText Markup Language (Lenguaje de Marcas de Hipertexto), es el lenguaje de marcado predominante para la construcción de páginas Web. Es usado para describir la estructura y el contenido en forma de texto, así como para complementar el texto con objetos tales como imágenes. HTML se escribe en formade "etiquetas", rodeadas por corchetes angulares (<,>). HTML también puede describir, hasta un cierto punto, la apariencia de un documento, y puede incluir un script (por ejemplo, JavaScript), el cual puede afectar el comportamiento de navegadores Web y otros procesadores de HTML.HTML también es usado para referirse al contenido del tipo de MIME text/html o todavía más ampliamente como un término genérico para el HTML, ya sea en forma descendida del XML (como XHTML 1.0 y posteriores) o en forma descendida directamente de SGML (como HTML 4.01 y anteriores). Por convención, los archivos de formato HTML usan la extensión .htm o .html

- CSS

HTML, siglas de HyperText Markup Language (Lenguaje de Marcas de Hipertexto), es el lenguaje de marcado predominante para la 
construcción de páginas Web. Es usado para describir la estructura y 
el contenido en forma de texto, así como para complementar el texto 
con objetos tales como imágenes. 
HTML se escribe en formade "etiquetas", rodeadas por corchetes 
angulares (<,>). HTML también puede describir, hasta un cierto punto, la apariencia de un 
documento, y puede incluir un script (por ejemplo, JavaScript), el cual puede afectar el 
comportamiento de navegadores Web y otros procesadores de HTML.
HTML también es usado para referirse al contenido del tipo de MIME text/html o todavía 
más ampliamente como un término genérico para el HTML, ya sea en forma descendida 
del XML (como XHTML 1.0 y posteriores) o en forma descendida directamente de SGML 
(como HTML 4.01 y anteriores). Por convención, los archivos de formato HTML usan la 
extensión .htm o .html


- JQuery

HTML, siglas de HyperText Markup Language (Lenguaje de Marcas 
de Hipertexto), es el lenguaje de marcado predominante para la 
construcción de páginas Web. Es usado para describir la estructura y 
el contenido en forma de texto, así como para complementar el texto 
con objetos tales como imágenes. 
HTML se escribe en formade "etiquetas", rodeadas por corchetes 
angulares (<,>). HTML también puede describir, hasta un cierto punto, la apariencia de un 
documento, y puede incluir un script (por ejemplo, JavaScript), el cual puede afectar el 
comportamiento de navegadores Web y otros procesadores de HTML.
HTML también es usado para referirse al contenido del tipo de MIME text/html o todavía 
más ampliamente como un término genérico para el HTML, ya sea en forma descendida 
del XML (como XHTML 1.0 y posteriores) o en forma descendida directamente de SGML 
(como HTML 4.01 y anteriores). Por convención, los archivos de formato HTML usan la 
extensión .htm o .html

- BxSlider

Permite transición vertical y horizontal. Las diapositivas 
pueden contener imágenes, videos o contenido HTML. 
Advanced touch / golpe soporte incorporado. Utiliza 
transiciones CSS para animación de diapositivas

<a name="tecnologias_escogidas_2"></a>
### 2.1 Tecnologias BackEnd

Son aquellas que se utilizan en el lado Servidor, las que 
utiliza el Servidor para gestionar las diferentes peticiones de información que le 
llegan y para gestionar las bases de datos alojadas en los mismos. Los usados son:

- JavaScript
				 
JavaScript es un lenguaje de programación 
interpretado, es decir, que no requiere
compilación, utilizado principalmente en páginas 
Web, con una sintaxis semejante ala del lenguaje 
Java y el lenguaje C. 
Al igual que Java, JavaScript es un lenguaje 
orientado a objetos propiamente dicho, ya que dispone de Herencia, si bien ésta se realiza 
siguiendo el paradigma de programación basada en prototipos, ya que las nuevas clases 
se generan clonándolas clases base (prototipos) y extendiendo su funcionalidad. 
Todos los navegadores modernos interpretan el código JavaScript integrado dentro de las 
páginas Web. Para interactuar con una página Web se provee al lenguaje JavaScript de 
una implementación del DOM	

- JSON
				 
JSON, que significa JavaScript Object Notation, es 
una formatación usada para estructurar datos en 
forma de texto y transmitirlos de un sistema a otro, 
como en aplicaciones cliente-servidor o en 
aplicaciones móviles.
Una manera de emplearlo es a través de requisiciones AJAX, en que la aplicación 
recupera los datos almacenados en el servidor de hosting sin la necesidad de recargar la 
página.
La especificación del archivo JSON surgió alrededor del año 200, pero solo pasó a formar 
parte del lenguaje JavaScript después del lanzamiento de la versión 5 del ECMAScript.
Actualmente, diversos tipos de lenguaje de programación soportan este formato, además 
de ser una alternativa más liviana que el modelo XML.
				      
- AJAX
				 
AJAX, acrónimo de Asynchronous JavaScript And XML (JavaScript 
asíncrono y XML), es una técnica de desarrollo Web para crear
aplicaciones interactivas oRIA (RichInternet Applications). Estas 
aplicaciones se ejecutan en el cliente, es decir, en el navegador de los 
usuarios mientras se mantiene la comunicación asíncrona con el 
servidor en segundo plano. De esta forma es posible realizar cambios 
sobre las páginas sin necesidad de recargarlas, lo que significa 
aumentar la interactividad, velocidad y usabilidad en las aplicaciones. 
Ajax es una tecnología asíncrona, en el sentido de que los datos 
adicionales se requieren al servidor y se cargan en segundo plano sin interferir con la 
visualización ni el comportamiento de la página. 
JavaScript es el lenguaje interpretado (scripting language) en el que normalmente se 
efectúan las funciones de llamada de Ajax mientras que el acceso a los datos se realiza 
mediante XMLHttpRequest, objeto disponible en los navegadores actuales. En cualquier 
caso, no es necesario que el contenido asíncrono esté formateado en XML. Ajax es una 
técnica válida para múltiples plataformas y utilizable en muchos sistemas operativos y 
navegadores dado que está basado en estándares abiertos como JavaScript y Document 
Object Model (DOM).				      
				      
<a name="por_que_elegir"></a>						     		
## 1. ¿Por qué he elegido este proyecto?	

Llevo pensando desde hace tiempo pensando en hacer una plataforma de videos, y me 
supone un gran reto ya que amplia muchos temas y es muy extenso, también no tiene 
límites para seguir extendiéndolo.


<a name="mercado_desarrollo"></a>
### 3.1 ¿Cómo está el mercado respecto a este tipo de proyecto que se desea desarrollar?

Crear una plataforma de videos es algo que requiere mucho tiempo, tanto para crearse 
como para comprobar de que no se tiene ningún problema, pero he visto ciertos puntos a 
destacar:
	 
• Como bien dije antes, se requiere mucho tiempo por si hay algún problema, pero la 
ventaja de esto es que está disponible las 24 horas y los 365 días del año, lo que 
me permitirá tener mi plataforma de videos permanentemente.
	 
• Ahorro en gastos no implica en incurrir en gastos de licencias de apertura, local 
físico...
	 
• Análisis completo y detalla de los clientes, ya que la analítica web y marketing digital 
permiten profundizar en el análisis del cliente, su comportamiento, gustos y 
preferencias. El fin es localizar los puntos fuertes y los puntos en los que se puede 
mejorar para el contenido y la publicidad añadida en sitios estratégicos
	 
• Anticipación a la competencia, donde la tecnología y el mundo avanza a pasos 
agigantados, es importante estar en continua actualización por lo que cuanto antes 
nos adaptemos a los nuevos cambios mayor ventaja compet	 
	 
<a name="objetivo"></a>
### 3.2 Objetivo del proyecto

La razón de la elaboración de este proyecto viene dada por la necesidad que tienen los 
usuarios de internet de usar su tiempo libre para ver videos, de consultar algún video para 
alguna necesidad que tenga y sobre todo en formato móvil, y al ver que tantas personas 
usan las redes sociales tanto, pues queremos generar interés en nuestro contenido 
desarrollando el diseño móvil y de la web de una forma diferente a la competencia 

<a name="planificacion"></a>
### 3.3 Planificación

A continuación, escribiré todas las historias de usuario empleadas en el proyecto, y el 
proceso que he llevado hasta el producto final:
1. Creación del icono con Canva de HiVideo Sport

2. Implementación de los botones de las redes sociales

3. Añadir el color al header junto con el botón izquierdo del menú

4. Añadir el tamaño, el color y las dimensiones que va a ocupar el sidebar 

5. Creaciones de los botones para las categorías (dentro del sidebar

6. Empleo de JavaScript (clase de css: .smallSidebar) para que el botón que está en el 
header llame al sidebar y si haga más pequeño, y luego que el contenido 
únicamente salga las fotos de cada uno, tapando el texto

7. Crear otra funcion para que cuando se vuelva “pequeño el sidebar”, se vuelva más 
grande el main (clase de css: .largeContainer)

8. Creación de los JSONs que será la información que permitirá pintar todas las 
pantallas

9. Idear una estructura para que cuando cree los renders de pueda “navegar” en base 
a la estructura de carpetas que tenga.

10. Crear un render principal para que me lea los jsons y que cada vez que se cumpla la 
condición [./json/(carpeta padre) /all /0.js] que me los separe en el index.html cada 
vez que entre en una carpeta padre (por la jerarquía establecida), y aparezca el 
nombre de la categoría y sus videos correspondientes 

11. Usare CSS flex para que se acomode a los tamaños de la pantalla, quiero q entren 
4 videos en tamaño pc y también hacer tamaño responsive de ello. 

12. Si me los pinta, luego que se redireccione en la página detalles con su item 
correspondiente (añadiremos un identificador para cada item y se llamara índex)

13. Pintar la página principal correctamente

14. Crear otro render para que me lea los canales del sidebar y que cada vez que se 
cumpla la condición [./json/(carpeta padre) /canales.js] me pinte unos canales u 
otros en funcion de lo que se ponga en la categoría (en la query)

15. Poner un slider con JQuery debido a que la informacion se pinta con este. Usare 
bxslider y estableceré un atributo del cual según pongas una cosa u otra se te 
pintará en el slider

16. Que la informacion no se repita en el slider y en el mosaico que cree

17. Hacer el detalles.html que es la página donde se pintará el video elegido en el 
index.html; copiar la base del header y del sidebar (quiero que cuando estes dentro 
de un video me sigas cargando los canales de la categoría. Ejemplo: 
categoría=baloncesto, y se me pinten todos los de baloncesto aun estando en el 
video).

18. Crear otro render para los detalles. Este a diferencia del otro render que necesite en 
la página principal, este no se recorrería todo, si no que se necesita que se 
seleccione un solo objeto JSON, priorizare el orden de cada json para leerlos uno a 
uno, como empieza a leerlo desde 0 (que sería el primer elemento) lo sincronizaré 
con el atributo nuevo (índex) que añadí a cada objeto JSON.
Todo esto servirá para cuando pongas en la query 
(category=futbol&channel=as&page=0&item=0) se me lea el primer elemento
del JSON, y como en la página principal, para pintar el mosaico, tiene ya un atributo 
llamado (índex) este será el que se pase en la query 
(category=futbol&channel=as&page=0&item=(índex)) 

19. Crear el render que sale los videos recomendados en la parte derecha, pondré 6 
videos aleatorios escogidos de las categorías creadas. Se pondrá en la ruta 
[./json/(carpeta padre) /recomendado.js], se cambiará cada vez que se cambia de 
categoría, y cada vez que se selecciona un item se cargará el render de 
recomendados. Ejemplo: (category=futbol&channel=as&page=0&item=0)

20. Acomodarlo en la pantalla el video juntos con los recomendados y sus títulos 
correspondientes

21. Ahora meter el canal del video junto con su imagen en grande cada vez que se 
cargue un video que aparezca su canal correspondiente [./json/(carpeta padre) 
/(canal)/detalleCanal.js] 

22. Ahora debajo de esto introducir algunos videos del canal, sería más o menos el 
mismo procedimiento que en el anterior paso a diferencia de la ruta que sería esta: 
[./json/(carpeta padre) /(canal)/videosCanal.js]

23. Hacer el tamaño responsive de los detalles

24. Crear el channel.html, sería reusar lo que hemos usado en el header y en el sidebar

25. Ahora lo que pintaremos será el cover, el canal en grande con su nombre y sus 
subscripciones y todos los videos que tenga ese canal. Para ello reusaremos todos 
los renders, ya que tiene una estructura parecida a la de los detalles
		  
<a name="diseno"></a>						     		
## 4. Diseño de la aplicación

<a name="casos_uso"></a>
### 4.1 Diagrama de flujo		
			       
![Imagen](Imagenes/Flujo.png)

<a name="prototipo"></a>
### 4.2 Prototipo de pantallas	

A continuación, mostraré las tres pantallas que habrá en mi proyecto. Estas serán las 
versiones finales
1. Esta será la página principal

![Imagen](Imagenes/Balsamic1.png)

2. Esta será la página de detalles para cuando le des a un video y quieras reproducirlo
![Imagen](Imagenes/Balsamic2.png)

3. Este apartado es el canal con todos los videos 
![Imagen](Imagenes/Balsamic3.png)
	 						  
